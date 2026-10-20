---
"@emdash-cms/admin": patch
---

Fixes the admin editor offering URL editing for unregistered blocks without an existing `id` or `url`, including WordPress-imported buttons. These blocks now show an unavailable-editor notice instead of saving an unrelated URL onto the block. Imported embeds and files with existing URLs remain editable. This does not add a Buttons editor or remove previously saved stray URLs.

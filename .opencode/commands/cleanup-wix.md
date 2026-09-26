---
description: Clean up generated directories to prepare the project for sharing. Keeps .env.local intact.
---

Delete the following generated directories from the project root:

- `node_modules/`
- `dist/`
- `.astro/`
- `.wix/`
- `.wrangler/`

**Important:** Do NOT delete `.env.local` or any other `.env` files.

Use `rm -rf` to remove each directory. After deletion, confirm the directories are gone.

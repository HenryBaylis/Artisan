# fork-tools

This branch only holds automation for this fork of [Artisan](https://github.com/PunishXIV/Artisan). It's the default branch because GitHub only runs scheduled workflows from there.

- `main` is an exact mirror of upstream's `main`.
- `feature/list-ipc` holds this fork's changes, rebased onto `main`: IPC functions to create, delete and cancel crafting lists (`Artisan.CreateList`, `Artisan.DeleteList`, `Artisan.CancelList`), used by [Tataru](https://github.com/HenryBaylis/Tataru).
- `.github/workflows/sync.yml` keeps both current daily and opens a "Fork sync failed" issue when a rebase conflicts or the build breaks.

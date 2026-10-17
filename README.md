# my-tasks

Single-page task list. Plain `index.html`, no build step and no dependencies.

## Running

Open `index.html` directly, or serve the folder:

```bash
npx serve .
```

## Notes

Everything is client-side and in-memory, so tasks are lost on reload. There is
no backend and no persistence - this is an early frontend exercise rather than a
finished app.

A more complete version with authentication and a database exists separately
as `task-client`.
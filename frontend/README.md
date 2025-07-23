# Notes Astro Frontend

A minimalistic, responsive note management interface built with Astro.

## Features

- Create, edit, delete, and list notes
- Responsive light-themed layout with primary (`#1e88e5`), secondary (`#43a047`), and accent (`#fdd835`) color palette
- Main layout: header with title and new note button, grid with notes list and editor/preview
- App state stored in browser (ready for backend API integration)

## Structure

- `src/pages/index.astro` &ndash; Main entry, loads the app interface
- `src/components/NotesApp.astro` &ndash; Root stateful app component
- `src/components/NoteList.astro` &ndash; Notes side-list
- `src/components/NoteEditor.astro` &ndash; Note editor (create/edit mode)
- Custom CSS matches the project's color theme and minimalist aesthetic.

## Running

```sh
npm install
npm run dev
```

App runs at [localhost:3000](http://localhost:3000) by default.


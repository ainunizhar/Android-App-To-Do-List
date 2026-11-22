# TaskMaster — Android To-Do App

**Bachelor project · Bachelor in Computer Forensic (Hons), Management and Science University (2024)**

A to-do list app for Android. Each user signs up and gets a private task list, stored on the phone in SQLite.

## Features
- **Accounts:** sign up and sign in; every account has its own SQLite database.
- **Tasks:** add or edit a task in a bottom sheet and give it a priority.
- **Swipe actions:** swipe right to edit, swipe left to delete (with a confirmation dialog).
- **Done:** tick the checkbox to mark a task complete; the status is saved.
- Custom fonts, and light and dark themes.

## Built with
Java · Android SDK (min 24, target 34) · SQLite (`SQLiteOpenHelper`) · RecyclerView + ItemTouchHelper · Material
Components

## Run it
Open the folder in Android Studio, let Gradle sync, and run it on an emulator or a phone with Android 7.0 or later.

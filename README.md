# Notes App

The Notes App is a simple web application that allows users to create, manage, and organize their notes online. Users can write down their thoughts, ideas, to-do lists, or any other important information and access them from any device with internet access.

## Features

- Create and save notes: Users can create new notes with a title and content and save them to the app.
- Pin and archive notes: Users can pin notes to keep them at the top for quick access and archive notes to hide them from the main view.
- Trash notes: Users can move notes to the trash when they are no longer needed, and the notes will be stored in the trash section until deleted permanently.
- Responsive design: The app is responsive and works seamlessly on various devices, including desktops, tablets, and smartphones.



## Technologies Used

The Notes App is built using the following technologies and React hooks:

- React.js: A JavaScript library for building user interfaces.
- React Hooks: The app uses `useState`, `useRef`, `useContext`, and `useEffect` hooks to manage state, create references, and handle side effects.
- React Router: For handling client-side routing with `BrowserRouter`, `Routes`, `Route`, and `Link` components.
- CSS: For styling the components and layout.
- Local Storage: To store notes and trash data on the user's browser.

## How to Use

1. **Create a Note**: To create a new note, click on the "New Note" button and enter a title and content for the note. Click the "Save" button to add the note to the list.

2. **Pin a Note**: Click on the pin icon (📌) next to a note to pin it. Pinned notes will appear at the top of the list.

3. **Archive a Note**: Click on the archive icon (🗑️) next to a note to archive it. Archived notes will be hidden from the main view.

4. **Move Note to Trash**: Click on the trash icon (🗑️) next to a note to move it to the trash. The note will be stored in the trash section until deleted permanently.

5. **Retrieve Notes from Trash**: To retrieve a note from the trash, go to the trash section and click the "Restore" button next to the note.

6. **Permanently Delete Notes**: To permanently delete a note, click the "Delete" button next to the note in the trash section.




# NotesApp

This is a simple notes app built using Vue.js and the Composition API. It allows users to create, edit, and delete notes.

## Project setup

1. Clone the repository:

```
git clone https://github.com/haloglu/notes-app.git
```

2. Install dependencies:

```
cd notes-app
npm install
```

2. Compile and Hot-Reload for Development:

```
npm run dev
```


## Project structure

The app consists of two main components:

1. **NotesList:** This component displays a list of all notes and allows users to create new notes.

2. **Note:** This component displays the contents of a single note and allows users to edit and delete it.

The app uses the Vuex store to manage state, with actions and mutations defined in separate files.

## Composition API

This app uses the Composition API, which is a new way of organizing component logic in Vue.js. The Composition API allows developers to use reactive state, lifecycle hooks, and other features in a more flexible and composable way.

In this app, the Composition API is used to define reactive state for the notes list and individual notes, as well as to define computed properties and lifecycle hooks.

## Conclusion

This notes app provides a simple example of how to use Vue.js and the Composition API to build a reactive and scalable application. Feel free to use this code as a starting point for your own projects!


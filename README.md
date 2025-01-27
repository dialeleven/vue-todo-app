# About VueTODO List App
Getting familiarized with Vue.js by converting a [TODO App originally created in React.js](https://github.com/dialeleven/react-todo-app-medium).

## Live Demo
Project demo has been deployed to Netlify at **[https://vue-todo-app8.netlify.app](https://vue-todo-app8.netlify.app)**.

## Screenshot
![VueTODO app screenshot](https://raw.githubusercontent.com/dialeleven/vue-todo-app/main/public/assets/screenshot_todo_app.png)

## Vue.js Concepts Used In Project
- Component based architecture (e.g. TodoList, TodoListItem, TodoListHero, TodoListModal)
- Data properties (e.g. `totalTasks` passed down to TodoListHero component)
- Computed properties: to derive new values based on existing data properties (e.g. `completedTasks` and `totalTasks` computed from the tasks array)
- Methods (e.g. handleShow, handleFilterChange)
- Event handling (e.g. @click, @keydown)
- Lifecycle hooks (using `watch` to track changes to `showModal` to update the todo task input and duedate on edit action)
- Conditional rendering with the `v-if` directive
- Use of the vuedraggable.next component for drag-and-drop sorting

## VueTodo App - Todo List
- [x] Drag and drop reordering of todo with [vue.draggable.next](https://github.com/SortableJS/vue.draggable.next)
- [x] Autofocus text input
- [x] Handle Enter key
- [x] Deploy project online (e.g Netlify)
- [x] <script setup> version for all components vs <script>

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

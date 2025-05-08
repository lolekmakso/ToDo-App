# ✅ React Todo App with API

A modern and feature-rich Todo application built with React and TypeScript.
It offers full CRUD functionality via API, user authentication, and a smooth user experience with loading indicators, notifications, and task filtering.

## 🌐 Live Demo

- 🔗 [Live Demo](https://lolekmakso.github.io/ToDo-App/)
- 🧪 API-based app with persistent todos per user

## 📦 Repository

- 📁 [GitHub Repo](https://github.com/lolekmakso/ToDo-App.git)

## 🛠️ Stack & Tools

- **React (Hooks)** — component-based UI architecture
- **TypeScript** — static typing for safer and more maintainable code
- **React Context (useContext)** — global state management for user data
- **SCSS Modules** — modular and maintainable styling
- **Fetch API** — communicates with the backend server
- **classnames** — utility for dynamic class name binding
- **Vite** — blazing fast development and build tool
- **Prettier** — automatic code formatting on save

## ✨ Key Features

- 👤 **User Authentication** — supports sign-up and login; todos are tied to the logged-in user
- 📡 **API Integration** — todos are fetched automatically when the app loads
- ➕ **Task Creation** — add new todos with input validation and async UI feedback
- ❌ **Task Deletion** — remove tasks with visual loading indicators and error handling
- 📝 **Inline Editing** — rename todos directly within the list
- 🔄 **Status Toggle** — switch individual tasks or toggle all at once
- 🧽 **Clear Completed** — remove all completed tasks in one action
- 🔍 **Filtering** — view tasks by All, Active, or Completed status
- ⚠️ **Error Handling** — notifications appear on API errors and auto-dismiss after a few seconds
- ⏳ **Loading States** — spinners and overlays for better UX during API calls

## 🖼️ Screenshot

![Todo App Screenshot](./todoapp.gif)

## 🚀 Getting Started

To run the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/lolekmakso/ToDo-App.git
   cd ToDo-App
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

## ✅ UX & Logic Considerations

- Input disabled while async actions are in progress
- Prevents accidental double submissions
- Focus returns to input on success
- Loader overlays used on todos during update/delete
- API errors show non-intrusive notifications
- Edge cases covered (empty titles, repeat edits, batch operations)

## 📬 Contact Me

- 💬 Telegram: [@lolekmakso](https://t.me/lolekmakso)
- 📧 Email: [makstarasovv1@gmail.com](mailto:makstarasovv1@gmail.com)

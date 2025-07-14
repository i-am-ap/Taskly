# **✅Taskly📋**

A dynamic and interactive Todo List application built with React and Vite. The app enables users to efficiently manage their tasks by adding, ticking/unticking, and removing todos. Task counts are updated in real time, and the application leverages local storage to maintain state between sessions.

---

🚀 Live Demo: [Taskly is deployed on Vercel](https://taskly-psi-three.vercel.app/)

---

## **Features**
- **Add Tasks:** Dynamically add new tasks to the list.
- **Mark as Done/Undone:** Toggle tasks as completed or incomplete.
- **Remove Tasks:** Easily delete tasks from the list.
- **Task Count:** Displays the total number of tasks added.
- **Persistent State:** Uses `localStorage` to save and restore tasks across sessions.
- **Responsive UI:** Built with HTML and CSS for a clean and user-friendly interface.

---

## **Technologies Used**
- **Frontend:**
  - React
  - Vite
  - JavaScript
  - HTML
  - CSS
- **State Management:** React's `useState` and `useEffect` hooks.
- **Storage:** Browser `localStorage`.

---

## **Installation**

Follow these steps to set up and run the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/todo-list-app.git
   cd todo-list-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open the app**:
   Navigate to [http://localhost:5173](http://localhost:5173) in your browser.

---

## **Usage**

1. Open the application in your browser.
2. Enter a task in the input field and click **Add** to include it in the list.
3. Click on a task to **tick** or **untick** it as done.
4. Use the delete button (if implemented) to **remove** tasks from the list.
5. Observe the **task count** update dynamically with each action.

---

## **Project Structure**
```
todo-list-app/
├── public/                # Static files (assets like images, fonts, etc.)
├── node_modules/          # Installed dependencies
├── src/                   # Main application code
│   ├── components/        # Contains reusable components
│   │   ├── assets/        # Static assets specific to components
│   │   ├── CSS/           # Component-specific styles
│   │   ├── Todo.jsx       # Main Todo component
│   │   ├── TodoItems.jsx  # Component for individual todo items
│   ├── App.jsx            # Root application component
│   ├── App.css            # Global styles for the app
│   ├── index.css          # Entry point styles
│   ├── main.jsx           # Application entry point
├── index.html             # HTML template for the app
├── package.json           # Project metadata and dependencies
├── package-lock.json      # Locked versions of dependencies
├── README.md              # Project documentation
├── vite.config.js         # Vite configuration
├── .gitattributes         # Git attribute configurations
├── .gitignore             # Git ignore rules
├── eslint.config.js       # ESLint configuration

```
## 📸 Screenshots

Dashboard:
![image](https://github.com/user-attachments/assets/6e6f6c9a-1bc6-4640-8d42-44ae8478b385)
<img width="1918" height="977" alt="image" src="https://github.com/user-attachments/assets/b98bbfa4-e24b-483b-ab53-1eb09d11ef16" />




---

## **Future Enhancements**
- Add task categories or priorities.
- Implement a search or filter feature for tasks.
- Allow task editing.
- Introduce user authentication to make it multi-user.

---

## **Contributing**
Contributions, issues, and feature requests are welcome!  
1. Fork the project.  
2. Create your feature branch: `git checkout -b feature/your-feature`.  
3. Commit your changes: `git commit -m 'Add your message'`.  
4. Push to the branch: `git push origin feature/your-feature`.  
5. Open a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## **Acknowledgments**
Thanks to the React and Vite teams for their awesome tools and documentation!

---

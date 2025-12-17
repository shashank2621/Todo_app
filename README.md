# Todo_App
Here’s a *formal GitHub-ready project description* you can use in your repository’s README:

This project is a simple *React-based To-Do application* that allows users to manage tasks efficiently. It demonstrates the use of React hooks for state management, dynamic rendering of lists, and basic styling with CSS.  

## Features  
Add new tasks using an input field and button  
- Delete tasks from the list with a single click  
-  Clean, modern UI styled with CSS (card layout, shadows, spacing)  
-  Built with React and Vite for fast development and rendering  

## Tech Stack  
- *React* (functional components, hooks)  
- *JavaScript (ES6+)*  
- *CSS* (custom styling, flexbox layout)  
- *Vite* (development and build tool)  

## Project Structure  

src/
 ├── App.jsx        # Main application component
 ├── index.css      # Global styles
 ├── main.jsx       # Entry point rendering App
public/
 └── index.html     # Root HTML file


## How It Works  
1. The app uses useState to track tasks and input values.  
2. Users can add tasks via the input field; tasks are stored in an array.  
3. Each task is displayed in a styled list with a delete button.  
4. Clicking  removes the selected task from the state.  

## Installation & Usage  
```bash
# Clone the repository
git clone https://github.com/your-username/todo-app.git

# Navigate to project folder
cd todo-app

# Install dependencies
npm install

# Run the development server
npm run dev

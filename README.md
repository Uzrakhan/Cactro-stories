📱 **Instagram Stories — React + Tailwind**

A mobile-first Instagram-style Stories feature built with React and Tailwind CSS.
Users can browse horizontally through stories, open them fullscreen, auto-play content, and manually navigate — just like the real app.

-------------

🚀 **FEATURES**
🟣 **Stories List**

1. Mobile-only layout

2. Horizontally scrollable story bubbles

3. User avatar + username

4. New-story indicator badge

📖 **Story Viewer**

1. Full-screen immersive viewer

2. User avatar + username in header

3. Gradient overlay for readability

4. Progress bars for each story

5. Auto-advance every 5 seconds

6. Tap left / right to navigate

7. Loading spinner while media loads

8. Supports multiple users & multiple stories per user

9. Viewer closes after last story



📂 **Data Handling**

1. Story + user details loaded from an external JSON file

2. Easily scalable — add more users or stories without code changes


🎨 **Tech Used**

1. ⚛ React

2. 🎨 Tailwind CSS

3. 🚦 React Hooks: useState, useEffect

4. 📱 Mobile-first responsive UI

-------------


🛠 **Installation & Setup**
git clone <your-repo-url>

cd project-folder

npm install

npm run dev

Open in browser at: http://localhost:5173

---------

📁 **Project Structure**

src/
 ├── components/
 │    └── Stories.jsx
 ├── data/
 │    └── stories.json
 ├── main.jsx
 └── index.css

-----------
🧠 **How It Works (Short Explanation)**

State stores:

1. current user

2. current story

3. progress bar value

4. loading state

A useEffect handles auto-advance timing

Navigation resets loading + progress

When the last story ends → viewer closes

This keeps logic simple, clean, and readable.
----------

🙌 **Acknowledgements**

This project was built as part of a Ccatro Frontend Hiring Test to recreate the Instagram Stories viewing experience using React + Tailwind.
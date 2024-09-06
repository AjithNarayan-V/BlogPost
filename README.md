
# Simple Blog Platform

## Description
This project is a fully functional blog platform designed for users to create, view, and delete blog posts seamlessly. Built with a focus on modern web development practices, the platform separates the frontend and backend for a modular architecture. It leverages popular frameworks and tools, ensuring a smooth development experience and an intuitive user interface.

## Tech Stack

### Frontend:
- **Next.js**: A powerful React framework for building performant web applications. It offers features like server-side rendering (SSR) and static site generation (SSG), providing optimal page load speeds and SEO benefits.
  
- **ShadCN**: A UI library used to style components with a modern, minimalist design. It ensures the platform looks polished with responsive design patterns, making it adaptable to different screen sizes.

### Key Components:
- **Blog Card**: Displays a blog post’s title and a short excerpt. Each card links to the full post, allowing users to either view the post or delete it.
- **Header**: A simple navigation bar for quick access to different sections of the platform.
- **Form**: Used on the "Create Post" page, the form is designed to be user-friendly with fields for the blog’s title and content. Validation ensures that no field is left blank.
- **Buttons**: Custom buttons styled with ShadCN, used for actions like submitting the form or deleting a post.

### Backend:
- **Express.js** (or **Flask**): A lightweight backend framework designed to handle API requests. It serves as the middle layer between the frontend and the database, managing all server-side logic, including blog post creation, retrieval, and deletion.
  
- **REST API**: The backend provides a RESTful interface with the following endpoints:
  - `GET /posts`: Fetches all blog posts from the database.
  - `GET /posts/:id`: Retrieves a single post by its ID.
  - `POST /posts`: Allows users to create a new blog post.
  - `DELETE /posts/:id`: Deletes a blog post by its ID.

### Database:
- **SQLite**: A lightweight, file-based relational database that is perfect for small projects due to its ease of setup and low maintenance. The platform uses an SQLite database to store blog post data, with fields for `id`, `title`, and `content`.

## Features

### Core Features:
- **Home Page**: A list of all blog posts, displayed in a clean and organized manner. Each post is represented by a Blog Card, showing the title and a short excerpt.
- **Create Post Page**: Users can fill out a form to create a new blog post. Both title and content fields are required, ensuring no empty posts are created.
- **View Post Page**: When a user clicks on a blog post from the home page, they are directed to the full post’s page, displaying the post’s title and content.
- **Blog Card Component**: Cards are used to give a quick overview of each blog post. Each card provides options for viewing or deleting the post.
- **Header Component**: Simplified navigation between key pages, providing a consistent experience across the site.
- **Form Component**: A well-structured form for creating new posts. Includes built-in validation to prevent submission of incomplete posts.
- **Button Component**: Reusable buttons for various actions, such as submitting the post creation form or confirming post deletion, styled with ShadCN.

### Extra Features:
- **Responsive Design**: The platform is fully responsive, ensuring a great experience across desktop, tablet, and mobile devices.
- **Form Validation**: Frontend validation ensures that users do not leave the title or content fields empty when creating a new blog post.
- **Confirmation Modal**: A confirmation dialog appears before deleting a post, preventing accidental deletions.
- **Post Editing**: Users can edit existing posts to update the title or content if needed, enhancing the overall usability of the platform.

# Tech Stack

## Frontend:
- **Next.js**: A powerful React framework that supports server-side rendering (SSR) and static site generation (SSG), improving performance and SEO.
- **ShadCN**: A modern UI library used for styling components and providing responsive design.

## Backend:
- **Express.js**: A minimal and flexible Node.js web application framework for creating the REST API.
- **SQLite**: A lightweight relational database used to store blog post data in a file-based format.

## Additional Tools:
- **React**: Used for building interactive UI components on the frontend.
- **Node.js**: The runtime environment for running JavaScript on the backend.

## Setup Instructions

### Clone the Repository:
```bash
git clone https://github.com/yourusername/simple-blog-platform.git
```

### Navigate to the Project Directory:
```bash
cd blopost
```

### Install Frontend Dependencies:
```bash
npm install
```

### Install Backend Dependencies:
```bash
cd ../backend
npm install
```



### Run the Backend:
```bash
nodemon index.js
```

### Run the Frontend:
Open a new terminal and navigate to the frontend directory.
```bash
npm run dev
```

### Access the Platform:
The platform should be accessible at `http://localhost:3000` for the frontend and `http://localhost:8747` for the backend API.

### Application Video:
`https://drive.google.com/drive/folders/1Dd4KeT8WzjoZmDkkNGCLmIfeYaYx_4fJ?usp=sharing`

<video controls src="blogpost-video.mp4" title="Title"></video>

### Application Images:
- **Home page**
![alt text](image.png)
![alt text](image-1.png)
- **Create Post Page**
![alt text](image-2.png)
![alt text](image-3.png)
- **View Post Page**
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
- **delete confirmation**
![alt text](image-7.png)
- **About Page**
![alt text](image-8.png)
![alt text](image-9.png)
- **contact us page**
![alt text](image-10.png)

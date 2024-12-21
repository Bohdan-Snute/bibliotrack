# Book Tracking System 📚  

## Project Overview  
The Book Tracking System is a full-stack application designed to help users manage their book collections and reading habits. With this system, users can:  
- **Add Books**: Build a personal library by adding books with details like title, author, genre, and description.  
- **Mark Books as Read**: Track your reading progress and maintain a list of completed books.  
- **Wishlist Management**: Organize books you'd like to read in the future.  
- **Search and Filter**: Effortlessly find books based on title, genre, or author.  
- **Leave Reviews**: Share your thoughts and read others' reviews for better insights.  

---

## Technologies Used  

### Frontend  
- **Framework**: Angular 2+ (TypeScript)  
- **UI Library**: Angular Material for polished and consistent design components.  
- **Styling**: SCSS with Bootstrap for a responsive and modern UI.  

### Backend  
- **Framework**: Spring Boot (Java) for building scalable backend services.  
- **Database**: PostgreSQL for robust and relational data storage.  
- **ORM**: Hibernate for efficient database operations.  
- **API Architecture**: RESTful services for seamless frontend-backend communication.  

---

## Features  

1. **User Authentication**  
   - Secure user registration and login powered by **JWT (JSON Web Tokens)** for session management.  
   - Supports user role differentiation (e.g., regular users vs. admins) for fine-grained access control.

2. **Book Management**  
   - Comprehensive **CRUD (Create, Read, Update, Delete)** operations allow users to manage their personal book library.  
   - Add detailed information for each book, including title, author, genre, publication date, and description.  
   - Display book covers and additional metadata for an enriched user interface.  
   - Users can organize books into custom categories or tags for better library management.  

3. **Wishlist Management**  
   - Allows users to build a **"To-Read" list**, where they can store books they plan to read in the future.  
   - Intuitive options to reorder, prioritize, or categorize wishlist items for better planning.  
   - Seamless functionality to move books between the wishlist and "read" list, maintaining accurate reading history.  

4. **Reading Progress Tracking**  
   - Mark books as "in progress" or "completed" to visualize your reading journey.  
   - Keep track of books you've read over time, with options to view reading statistics like the number of books completed in a year.  
   - Features a reading calendar or timeline to showcase the history of completed books.  

5. **Search and Filtering**  
   - Advanced search functionality to quickly locate books by title, author, genre, or tags.  
   - Multi-criteria filtering options to combine attributes like genre, read status, and author in one search.  
   - Dynamic sorting options such as by rating, publication date, or most recently added.  
   - Pagination and lazy loading ensure smooth navigation for libraries with a large number of entries.  

6. **Book Reviews**  
   - Users can write detailed reviews for books, rate them on a scale, and share their thoughts with the community.  
   - View aggregated ratings and top reviews to make informed decisions about what to read next.  
   - Review history allows users to revisit and edit their feedback.  

7. **Responsive Design**  
   - Fully responsive user interface built with **Angular Material** and **Bootstrap**, ensuring compatibility across devices.  
   - Optimized layouts for desktops, tablets, and mobile devices for a seamless user experience.  

---

## Installation and Setup  

### Prerequisites  
Ensure the following software is installed on your system:  
- **Node.js** (v16+)  
- **Angular CLI** (v15+)  
- **Java JDK** (v17+)  
- **PostgreSQL** (v12+)  
- **Maven**  


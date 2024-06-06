- 👋 Hi, I’m @Yogesh-Ginti
- 👀 I’m interested in Web development and BlockChain
- 🌱 I’m currently learning Web development(MERN)
- 💞️I'm looking to collaborate on innovative web development projects
- ✉️  You can contact me at yogeshginti@gmail.com
- 😄 Pronouns: "yoggi"
- ⚡ Fun fact: "I Love Moto Riding"

<!---
Yogesh-Ginti/Yogesh-Ginti is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Entertainment App
The Entertainment App is a full-stack application designed to provide users with access to a vast collection of movies and TV shows, leveraging the TMDB API for fetching media details. It features user authentication, media exploration, and personal bookmarks, offering a comprehensive and personalized media browsing experience.

Features
User Authentication: Utilizes JWT for secure login and registration, ensuring user data protection.
Media Exploration: Allows users to discover trending movies and TV shows, with detailed views available for each media item.
Bookmarks: Enables users to bookmark their favorite media, creating a personalized list of favorites accessible at any time.
Detailed Media Information: Provides in-depth details about movies and TV shows, including cast, genres, ratings, and more.
Getting Started
Prerequisites
Node.js (v14 or later)
npm (v6 or later)
MongoDB instance (local or remote)
TMDB API key for fetching media data
Backend Setup
Clone the Repository: Start by cloning the Entertainment App repository to your local machine.

git clone https://github.com/yourusername/entertainment-app.git
Navigate to the Backend Directory: Move into the backend directory of the project.

cd entertainment-app/backend
Install Dependencies: Install the necessary dependencies using npm.

npm install
Configure Environment Variables: Create a .env file based on the provided .env.example file. Provide your MongoDB URI and TMDB API key in the .env file.

 MONGODB_URL= "your mongodb url"
 SECRET_TOKEN= "your secret token for user authentication"
 TMDB_TOKEN= "your tmdb access token for tmdb media data"
Start the Server: Run the backend server.

npm start
Verify Backend Setup: Confirm that the backend server is running without any errors.

Frontend Setup
Navigate to the Frontend Directory: Move into the frontend directory of the project.

cd ../frontend
Install Dependencies: Install the necessary dependencies using npm.

npm install
Configure Environment Variables: Create a .env file in the frontend directory and specify the URL of the backend server. For example:

REACT_APP_BACKEND_URL= "your live backend server"
VITE_APP_TMDB_API_KEY= "your tmdb api key for image"
Start the Application: Run the frontend application.

npm run dev
Access the Application: Open your web browser and navigate to the specified URL (default: http://localhost:3000) to access the Entertainment App.

By following these steps, you should have both the backend server and frontend application running locally, allowing you to explore the features of the Entertainment App.

Project Structure
Backend
Controllers: Contains logic for handling API requests, such as DetailMediaController.js for fetching detailed media information.
Models: Defines the schema for database collections, including Users and Bookmarks.
Routes: API routes for handling requests to different endpoints.
Middleware: Includes middleware for authentication and error handling.
Utils: Helper functions for interacting with external APIs (fetchDataUtils.js) and customizing media response data (customizeMediaResponse.js).
Frontend
Components: Reusable UI components like SingleCard for displaying media information.
Pages: React components representing pages (Home.jsx, Login.jsx, SignUp.jsx, MovieDetail.jsx, and TvDetail.jsx), utilizing hooks like useParams and services (TmdbService.js) for fetching media details.
Services: Functions for making API requests, including user authentication (UserService.js) and media data fetching (TmdbService.js).
Store: Redux setup for state management, including slices like BookmarkSlice.js for managing bookmarks.
Utils: Utility functions such as cookieActionUtils.js for managing cookies and customToast.js for displaying toast notifications.
Deployment
Frontend : https://entertainment-app-frontend-110.onrender.com
Backend : https://entertainment-app-backend-110.onrender.com
API Documentation
You can visit API documentation from here

Database Design
You can visit Database Design from here

Note
If tmdb api is not working then change your system dns according to this

Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch for your feature (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.

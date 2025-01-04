# Social Network

## **Challenge**
Create a mini social network. The application should have features like:

- Users should be able to sign up/sign in and create a profile for themselves.
- Search for other users.
- View other users' profiles & make them friends/unfriend them.
- View a list of mutual friends between users. A mutual friend is a user who is a friend of two other users who may or may not know each other.

---

## **Social Network**
This is a mini social network web application created using the **MERN stack**, which stands for **MongoDB, Express, React, and Node.js**. This app allows users to sign up or sign in, create their profile, search for other users, view other users' profiles, and make them friends or unfriend them.

---

## **Features**
The following features have been implemented in this mini social network app:

1. **Sign up/sign in**:  
   Users can sign up for a new account or sign in with an existing account. Passwords are securely hashed before being stored in the database.

2. **Create a profile**:  
   Users can create a profile for themselves by providing their name, location, occupation, email, and profile picture.

3. **Search for other users**:  
   Users can search for other users by name.

4. **View other users' profiles**:  
   Users can view other users' profiles by clicking on their name. They can also see the number of friends that the user has.

5. **Add/Remove Friends**:  
   Users can add or remove friends from their profile page or home page. (This option will be disabled while viewing their own profile page).

6. **View Mutual Friends**:  
   The logged-in user can view any mutual friends on the viewed profile.

7. **Posts Functionality**:  
   Every user can see all posts on the home page where general posts from every user will be displayed.

8. **Add Posts**:  
   Each logged-in user can add a post to their feed, which will be shown on their own profile and in the general feed.

9. **Update Posts**:  
   Likes for each post are counted separately and displayed, and the system keeps track of which users have already liked the posts.

---

## **Dependencies**
The following major dependencies have been used in this project:

- **React JS**: A JavaScript library used for building user interfaces.
- **Node.js**: A JavaScript runtime used to build server-side applications (Runtime Environment for JavaScript).
- **MongoDB**: A NoSQL document database used to store data in a flexible, JSON-like format.
- **Express**: A web application framework for Node.js used to build APIs and web applications.
- **bcrypt**: A library used to hash and salt passwords.
- **jsonwebtoken**: A library used to generate and verify JSON Web Tokens (JWTs).
- **multer**: Used for handling file uploads.
- **formik, yup**: Used for form validation.
- **dropzone**: Provides a drag-and-drop interface for file uploads in the client.

---

## **Run Locally**

Follow these steps to run the project locally:

1. **Clone this repository to your local machine**:
   ```bash
   git clone https://github.com/ayushjain12004/MERN-Stack-Developer-Assignment

2. **Go to the project directory**:
   ```bash
   cd SOCIAL-NETWORK

3. **Install the dependencies for both the client and server side**:
   ```bash
npm install

4. **Create a .env file in the server directory and set the following environment variables**:
   ```bash
   MONGO_URL=<your_mongodb_url>
JWT_SECRET=<your_jwt_secret>
PORT=<set_port>

5. **Start the backend development server**:
   ```bash
   cd server && nodemon index.js

6. **Open another terminal window and start the client**:
   ```bash
   cd frontend && npm start



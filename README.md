# Quiz-App

Quiz-App is an interactive full-stack web application designed to create, share, and take quizzes in a user-friendly environment. It's built using modern web technologies and offers a seamless experience for both quiz creators and participants. The app includes features like user authentication, personalized dashboards, and a rich set of tools for quiz management.

## Key Features
- **User Authentication:** Secure sign-up and login functionality, with profile management for users.
- **Quiz Creation Interface:** Intuitive tools for creating quizzes, including options for different question types, time limits, and more.
- **Community Engagement:** Users can share their quizzes with the community and also participate in quizzes created by others.
- **Personal Dashboard:** A dashboard for users to track their created quizzes, participated quizzes, and view their performance analytics.
- **Real-Time Scoring:** Instant feedback and scoring for quiz participants, with leaderboards to foster competition.
- **Responsive Design:** The app is designed to be responsive and accessible on various devices and screen sizes.

## Technology Stack
- **Frontend:** Built with React.js, leveraging components for a modular and interactive UI. Styled using CSS with a focus on a responsive and user-friendly design.
- **Backend:** Node.js with Express.js framework, handling RESTful API requests and server-side logic.
- **Database:** MongoDB for storing user data, quiz information, and results (assumed based on typical MERN stack usage).
- **State Management:** Redux used for managing application state across different components.
- **File Storage:** Cloudinary integration for efficient image upload and storage.
- **Testing:** Jest and React Testing Library for frontend testing (if applicable).

## Installation and Setup
To get the Quiz-App running locally, follow these steps:

### Prerequisites
- Node.js and npm (Node Package Manager)
- MongoDB installed and running (for database)

### Server Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/jdumez10/Quiz-App.git
   cd Quiz-App/server
2. Install server dependencies
   ```bash
   npm install
3. Start the server
  ```bash
  npm start
  ```
  
### Client Setup
1. Open a new terminal and navigate to the client folder
   ```bash
   cd Quiz-App/client
   ```
2. Install client dependencies
  ```bash
  npm install
  ```
3. Start the React client
  ```bash
  npm start
  ```


## Usage
After starting both the server and client, the Quiz-App will be accessible at http://localhost:3000. Navigate through the app to create an account, make quizzes, or participate in community quizzes.


## Contributing
Contributions to improve this project are welcome. Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

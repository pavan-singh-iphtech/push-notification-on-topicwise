## Firebase Push Notification - Topicwise

Firebase Push Notification - Topicwise is a project that demonstrates how to implement push notifications using Firebase Cloud Messaging (FCM) with topic-based messaging. This project utilizes JavaScript, React.js, Firebase, and Node.js to create a simple application that sends push notifications to specific topics.

## Table of Contents
-- Introduction
Technologies Used
Installation
Usage
Configuration
Contributing
License
Introduction
Firebase Push Notification - Topicwise provides a practical example of implementing push notifications using Firebase Cloud Messaging. The application is built using React.js for the frontend, Firebase for backend services, and Node.js for server-side logic. By following this example, you can gain insights into how to enable push notifications in your own projects.

## Technologies Used
JavaScript (ES6+)
React.js
Firebase
Node.js
Installation
To run this project locally, follow these steps:



 


cd firebase-push-notification-topicwise
## Install the required dependencies for backend:


cd push-notification
npm install

Usage
Start the frontend React app:

cd client
npm start
This will launch the React app on http://localhost:3000.

Start the Nod.js server:


cd push-notification
npm start
The server will run on http://localhost:8000.

Open your web browser and navigate to http://localhost:3000 to access the application.

Configuration
Before running the application, you need to set up Firebase and configure the necessary credentials:

Create a new Firebase project on the Firebase Console.

Obtain your Firebase Web API Key and replace it in the client/src/firebaseConfig.js file.

Configure the Firebase Admin SDK in the server/index.js file by replacing the placeholder values with your Firebase Admin credentials.

Ensure you have Node.js installed on your machine.

Install the Firebase CLI by running:


npm install -g firebase-tools
Authenticate the Firebase CLI using:


firebase login
Initialize your Firebase project in the server directory:

cd push-notification
firebase init
Follow the prompts to set up your Firebase project for Cloud Functions.

Deploy the Cloud Functions:

bash
Copy code
firebase deploy --only functions
Contributing
Contributions to this project are welcome! Feel free to open issues or submit pull requests.

Fork the repository.
Create a new branch for your feature: git checkout -b feature-name
Make your changes and commit them: git commit -m "Add feature"
Push to the branch: git push origin feature-name
Create a pull request.
License
This project is licensed under the MIT License.

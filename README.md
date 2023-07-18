# Description:
This project is a feature-rich Android video-calling app that utilizes Jitsi SDK for seamless real-time communication. The app enables users to sign up with their basic details and securely stores the data using Firebase Cloud Firestore. User authentication is handled through Firebase Authentication, providing a convenient auto-sign-in feature. The app includes the following key functionalities:

# User Registration and Authentication:

1. Users can sign up using their first name, last name, email, and password.
2. Firebase Authentication ensures secure authentication and user management.

# User Listing:

1. The app displays a list of other registered users, excluding the current user.
2. This feature allows users to connect and initiate video meetings with others.

# Meeting Invitations:

1. Users can send meeting invitations to other users using Firebase Cloud Messaging.
2. Invitations can be accepted or rejected, triggering appropriate response messages.
3. The initiator can cancel meeting invitations by initiating a hang-up process.

# Video Meetings using Jitsi Meet:

1. Accepted invitations to launch video meetings powered by Jitsi Meet.
2. Jitsi Meet provides real-time audio and video communication with rich features.
3. Features include switching sound devices, inviting more participants, audio-only mode, toggling the camera, and tile view.
4. Users can also engage in chat conversations during video meetings.

# Additional Features:

1. Scheduling new meetings and receiving notifications at the scheduled time.
2. Accessing the locations of other users who are using the app.

# Technology Stack:

1. Jitsi SDK: Used for implementing video calling functionality and real-time communication.
2. Firebase Cloud Firestore: A scalable and flexible database for storing user data.
3. Firebase Authentication: Enables user registration, login, and secure authentication.
4. Firebase Cloud Messaging (FCM): Facilitates sending meeting invitations and remote messages.

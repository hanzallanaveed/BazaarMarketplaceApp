# Bazaar Marketplace #

Bazaar Marketplace is a mobile application that enables users to buy or sell items with ease through a straightforward, user-friendly interface. Built on the **MERN stack** (MongoDB, Express.js, React Native, and Node.js), Bazaar delivers robust functionality for managing listings and finding products in your vicinity.

## Main Features

- **Secure User Profiles**: Uses Firebase for seamless user authentication.
- **Camera Integration**: Snap photos within the app to attach to listings.
- **Google Maps API Integration**: View listing locations on an interactive map.
- **Dynamic Marketplace**: Add and browse items in a constantly updated marketplace.
- **User-Friendly Interface**: Enjoy a clean design that simplifies navigation.
- **Robust Search**: Quickly find items through powerful search capabilities.

---

## Getting Started

Follow the steps below to run the Bazaar Marketplace application locally.

### Prerequisites

1. Install [Node.js](https://nodejs.org/) (LTS version recommended).
2. Install [Expo CLI](https://expo.dev/) globally for running the React Native client:
   ```bash
   npm install -g expo-cli
    ```
3. Install MongoDB or set up a MongoDB Atlas cluster.
4. Set up Firebase in your Google Cloud Console and retrieve API keys for authentication.

### Setup Instructions

1. Clone the Repository
   ```bash
    git clone <https://github.com/hanzallanaveed/BazaarMarketplaceApp>
    cd BazaarMarketplace
    ```
2. Set Up the Backend (Server)
- Navigate to the server directory:
   ```bash
    cd server
    ```
- Install Dependencies:
   ```bash
    npm install
    ```
- Create a .env file in the server directory and add the following:
   ```bash
    MONGO_URI=your-mongodb-uri
    ```
- Start the Server:
   ```bash
    node server.js
    ```
2. Set Up the Frontend (Client)
- Navigate to the client directory:
   ```bash
    cd client
    ```
- Install Dependencies:
   ```bash
    npm install
    ```
- Create a .env file in the client directory and add the following Firebase configurations:
   ```bash
    FIREBASE_API_KEY=your-firebase-api-key
    FIREBASE_AUTH_DOMAIN=your-firebase-auth-domain
    FIREBASE_PROJECT_ID=your-firebase-project-id
    FIREBASE_STORAGE_BUCKET=your-firebase-storage-bucket
    FIREBASE_MESSAGING_SENDER_ID=your-firebase-messaging-sender-id
    FIREBASE_APP_ID=your-firebase-app-id
    ```
- Start the Client:
   ```bash
    npx expo start
    ```

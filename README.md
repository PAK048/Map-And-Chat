**Project Name:** Map-And-Chat

**Description:** Map And Chat is a real-time communication platform that integrates chat functionality with geolocation features. Built using Next.js and Socket.IO, this project allows users to connect, chat, and interact with other users based on their geographical locations. Users can view nearby users on a map, send friend requests, and engage in conversations. Additionally, the platform supports social authentication via Google and Facebook for seamless login and sign-up.

**Features:**

- Real-time chat with WebSockets (Socket.IO)
- Interactive map to view and connect with nearby users
- Secure authentication with Google and Facebook using NextAuth.js
- Story posting functionality similar to Instagram
- Friend request and messaging system

**Tech Stack:**

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Node.js, Express, Socket.IO
- **Database:** MongoDB
- **Authentication:** NextAuth.js (Google & Facebook OAuth)
- **Mapping:** OpenStreetMap / Leaflet.js

**Installation:**

1. Clone the repository:
   ```bash
   git clone https://github.com/PAK048/Map-And-Chat.git
   ```
2. Install dependencies:
   ```bash
   cd Map-And-Chat
   npm install
   ```
3. Set up environment variables in a `.env.local` file:
   ```plaintext
   NEXTAUTH_SECRET=your_nextauth_secret
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   FACEBOOK_CLIENT_ID=your_facebook_client_id
   FACEBOOK_CLIENT_SECRET=your_facebook_client_secret
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

**Contributing:**
Feel free to contribute by submitting pull requests or reporting issues. Let's build an interactive and seamless communication platform together!

**License:**
MIT License


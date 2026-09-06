<div style="max-width: 800px; margin: 0 auto; font-family: Arial, sans-serif; line-height: 1.6;">
  <h1 style="text-align: center; color: #333;">Real-Time Chat App</h1>

  <p style="color: #555; font-size: 18px;">
    <strong>Real-Time Chat App</strong> is a real-time messaging application that allows users to communicate with each other instantly. Built using React, Node.js, Express.js, MongoDB, and Socket.IO, the application provides real-time messaging, image sharing, user authentication, and a responsive interface.
  </p>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Features</h2>

  <ul style="list-style-type: disc; padding-left: 20px; color: #555; font-size: 16px;">
    <li><strong>Real-Time Messaging:</strong> Send and receive messages instantly using Socket.IO.</li>
    <li><strong>User Authentication:</strong> User registration and login with JWT-based authentication and cookies.</li>
    <li><strong>Image Sharing:</strong> Users can send images through the chat.</li>
    <li><strong>Responsive Design:</strong> Tailwind CSS provides a responsive interface for different screen sizes.</li>
    <li><strong>Modern UI:</strong> React components are used to build a simple and interactive chat interface.</li>
    <li><strong>Client-Server Communication:</strong> REST APIs and Axios are used for communication between the frontend and backend.</li>
    <li><strong>Data Storage:</strong> MongoDB is used to store user and chat data.</li>
  </ul>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Tech Stack</h2>

  <h3 style="color: #34495e; font-size: 20px;">Frontend:</h3>

  <ul style="list-style-type: disc; padding-left: 20px; color: #555; font-size: 16px;">
    <li>React.js for UI development</li>
    <li>Tailwind CSS for styling</li>
    <li>React Router DOM for client-side routing</li>
    <li>Axios for API requests</li>
    <li>Socket.IO Client for real-time communication</li>
  </ul>

  <h3 style="color: #34495e; font-size: 20px;">Backend:</h3>

  <ul style="list-style-type: disc; padding-left: 20px; color: #555; font-size: 16px;">
    <li>Node.js for server-side JavaScript</li>
    <li>Express.js for building REST APIs</li>
    <li>Socket.IO Server for real-time messaging</li>
    <li>MongoDB for database storage</li>
    <li>Mongoose for MongoDB data modelling</li>
    <li>JWT for authentication</li>
  </ul>

  <h3 style="color: #34495e; font-size: 20px;">Other:</h3>

  <ul style="list-style-type: disc; padding-left: 20px; color: #555; font-size: 16px;">
    <li>Git for version control</li>
    <li>GitHub for source code management</li>
  </ul>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Installation &amp; Setup</h2>

  <ol style="padding-left: 20px; color: #555; font-size: 16px;">

```
<li>
  Clone the repository:

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>git clone https://github.com/Abhiram163/real-time-chat.git
```

cd real-time-chat</code></pre> </li>

```
<li>
  Navigate to the client directory:

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>cd client</code></pre>
</li>

<li>
  Install client-side dependencies:

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>npm install</code></pre>
</li>

<li>
  Start the frontend development server:

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>npm run dev</code></pre>

  <p>
    The frontend typically runs on
    <code>http://localhost:5173</code>.
  </p>
</li>

<li>
  Setup the backend:

  <p>
    Open another terminal and navigate to the backend directory.
  </p>

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>cd server</code></pre>
</li>

<li>
  Install backend dependencies:

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>npm install</code></pre>
</li>

<li>
  Create a <code>.env</code> file in the backend directory and add the required environment variables, such as the MongoDB connection string and JWT secret.
</li>

<li>
  Start the backend server:

  <pre style="background-color: #f4f4f4; padding: 6px; border-radius: 4px;"><code>npm run dev</code></pre>
</li>
```

  </ol>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Usage</h2>

  <p style="color: #555; font-size: 16px;">
    Users can register or log in to the application and start conversations with other users. Messages are delivered in real time using Socket.IO, and users can also share images through the chat. User and chat information is stored in MongoDB.
  </p>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Real-Time Communication</h2>

  <p style="color: #555; font-size: 16px;">
    Socket.IO is used to establish real-time communication between the client and server. When a message is sent, the server processes the event and delivers it to the appropriate user without requiring the page to be refreshed.
  </p>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Contributing</h2>

  <ol style="padding-left: 20px; color: #555; font-size: 16px;">
    <li>Fork the repository.</li>
    <li>Create a new branch for your changes.</li>
    <li>Make your changes and test them.</li>
    <li>Commit your changes.</li>
    <li>Submit a pull request.</li>
  </ol>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Author</h2>

  <p style="color: #555; font-size: 16px;">
    <strong>Abhiram Vadhri</strong>
  </p>

  <p style="color: #555; font-size: 16px;">
    GitHub:
    <a href="https://github.com/Abhiram163">Abhiram163</a>
  </p>

  <h2 style="color: #2c3e50; border-bottom: 2px solid #ddd; padding-bottom: 10px;">Acknowledgments</h2>

  <ul style="list-style-type: disc; padding-left: 20px; color: #555; font-size: 16px;">
    <li>React.js</li>
    <li>Tailwind CSS</li>
    <li>Node.js</li>
    <li>Express.js</li>
    <li>MongoDB</li>
    <li>Mongoose</li>
    <li>Socket.IO</li>
    <li>Axios</li>
  </ul>

</div>

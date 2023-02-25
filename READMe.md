### Welcome to the Backend Web Dev: Real-Time Chat App challenge challenge! You will push your code here.

#### Description
In this project, we’ll demonstrate backend web development skills by building a simple client-server chat application using Node JS and WebSockets. The application will allow multiple clients to communicate with each other in real-time through a web interface. The core functionality of the application will be creating a WebSocket connection between the client and server using socket.io and sending information from one client to another client using the server.

Required Components:

1. Install necessary tools:
   - Install Node JS on your machine.
   - Create a new directory for your project and navigate to it in the terminal.
   - Initialize a new Node JS project.

2. Create a web socket connection between the client and server:
    - Install the socket.io package using npm.
    - Create a new server file called server.js and require the socket.io package.
    - Create a new http server using the http package and listen on a specific port.
    - Set up the socket.io server to listen to the http server and handle incoming connections.

3. Send information from one client to another client using the server:
   - Set up event listeners on the server to handle incoming messages from clients.
   - Broadcast messages to all connected clients.

Optional Components:

1. Add user authentication with passwords:
     - Install a user authentication package such as passport and bcrypt.
     - Create a registration form for users to create an account with a username and password.
     - Hash and salt the user's password using bcrypt.
     - Set up login and logout routes to handle user authentication.
     - Implement a middleware function to ensure only authenticated users can access the chat room.

2. Add a graphical user interface:
    - Use a front-end framework such as React or Vue to create a user interface.
    - Create a form for sending messages and displaying the chat history.
    - Use CSS to style the user interface and make it look appealing.

3. Deploy the application to a live domain using Heroku, AWS, or a similar service:
    - Sign up for a hosting service such as Heroku or AWS.
    - Follow the hosting service's instructions to deploy the application to a live domain.
    - Make sure to update the necessary configuration files and environment variables to reflect the live domain.

Extensive documentation is required for all project submissions. Documentation should include clear and detailed instructions on how to set up the project on a local machine, including any necessary configuration steps and dependencies. 

Candidates who submit the best projects will be placed at companies recruiting for backend web development roles and be featured on LinkedIn to Mercor's network of US recruiters.

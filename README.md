
  <h1>Password Manager Project</h1>
    <h2>Overview</h2>
    <p>The Password Manager project provides a secure and convenient solution for managing and storing passwords. It offers functionalities for users to sign up, sign in, save, retrieve, and delete their credentials. The project utilizes encryption techniques to safeguard sensitive information and ensures proper session management for user authentication.</p>
    
  <h2>Features</h2>
    <ul>
      <li>User Authentication: Users can sign up and sign in securely to access their password vault.</li>
      <li>Password Encryption: Utilizes encryption methods to secure user passwords and stored credentials.</li>
      <li>Session Management: Implements session-based authentication to maintain user login states securely.</li>
      <li>Credential Management: Allows users to save, retrieve, and delete their credentials for various websites or applications.</li>
      <li>Responsive Design: Provides a user-friendly interface accessible across different devices and screen sizes.</li>
    </ul>

  <h2>Modules Used</h2>
    <ul>
      <li>Express: For building the backend server and handling HTTP requests.</li>
      <li>Mongoose: Object Data Modeling (ODM) library for MongoDB, facilitating interaction with the database.</li>
      <li>Body Parser: Middleware for parsing incoming request bodies.</li>
      <li>Express Session: Middleware for session management.</li>
      <li>dotenv: For loading environment variables from a .env file.</li>
      <li>bcrypt: Library for hashing user passwords for storage.</li>
      <li>randomstring: Generates random strings for session secret and password salting.</li>
    </ul>

  <h2>How to Use</h2>
    <h3>Setup</h3>
    <ol>
      <li>Clone the repository:<br><code>git clone &lt;repository_url&gt;</code></li>
      <li>Install dependencies:<br><code>npm install</code></li>
      <li>Set up environment variables: Create a <code>.env</code> file in the project root directory and specify the following variables:
        <ul>
          <li><code>PORT=&lt;port_number&gt;</code></li>
          <li><code>MONGODB_USERNAME=&lt;mongodb_username&gt;</code></li>
          <li><code>MONGODB_PASSWORD=&lt;mongodb_password&gt;</code></li>
          <li><code>SESSION_SECRET=&lt;session_secret&gt;</code></li>
        </ul>
      </li>
    </ol>

  <h3>Running the Application</h3>
    <p>Run the application using the following command:</p>
    <pre><code>npm start</code></pre>
    <p>The server will start running on the specified port.</p>

  <h3>API Endpoints</h3>
    <ul>
      <li><code>POST /signup:</code> Endpoint for user registration.</li>
      <li><code>POST /login:</code> Endpoint for user authentication.</li>
      <li><code>GET /success:</code> Endpoint for accessing the password manager dashboard.</li>
      <li><code>POST /success/add:</code> Endpoint for adding new credentials.</li>
      <li><code>GET /success/delete/:index:</code> Endpoint for deleting saved credentials.</li>
      <li><code>GET /signout:</code> Endpoint for user logout.</li>
    </ul>

  <h2>Contributing</h2>
    <p>Contributions are welcome! Please fork the repository and submit a pull request with your enhancements or bug fixes.</p>
  </div>
</body>
</html>

<h1 align="center">🚀 <b>Job Portal Application (MERN Stack)</b></h1>

<h2>🎯 <b>Project Overview</b></h2>
<p>
This project is a full-stack web application that serves as a modern job portal. It connects job seekers with employers by providing a platform where companies can post job listings and candidates can search for and apply to them.
</p>
<p>
This is a <b>MERN Stack</b> application. The backend is powered by <b>Node.js</b> and <b>Express.js</b>, offering a secure REST API (with JWT authentication) that connects to a <b>MongoDB Atlas</b> database. The frontend is a responsive and interactive single-page application built with <b>React.js</b>.
</p>

<h2>✨ <b>Key Features</b></h2>
<ul>
<li><b>Secure Authentication:</b> Full user registration and login system using <b>JSON Web Tokens (JWT)</b>.</li>
<li><b>Job Seeker Features:</b> Can search for jobs and view job details.</li>
<li><b>Recruiter Features:</b> Can post, update, and delete their own job listings.</li>
<li><b>RESTful API:</b> A clean, well-structured API for all CRUD operations (Create, Read, Update, Delete) for jobs.</li>
<li><b>Database:</b> Uses MongoDB Atlas for scalable, cloud-based data storage.</li>
</ul>

<h2>🧰 <b>Technologies & Tools Used</b></h2>

<h3>Backend (Server)</h3>
<ul>
<li><b>Node.js</b> (Runtime environment)</li>
<li><b>Express.js</b> (Web framework)</li>
<li><b>MongoDB Atlas</b> (Database)</li>
<li><b>jsonwebtoken</b> (for JWT Authentication)</li>
<li><b>dotenv</b> (for managing environment variables)</li>
<li><b>cors</b> (for cross-origin requests)</li>
</ul>

<h3>Frontend (Client)</h3>
<ul>
<li><b>React.js</b> (with Hooks & Functional Components)</li>
<li><b>React Router</b> (for client-side routing)</li>
<li><b>Axios</b> (for API calls)</li>
<li><b>Tailwind CSS / Bootstrap</b> (for styling)</li>
</ul>

<h3>Tools & Platforms</h3>
<ul>
<li><b>Postman</b> (for API testing)</li>
<li><b>Git & GitHub</b> (for version control)</li>
<li><b>VS Code</b> (IDE)</li>
</ul>

<h2>🚀 <b>How to Run This Project</b></h2>

<p><b>Prerequisites:</b></p>
<ul>
<li>Java JDK 17 or newer</li>
<li>Node.js (v18 or newer) & npm</li>
<li>A free <b>MongoDB Atlas</b> account</li>
</ul>

<p><b>Steps:</b></p>
<ol>
<li><b>Clone the repository:</b>
<pre><code>git clone https://www.google.com/search?q=https://github.com/vaishnavi1064/jobportal.git</code></pre>
</li>

<li><b>Navigate to the project directory:</b>
<pre><code>cd jobportal</code></pre>
</li>

<li><b>Backend Setup (Express.js):</b>
<ul>
<li>Navigate to the backend/server folder (e.g., <code>cd server</code>).</li>
<li>Install the required dependencies: <code>npm install</code></li>
<li>Create a <code>.env</code> file in this directory.</li>
<li>Inside your <code>.env</code> file, add your MongoDB Atlas credentials. The connection string in <code>index.js</code> is: 




<code>mongodb+srv://${process.env.DB_USER}:${process.env.DB_PASSWORD}@jobportal.epgboqa.mongodb.net</code>




So, your <code>.env</code> file must contain:
<pre><code>DB_USER="your-mongodb-username"
DB_PASSWORD="your-mongodb-password"</code></pre>
</li>
<li>Run the server: S<code>node index.js</code> (or <code>nodemon index.js</code> for development)</li>
<li>The backend server will start on <code>http://localhost:4000</code>.</li>
</ul>
</li>

<li><b>Frontend Setup (React):</b>
<ul>
<li>Navigate to the frontend/client folder (e.g., <code>cd client</code>).</li>
<li>Install dependencies: <code>npm install</code></li>
<li>Start the client: <code>npm start</code></li>
</ul>
</li>

<li><b>Access the application:</b>
<p>Open your browser and go to <code>http://localhost:3000</code> (the React app).</p>
</li>
</ol>

<h2>👩‍💻 <b>Author</b></h2>
<p>
<b>Vaishnavi Chaughule</b>
</p>

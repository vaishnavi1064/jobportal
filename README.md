<h1 align="center">🚀 <b>Job Portal Application</b></h1>

<h2>🎯 <b>Project Overview</b></h2>
<p>
This project is a full-stack web application that serves as a modern job portal. It connects job seekers with employers by providing a platform where companies can post job listings and candidates can search for and apply to them.
</p>
<p>
The application features distinct user roles (Job Seeker and Recruiter/Employer), each with a dedicated dashboard and functionalities. The backend is powered by <b>Java Spring Boot</b>, offering a secure REST API, while the frontend is a responsive and interactive single-page application built with <b>React.js</b>.
</p>

<h2>✨ <b>Key Features</b></h2>
<ul>
<li><b>Dual User Roles:</b>
<ul>
<li><b>Job Seeker:</b> Can create a profile, upload a resume, search for jobs (with filters for location, job type, etc.), and manage their applications.</li>
<li><b>Recruiter/Employer:</b> Can create a company profile, post new job listings, view applications for their jobs, and browse candidate profiles.</li>
</ul>
</li>
<li><b>Secure Authentication:</b> Role-based authentication and authorization using <b>Spring Security</b> and <b>JWT (JSON Web Tokens)</b>.</li>
<li><b>Job Management:</b> Recruiters have full CRUD functionality for job postings.</li>
<li><b>Application System:</b> Seekers can submit applications, which are then viewable by the respective recruiter.</li>
<li><b>Profile Management:</b> Users can create and update their personal and professional details.</li>
<li><b>RESTful API:</b> A clean, well-structured API to handle all data operations.</li>
</ul>

<h2>🧰 <b>Technologies & Tools Used</b></h2>

<h3>Backend</h3>
<ul>
<li><b>Java 17</b> & <b>Spring Boot 3</b></li>
<li><b>Spring Security</b> (for JWT Authentication)</li>
<li><b>MySQL</b> (Database)</li>
<li><b>Spring Data JPA (Hibernate)</b> (for ORM)</li>
<li><b>Maven</b> (for dependency management)</li>
</ul>

<h3>Frontend</h3>
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
<li><b>IntelliJ IDEA / VS Code</b> (IDE)</li>
</ul>

<h2>🚀 <b>How to Run This Project</b></h2>

<p><b>Prerequisites:</b></p>
<ul>
<li>Java JDK 17 or newer</li>
<li>Node.js (v18 or newer) & npm</li>
<li>MySQL Server</li>
</ul>

<p><b>Steps:</b></p>
<ol>
<li><b>Clone the repository:</b>
<pre><code>git clone https://www.google.com/search?q=https://github.com/vaishnavi1064/jobportal.git</code></pre>
</li>

<li><b>Navigate to the project directory:</b>
<pre><code>cd jobportal</code></pre>
</li>

<li><b>Backend Setup (Spring Boot):</b>
<ul>
<li>Navigate to the backend folder (e.g., <code>cd backend</code>).</li>
<li>Create a new MySQL database named <code>job_portal_db</code>.</li>
<li>Open <code>src/main/resources/application.properties</code>.</li>
<li>Update the <code>spring.datasource.username</code> and <code>spring.datasource.password</code> properties with your MySQL credentials.</li>
<li>Run the application using Maven: <code>./mvnw spring-boot:run</code></li>
<li>The backend server will start on <code>http://localhost:8080</code>.</li>
</ul>
</li>

<li><b>Frontend Setup (React):</b>
<ul>
<li>Navigate to the frontend folder (e.g., <code>cd frontend</code>).</li>
<li>Install dependencies: <code>npm install</code></li>
<li>Start the client: <code>npm start</code></li>
</ul>
</li>

<li><b>Access the application:</b>
<p>Open your browser and go to <code>http://localhost:3000</code>.</p>
</li>
</ol>

<h2>👩‍💻 <b>Author</b></h2>
<p>
<b>Vaishnavi Chaughule</b>
</p>

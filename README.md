# MY-PROFESSIONAL-WORLD


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Full-Stack Learning Roadmap</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f0f4f8;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 25px 20px;
      text-align: center;
      box-shadow: 0px 3px 6px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    header p {
      margin: 5px 0 0 0;
      font-size: 16px;
      opacity: 0.9;
    }

    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 15px;
    }

    /* Phase box */
    .phase {
      background-color: #fff;
      padding: 20px 25px;
      margin-bottom: 25px;
      border-left: 8px solid #4CAF50;
      border-radius: 10px;
      box-shadow: 0px 3px 10px rgba(0,0,0,0.08);
      transition: transform 0.2s;
    }
    .phase:hover {
      transform: translateY(-3px);
    }

    /* Phase Title */
    .phase h2 {
      margin-top: 0;
      color: #4CAF50;
      font-size: 22px;
      margin-bottom: 15px;
    }

    /* Ordered Lists */
    ol {
      line-height: 1.8;
      margin-left: 20px;
    }
    ol li {
      margin-bottom: 8px;
    }
    ol li ol {
      margin-top: 5px;
    }

    /* Mini project box */
    .mini-project {
      background-color: #e8f5e9;
      padding: 12px 15px;
      margin-top: 15px;
      border-left: 5px solid #388E3C;
      border-radius: 5px;
      font-weight: bold;
      color: #2E7D32;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .phase {
        padding: 15px 15px;
      }
      header h1 {
        font-size: 22px;
      }
      header p {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Full-Stack Developer Learning Roadmap</h1>
    <p>Python → React → SQL → Django → API → Full-Stack → Deployment</p>
  </header>

  <main>

    <!-- Phase 1: Python -->
    <div class="phase">
      <h2>Phase 1: Python Fundamentals (2–3 weeks)</h2>
      <ol>
        <li>Introduction
          <ol>
            <li>Python Overview</li>
            <li>Installation & Setup (Python, VS Code, Pip)</li>
          </ol>
        </li>
        <li>Basics
          <ol>
            <li>Variables & Data Types</li>
            <li>Input & Output</li>
            <li>Typecasting</li>
            <li>Comments</li>
          </ol>
        </li>
        <li>Operators
          <ol>
            <li>Arithmetic</li>
            <li>Comparison</li>
            <li>Logical</li>
          </ol>
        </li>
        <li>Control Flow
          <ol>
            <li>if-else</li>
            <li>for loop</li>
            <li>while loop</li>
            <li>break & continue</li>
          </ol>
        </li>
        <li>Data Structures
          <ol>
            <li>List</li>
            <li>Tuple</li>
            <li>Set</li>
            <li>Dictionary</li>
            <li>Strings</li>
          </ol>
        </li>
        <li>Functions
          <ol>
            <li>Defining Functions</li>
            <li>Parameters & Return Values</li>
            <li>Lambda Functions</li>
          </ol>
        </li>
        <li>OOP Basics
          <ol>
            <li>Classes & Objects</li>
            <li>Constructor</li>
            <li>Inheritance (basic)</li>
          </ol>
        </li>
        <li>File Handling
          <ol>
            <li>Reading Files</li>
            <li>Writing Files</li>
            <li>Appending Files</li>
          </ol>
        </li>
      </ol>
      <div class="mini-project">
        Mini Project: CLI Todo App or Notes Saver
      </div>
    </div>

    <!-- Phase 2: React -->
    <div class="phase">
      <h2>Phase 2: React Frontend (1–1.5 months)</h2>
      <ol>
        <li>Setup
          <ol>
            <li>Node.js & npm</li>
            <li>Create React App / Vite</li>
            <li>Folder Structure</li>
          </ol>
        </li>
        <li>Core Concepts
          <ol>
            <li>JSX</li>
            <li>Components (Functional)</li>
            <li>Props & State</li>
          </ol>
        </li>
        <li>Hooks
          <ol>
            <li>useState</li>
            <li>useEffect</li>
            <li>useRef</li>
          </ol>
        </li>
        <li>Lists & Conditional Rendering</li>
        <li>Forms (Controlled Components)</li>
        <li>Routing
          <ol>
            <li>React Router Basics</li>
            <li>Dynamic Routes</li>
          </ol>
        </li>
        <li>API Handling
          <ol>
            <li>Fetch API</li>
            <li>Axios</li>
            <li>Loading & Error States</li>
          </ol>
        </li>
        <li>Advanced
          <ol>
            <li>Context API</li>
            <li>Redux Toolkit</li>
            <li>Custom Hooks</li>
          </ol>
        </li>
      </ol>
      <div class="mini-project">
        Mini Projects: Notes App, Weather App, Todo App<br>
        Major Project: Blog/Auth UI
      </div>
    </div>

    <!-- Phase 3: SQL & Databases -->
    <div class="phase">
      <h2>Phase 3: SQL & Databases (2–3 weeks)</h2>
      <ol>
        <li>Introduction
          <ol>
            <li>What is a Database?</li>
            <li>Types of Databases</li>
          </ol>
        </li>
        <li>Database Creation
          <ol>
            <li>Create Database & Tables</li>
            <li>Data Types</li>
          </ol>
        </li>
        <li>CRUD Operations
          <ol>
            <li>SELECT</li>
            <li>INSERT</li>
            <li>UPDATE</li>
            <li>DELETE</li>
          </ol>
        </li>
        <li>Filters & Sorting
          <ol>
            <li>WHERE</li>
            <li>LIKE</li>
            <li>ORDER BY</li>
            <li>LIMIT</li>
          </ol>
        </li>
        <li>Relationships & Keys
          <ol>
            <li>Primary Key</li>
            <li>Foreign Key</li>
          </ol>
        </li>
        <li>Joins
          <ol>
            <li>INNER JOIN</li>
            <li>LEFT JOIN</li>
            <li>RIGHT JOIN</li>
          </ol>
        </li>
        <li>Aggregate Functions
          <ol>
            <li>COUNT</li>
            <li>SUM</li>
            <li>AVG</li>
            <li>MIN</li>
            <li>MAX</li>
          </ol>
        </li>
        <li>Normalization Basics</li>
        <li>Indexing Basics</li>
      </ol>
      <div class="mini-project">
        Mini Project: Design Users, Posts, Comments tables
      </div>
    </div>

    <!-- Phase 4: Django Backend -->
    <div class="phase">
      <h2>Phase 4: Django Backend (1–1.5 months)</h2>
      <ol>
        <li>Setup
          <ol>
            <li>Install Django</li>
            <li>Create Project & Apps</li>
            <li>Folder Structure</li>
          </ol>
        </li>
        <li>Core Concepts
          <ol>
            <li>URLs & Views</li>
            <li>Templates (Basic)</li>
          </ol>
        </li>
        <li>Models & ORM
          <ol>
            <li>Model Creation</li>
            <li>Migrations</li>
          </ol>
        </li>
        <li>Forms Basics</li>
        <li>Database Integration (SQL)</li>
        <li>Authentication
          <ol>
            <li>Login</li>
            <li>Register</li>
            <li>Logout</li>
            <li>Permissions</li>
          </ol>
        </li>
        <li>Django Admin
          <ol>
            <li>Customize Models</li>
            <li>Filters & Search</li>
          </ol>
        </li>
      </ol>
      <div class="mini-project">
        Mini Project: Blog or Notes App (Backend + Admin)
      </div>
    </div>

    <!-- Phase 5: Django REST Framework & API -->
<div class="phase">
  <h2>Phase 5: Django REST Framework & API (3–4 weeks)</h2>
  <ol>
    <li>REST API Basics
      <ol>
        <li>What is REST?</li>
        <li>Serializers</li>
        <li>Views (FBV & CBV)</li>
        <li>Routers & URL Patterns</li>
      </ol>
    </li>
    <li>CRUD APIs</li>
    <li>Relationships in API</li>
    <li>Pagination & Filtering</li>
    <li>Authentication
      <ol>
        <li>JWT Authentication</li>
        <li>Login/Register via API</li>
      </ol>
    </li>
  </ol>
  <div class="mini-project">
    Mini Project: Blog API with JWT, CRUD, Filtering, Comments
  </div>
</div>

<!-- Phase 6: Full-Stack Integration -->
<div class="phase">
  <h2>Phase 6: Full-Stack Integration (1 month)</h2>
  <ol>
    <li>Connect React Frontend with Django REST API</li>
    <li>Handle JWT Authentication in Frontend</li>
    <li>Protected Routes, Pagination, Search, Filtering</li>
  </ol>
  <div class="mini-project">
    Full-Stack Projects: Blog with Auth, Todo with User Accounts, E-commerce Mini App
  </div>
</div>

<!-- Phase 7: Deployment -->
<div class="phase">
  <h2>Phase 7: Deployment</h2>
  <ol>
    <li>Backend Deployment: Render / Railway / DigitalOcean</li>
    <li>Frontend Deployment: Vercel</li>
    <li>Database Deployment: Hosted SQL (Railway / PlanetScale / PostgreSQL)</li>
    <li>Environment Variables & Security</li>
  </ol>
</div>


  </main>

</body>
</html>

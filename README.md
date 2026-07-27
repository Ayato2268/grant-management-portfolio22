<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Web-Based Grant Management System final year project portfolio by Muhammad Irfan Wafiq Bin Kamaruzaman." />
  <meta name="theme-color" content="#0b1f46" />
  <title>Web-Based Grant Management System | FYP Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
</head>
<body>
  <div class="scroll-progress" id="scrollProgress"></div>

  <header class="site-header" id="top">
    <div class="container nav-shell">
      <a class="brand" href="#home" aria-label="Go to home">
        <img src="assets/uctati-logo.png" alt="University College TATI logo" />
        <div>
          <strong>UC TATI</strong>
          <span>Final Year Project Portfolio</span>
        </div>
      </a>

      <nav class="desktop-nav" aria-label="Primary navigation">
        <a href="#overview">Overview</a>
        <a href="#features">Features</a>
        <a href="#gallery">Gallery</a>
        <a href="#architecture">Architecture</a>
        <a href="#timeline">Timeline</a>
        <a href="#profile">Profile</a>
      </nav>

      <div class="nav-actions">
        <button class="icon-button" id="themeToggle" aria-label="Toggle dark mode" title="Toggle dark mode">
          <span class="sun">☀</span><span class="moon">☾</span>
        </button>
        <button class="menu-button" id="menuButton" aria-label="Open menu" aria-expanded="false">
          <span></span><span></span><span></span>
        </button>
      </div>
    </div>

    <nav class="mobile-nav" id="mobileNav" aria-label="Mobile navigation">
      <a href="#overview">Overview</a>
      <a href="#features">Features</a>
      <a href="#gallery">Gallery</a>
      <a href="#architecture">Architecture</a>
      <a href="#timeline">Timeline</a>
      <a href="#profile">Profile</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-glow glow-one"></div>
      <div class="hero-glow glow-two"></div>
      <div class="container hero-layout">
        <div class="hero-copy reveal">
          <div class="project-badge">
            <span class="dot"></span>
            Final Year Project · 2026
          </div>
          <h1>Web-Based Grant <span>Management System</span></h1>
          <p>
            A centralized and role-based platform designed to improve the management,
            monitoring, approval, and reporting of research grants at University College TATI.
          </p>

          <div class="hero-buttons">
            <a class="button primary" href="#gallery">Explore System</a>
            <a class="button ghost" href="#architecture">View Architecture</a>
          </div>

          <div class="hero-metrics">
            <article>
              <strong data-counter="2">0</strong>
              <span>User Roles</span>
            </article>
            <article>
              <strong data-counter="6">0</strong>
              <span>Core Modules</span>
            </article>
            <article>
              <strong data-counter="100" data-suffix="%">0</strong>
              <span>Web-Based</span>
            </article>
          </div>
        </div>

        <div class="hero-visual reveal">
          <div class="browser">
            <div class="browser-top">
              <div class="traffic"><i></i><i></i><i></i></div>
              <div class="address">grant-system.local/admin/dashboard</div>
            </div>
            <img src="assets/admin-dashboard.png" alt="Administrator dashboard interface" />
          </div>
          <div class="floating-card card-a">
            <span>✓</span>
            <div><strong>Centralized Data</strong><small>One reliable source of information</small></div>
          </div>
          <div class="floating-card card-b">
            <span>↗</span>
            <div><strong>Real-Time Overview</strong><small>Monitor grants and progress quickly</small></div>
          </div>
        </div>
      </div>
    </section>

    <section class="trust-strip">
      <div class="container">
        <span>Built with</span>
        <div class="tech-mini">
          <b>PHP 8.2</b><b>MySQL</b><b>Bootstrap 5</b><b>JavaScript</b><b>XAMPP</b><b>VS Code</b>
        </div>
      </div>
    </section>

    <section class="section" id="overview">
      <div class="container">
        <div class="section-head reveal">
          <span>Project Overview</span>
          <h2>One platform for the complete grant management process</h2>
          <p>The proposed system replaces fragmented manual work with an integrated digital workflow.</p>
        </div>

        <div class="overview-grid">
          <article class="overview-card reveal">
            <div class="card-index">01</div>
            <h3>Current Challenge</h3>
            <p>Grant data is spread across spreadsheets, emails, and separate documents, making updates and retrieval difficult.</p>
          </article>
          <article class="overview-card focus reveal">
            <div class="card-index">02</div>
            <h3>Proposed Solution</h3>
            <p>A secure web-based platform with role control, grant records, progress submissions, approval workflow, and reports.</p>
          </article>
          <article class="overview-card reveal">
            <div class="card-index">03</div>
            <h3>Expected Impact</h3>
            <p>Faster administration, improved accuracy, better transparency, and clearer communication between users.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section soft-section" id="features">
      <div class="container">
        <div class="section-head reveal">
          <span>Core Features</span>
          <h2>Designed around practical academic grant workflows</h2>
        </div>
        <div class="feature-grid">
          <article class="feature reveal"><div class="feature-icon">01</div><h3>User Management</h3><p>Manage accounts, user details, and Administrator or Lecturer roles.</p></article>
          <article class="feature reveal"><div class="feature-icon">02</div><h3>Grant Records</h3><p>Add, update, view, and maintain centralized grant information.</p></article>
          <article class="feature reveal"><div class="feature-icon">03</div><h3>Research Teams</h3><p>Maintain lecturer profiles and research team member information.</p></article>
          <article class="feature reveal"><div class="feature-icon">04</div><h3>Progress Monitoring</h3><p>Track milestones, percentage, completed activities, challenges, and next plans.</p></article>
          <article class="feature reveal"><div class="feature-icon">05</div><h3>Approval Workflow</h3><p>Approve or reject progress submissions with administrative remarks.</p></article>
          <article class="feature reveal"><div class="feature-icon">06</div><h3>Reports & Analytics</h3><p>View visual summaries, statistics, and structured institutional reports.</p></article>
        </div>
      </div>
    </section>

    <section class="section roles-section">
      <div class="container role-grid">
        <article class="role-card admin reveal">
          <div class="role-top"><span>Administrator</span><b>Full Management Access</b></div>
          <h2>Control the complete grant administration process</h2>
          <ul>
            <li>Manage users and lecturers</li>
            <li>Maintain grant records</li>
            <li>Assign research team members</li>
            <li>Review and approve progress</li>
            <li>Generate reports and dashboards</li>
          </ul>
        </article>

        <article class="role-card lecturer reveal">
          <div class="role-top"><span>Lecturer</span><b>Focused Project Access</b></div>
          <h2>Submit and monitor project progress with less effort</h2>
          <ul>
            <li>View assigned grants</li>
            <li>Submit progress reports</li>
            <li>Upload supporting documents</li>
            <li>Track status and remarks</li>
            <li>Review submission history</li>
          </ul>
        </article>
      </div>
    </section>

    <section class="section" id="gallery">
      <div class="container">
        <div class="section-head reveal">
          <span>System Gallery</span>
          <h2>Selected interfaces from the completed system</h2>
          <p>Click any image to view it in full size.</p>
        </div>

        <div class="gallery-grid">
          <figure class="gallery-card wide reveal" data-lightbox="assets/login.png">
            <div class="gallery-image"><img src="assets/login.png" alt="System login page" /><div class="zoom-hint">View full size</div></div>
            <figcaption><span>Authentication</span><h3>Secure Login Interface</h3><p>Role-based access for administrators and lecturers.</p></figcaption>
          </figure>

          <figure class="gallery-card reveal" data-lightbox="assets/admin-dashboard.png">
            <div class="gallery-image"><img src="assets/admin-dashboard.png" alt="Administrator dashboard" /><div class="zoom-hint">View full size</div></div>
            <figcaption><span>Dashboard</span><h3>Administration Overview</h3><p>Quick actions and system summaries in one workspace.</p></figcaption>
          </figure>

          <figure class="gallery-card reveal" data-lightbox="assets/statistics-dashboard.png">
            <div class="gallery-image"><img src="assets/statistics-dashboard.png" alt="System statistics dashboard" /><div class="zoom-hint">View full size</div></div>
            <figcaption><span>Analytics</span><h3>System Statistics</h3><p>Visual summaries of grants, lecturers, users, and project status.</p></figcaption>
          </figure>

          <figure class="gallery-card wide reveal" data-lightbox="assets/report.png">
            <div class="gallery-image"><img src="assets/report.png" alt="Research grant summary report" /><div class="zoom-hint">View full size</div></div>
            <figcaption><span>Reporting</span><h3>Research Grant Summary Report</h3><p>Structured reporting for institutional monitoring and decision-making.</p></figcaption>
          </figure>
        </div>
      </div>
    </section>

    <section class="section soft-section" id="architecture">
      <div class="container">
        <div class="section-head reveal">
          <span>System Architecture</span>
          <h2>Database structure and user workflows</h2>
        </div>

        <div class="architecture-grid">
          <figure class="architecture-card main-diagram reveal" data-lightbox="assets/erd.png">
            <div class="diagram-wrap"><img src="assets/erd.png" alt="Entity relationship diagram" /></div>
            <figcaption><span>Database Design</span><h3>Entity Relationship Diagram</h3><p>Core tables, keys, and relationships used by the system.</p></figcaption>
          </figure>

          <figure class="architecture-card reveal" data-lightbox="assets/admin-flowchart.png">
            <div class="diagram-wrap"><img src="assets/admin-flowchart.png" alt="Administrator flowchart" /></div>
            <figcaption><span>User Flow</span><h3>Administrator Flowchart</h3><p>Administrative operations from login to reporting.</p></figcaption>
          </figure>

          <figure class="architecture-card reveal" data-lightbox="assets/lecturer-flowchart.png">
            <div class="diagram-wrap"><img src="assets/lecturer-flowchart.png" alt="Lecturer flowchart" /></div>
            <figcaption><span>User Flow</span><h3>Lecturer Flowchart</h3><p>Grant viewing, progress submission, and status tracking.</p></figcaption>
          </figure>
        </div>
      </div>
    </section>

    <section class="section" id="timeline">
      <div class="container">
        <div class="section-head reveal">
          <span>Development Process</span>
          <h2>Project development timeline</h2>
        </div>

        <div class="timeline">
          <article class="timeline-item reveal"><b>01</b><div><span>Analysis</span><h3>Requirements Gathering</h3><p>Identified user roles, existing issues, and functional requirements.</p></div></article>
          <article class="timeline-item reveal"><b>02</b><div><span>Design</span><h3>System & Database Design</h3><p>Prepared interfaces, workflows, ERD, and database specifications.</p></div></article>
          <article class="timeline-item reveal"><b>03</b><div><span>Development</span><h3>System Implementation</h3><p>Developed the platform using PHP, MySQL, Bootstrap, and JavaScript.</p></div></article>
          <article class="timeline-item reveal"><b>04</b><div><span>Testing</span><h3>Functional Verification</h3><p>Tested login, role control, grant management, progress, and reporting modules.</p></div></article>
          <article class="timeline-item reveal"><b>05</b><div><span>Completion</span><h3>Evaluation & Documentation</h3><p>Finalized system improvements, documentation, presentation, and portfolio.</p></div></article>
        </div>
      </div>
    </section>

    <section class="section objective-section">
      <div class="container objective-layout">
        <div class="section-head reveal">
          <span>Project Objectives</span>
          <h2>Analyze. Design. Develop.</h2>
          <p>Three objectives guide the complete project lifecycle.</p>
        </div>
        <div class="objective-list">
          <article class="reveal"><b>01</b><p>Analyze the system requirements for the Web-Based Grant Management System.</p></article>
          <article class="reveal"><b>02</b><p>Design the system specifications, interfaces, and technical structure.</p></article>
          <article class="reveal"><b>03</b><p>Develop a functional Web-Based Grant Management System for UC TATI.</p></article>
        </div>
      </div>
    </section>

    <section class="profile-section" id="profile">
      <div class="container profile-shell reveal">
        <div>
          <span class="profile-label">Prepared By</span>
          <h2>Muhammad Irfan Wafiq Bin Kamaruzaman</h2>
          <div class="profile-details">
            <span>No. Matric: 24B08D002</span>
            <span>Faculty / Programme: FKMPT, BCSC</span>
          </div>
        </div>
        <div class="supervisor">
          <span>Supervisor</span>
          <strong>Dr. Azliza Binti Yacob</strong>
          <small>University College TATI</small>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container footer-inner">
      <p>© 2026 Muhammad Irfan Wafiq · Final Year Project Portfolio</p>
      <a href="#top">Back to top ↑</a>
    </div>
  </footer>

  <div class="lightbox" id="lightbox" aria-hidden="true">
    <button id="lightboxClose" aria-label="Close image">×</button>
    <img id="lightboxImage" alt="Expanded system screenshot" />
  </div>
</body>
</html>

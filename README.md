<h1 align="center">Hi 👋, I'm George Joseph</h1>

<p align="center">
  <b>Computer Science & AI Student · Backend Developer · Competitive Programmer</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/georgejosephx">
    <img src="https://img.shields.io/badge/LinkedIn-0A77B6?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

<h2>🚀 About Me</h2>

<p>
I'm a Computer Science & Artificial Intelligence student interested in
backend engineering, distributed systems, concurrency, databases, and
algorithmic problem solving.
</p>

<p>
I enjoy building practical backend systems and progressively improving
their scalability and reliability by solving concrete engineering problems.
I'm also an active competitive programmer with 2,000+ problems solved.
</p>

---

<h2>🛠️ Languages & Technologies</h2>

<h3>Languages</h3>

<p>
  <a href="https://go.dev/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" alt="Go" width="42" height="42"/>
  </a>
  <a href="https://isocpp.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="42" height="42"/>
  </a>
  <a href="https://www.cprogramming.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="42" height="42"/>
  </a>
  <a href="https://www.python.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="42" height="42"/>
  </a>
  <a href="https://www.javascript.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="42" height="42"/>
  </a>
  <a href="https://www.mysql.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="SQL" width="42" height="42"/>
  </a>
</p>

<h3>Backend & Databases</h3>

<p>
  <a href="https://go.dev/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original-wordmark.svg" alt="Go" width="42" height="42"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="42" height="42"/>
  </a>
  <a href="https://expressjs.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js" width="42" height="42"/>
  </a>
  <a href="https://www.postgresql.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" width="42" height="42"/>
  </a>
  <a href="https://www.mongodb.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="42" height="42"/>
  </a>
  <a href="https://redis.io/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="Redis" width="42" height="42"/>
  </a>
</p>

<h3>Tools & Infrastructure</h3>

<p>
  <a href="https://www.docker.com/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" width="42" height="42"/>
  </a>
  <a href="https://git-scm.com/">
    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="42" height="42"/>
  </a>
  <a href="https://www.postman.com/">
    <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" width="42" height="42"/>
  </a>
  <a href="https://www.linux.org/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="42" height="42"/>
  </a>
</p>

<h3>Frontend & ML</h3>

<p>
  <a href="https://react.dev/">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="42" height="42"/>
  </a>
  <a href="https://tailwindcss.com/">
    <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind CSS" width="42" height="42"/>
  </a>
  <a href="https://scikit-learn.org/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit-learn" width="42" height="42"/>
  </a>
</p>

---

<h2>🚀 Featured Projects</h2>

<h3>⚙️ JobMQ</h3>

<p>
Concurrent job scheduling and execution system built in Go and PostgreSQL,
designed to evolve from a single-process scheduler into a fault-tolerant
multi-instance system.
</p>

<ul>
  <li>Built a bounded scheduler with capacity-aware database fetching and backpressure.</li>
  <li>Implemented atomic job claiming using PostgreSQL row locking and <code>FOR UPDATE SKIP LOCKED</code>.</li>
  <li>Added PostgreSQL-backed execution leases with heartbeats and stale-worker protection.</li>
  <li>Used Go goroutines, worker pools, priority queues and <code>pgxpool</code>.</li>
  <li>Designed the system version-by-version around concrete scalability and reliability problems.</li>
</ul>

<p>
  <a href="https://github.com/georgejosephcodes/jobmq">
    <img src="https://img.shields.io/badge/Repository-JobMQ-black?style=for-the-badge&logo=github" alt="JobMQ Repository"/>
  </a>
</p>

<h3>💊 MedInventory</h3>

<p>
AI-powered medical inventory management system built with Node.js,
Express.js, MongoDB, Redis, JWT, Flask and scikit-learn.
</p>

<ul>
  <li>Implemented FEFO-based stock issuance to reduce expired-stock wastage.</li>
  <li>Used Redis distributed locking for consistent concurrent stock operations.</li>
  <li>Integrated a Python Flask service for anomaly detection.</li>
  <li>Automated inventory analysis using scheduled processing.</li>
</ul>

<h3>🗺️ Loopless</h3>

<p>
AI-powered travel planner combining React, Express.js, a native C++ TSP
solver, real road-distance matrices, Gemini API and Redis.
</p>

<ul>
  <li>Built a native C++ TSP solver for route optimization.</li>
  <li>Integrated Gemini API for natural-language travel planning.</li>
  <li>Used real road-distance matrices instead of straight-line distances.</li>
  <li>Implemented Redis-backed caching to reduce redundant API requests.</li>
</ul>

<h3>🤝 SevaLink</h3>

<p>
AI-assisted volunteer coordination platform built with React, Node.js,
Express.js, Firebase, Google Maps API and Gemini API.
</p>

<ul>
  <li>Matched volunteers using geospatial and multi-parameter filtering.</li>
  <li>Used Firebase Realtime Database for live application updates.</li>
  <li>Integrated Gemini API for AI-assisted coordination.</li>
</ul>

---

<h2>🏆 Achievements</h2>

<ul>
  <li>
    <b>Google Big Code 2026:</b> Advanced to Round 2, ranking among the
    <b>top 1,500 out of 15,000+</b> participants.
  </li>

  <li>
    <b>Flipkart GRiD 8.0:</b> National Semi-Finalist.
  </li>

  <li>
    <b>LeetCode:</b> Knight — maximum rating <b>1905</b>.
  </li>

  <li>
    <b>CodeChef:</b> 4-Star — maximum rating <b>1811</b>.
  </li>

  <li>
    <b>Codeforces:</b> Specialist — maximum rating <b>1520</b>.
  </li>

  <li>
    Solved <b>2,000+ algorithmic problems</b> and participated in
    <b>130+ contests</b>.
  </li>
</ul>

---

<h2>💻 Competitive Programming</h2>

<p>
I enjoy solving problems involving data structures, graphs, dynamic
programming, greedy algorithms, binary search, optimization and
competitive programming techniques.
</p>

<p>
  <a href="https://leetcode.com/">
    <img src="https://img.shields.io/badge/LeetCode-Knight-orange?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
  <a href="https://codeforces.com/">
    <img src="https://img.shields.io/badge/Codeforces-Specialist-blue?style=for-the-badge" alt="Codeforces"/>
  </a>
  <a href="https://www.codechef.com/">
    <img src="https://img.shields.io/badge/CodeChef-4★-brown?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/>
  </a>
</p>

<p align="center">
  <b>2,000+ Problems Solved</b> &nbsp;•&nbsp;
  <b>130+ Contests</b>
</p>

---

<h2>⚡️ Connect With Me</h2>

<p>
  <a href="https://www.linkedin.com/in/georgejosephx">
    <img src="https://img.shields.io/badge/LinkedIn-0A77B6?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

<h2>🐍 GitHub Contributions</h2>

<p align="center">
  <img src="https://raw.githubusercontent.com/georgejosephcodes/georgejosephcodes/output/snake-purple.svg" alt="GitHub Contribution Snake"/>
</p>

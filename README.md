SecuritySqlXSS — a practical, hands‑on web security demo that demonstrates common web vulnerabilities (SQL Injection and Cross‑Site Scripting / XSS) and the correct defenses (parameterized queries, input validation & output escaping, Content Security Policy, etc.).
This repository is intended both as a learning tool and as a technical portfolio piece you can show in interviews.

⚡ Project summary

SecuritySqlXSS contains a small web application that intentionally includes vulnerable endpoints so you can see how SQL Injection and XSS attacks work, plus secure implementations that mitigate those vulnerabilities. The project includes:

A simple frontend (HTML / JS) for interacting with the app.

A backend API that demonstrates vulnerable vs. secure query handling.

Example database schema and seed data to reproduce attacks safely on your local machine.

Documentation and code examples showing how to fix vulnerabilities (prepared statements, escaping, input sanitization, CSP, etc.).

Use this project to learn, to demonstrate security awareness in interviews, or to teach others safe coding practices.

🧩 Features / What this repo demonstrates

SQL Injection (vulnerable endpoint) — shows how concatenating user input into queries can be exploited.

SQL Injection (secure endpoint) — shows how to prevent injection using parameterized queries / prepared statements.

Reflected XSS (vulnerable endpoint) — shows how unescaped user input rendered in HTML can execute scripts.

Reflected XSS (secure endpoint) — shows how proper output encoding/escaping and CSP prevent exploitation.

Configuration examples for DB, server, and browser security headers.

Guided examples with step‑by‑step attack and remediation walkthroughs.

🛠 Technology stack (example)

Update these lines if your implementation differs.

Frontend: HTML, vanilla JavaScript (or React for extended demo)

Backend: Node.js + Express (example), but code snippets include PHP and Java alternatives

Database: MySQL / SQLite (SQL file included)

Dev tools: npm, dotenv

Optional: Dockerfile / docker‑compose for quick local environment

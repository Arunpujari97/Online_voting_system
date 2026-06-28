1.Online Voting System

A secure, web-based voting platform that enables authenticated users to cast votes digitally with full data integrity and tamper-proof security measures.

2.About the Project

This system allows registered voters to securely log in and cast their vote online. It enforces strict authentication, prevents duplicate voting, and uses basic encryption to protect sensitive voter data. The system was stress-tested with multiple simultaneous users to ensure reliability and security.

3.Tech Stack

Frontend: HTML5, CSS3, JavaScript
Backend: PHP
Database: MySQL
Security: User authentication, session management, basic encryption
Tools: Git, GitHub, VS Code

4.Features

Secure user registration and multi-layer login authentication
One-vote-per-user enforcement (duplicate vote prevention)
Basic encryption for sensitive voter data protection
Real-time vote count tracking (admin view)
Session management to prevent unauthorised access
Clean, user-friendly voting interface
Admin dashboard for result management

5.Security Implementation

Authentication: Username + password with session-based login
Encryption: Basic encryption applied to sensitive voter records
Duplicate Prevention: Database-level constraints prevent multiple votes
Session Management: Auto-logout on inactivity
Input Validation: Frontend (JS) + backend (PHP) validation on all inputs

6.How It Works

Voters register with verified credentials
Login triggers authentication check and creates a secure session
Voter selects their candidate and submits
System validates the vote — checks for duplicates, validates session
Vote is encrypted and stored securely in MySQL database
Admin can view live results from the dashboard

7.Project Structure

online-voting-system/
│
├── index.php             # Landing / login page
├── register.php          # Voter registration
├── vote.php              # Voting interface
├── submit_vote.php       # Vote submission and validation
├── dashboard.php         # Admin results view
├── auth.php              # Authentication logic
├── encrypt.php           # Encryption functions
├── style.css             # Styling
├── voting_system.sql     # MySQL schema
└── README.md

7.Testing

Stress-tested with multiple simultaneous users
Identified and resolved 5+ edge-case vulnerabilities
Usability testing conducted across different user types
Verified duplicate vote prevention under concurrent access
Documented complete security architecture

8.Developer

Arun Kumar K H
BE – Information Science & Engineering, 2025
Sir M Visvesvaraya Institute of Technology, Bengaluru
arunkumarkh.66@gmail.com
LinkedIn

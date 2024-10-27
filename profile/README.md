# Virtual Adults - PCGZZ

## Mission

At Virtual Adults, our mission is to empower psychology students by providing a realistic, AI-driven simulation platform where they can engage with virtual patients to practice and develop their skills. By creating a safe, interactive environment, we aim to bridge the gap between theory and real-world application, enhancing students' abilities to manage a variety of mental health scenarios.

## About the Platform

Virtual Adults is an educational tool designed for psychology programs to aid in experiential learning. The platform allows students to converse with AI-simulated virtual adults, each embodying various mental health conditions, providing them with a rich, hands-on experience. Educators can create assignments, design custom scenarios, monitor student interactions, and evaluate performance based on realistic transcripts and reports.

### Key Features

- **AI-Driven Simulations**: AI-generated responses that reflect real-world scenarios.
- **Role-Based Functionality**: Separate access levels for students, educators, and administrators.
- **Assignment Creation**: Customisable assignments with scenario uploads (TXT, PDF, DOC, DOCX formats).
- **Student Performance Tracking**: Detailed chat transcripts and evaluation tools.
- **Secure Authentication**: Auth0 and JWT-based user authentication for secure access.

### Technology Stack

- **Frontend**: React.js
- **Backend**: Express.js, Node.js
- **Database**: NoSQL (MongoDB)
- **Test**: Mocha, Jest, React Test Library
- **Cloud Services**: Distributed deployment: Vercel for frontend + GCP for backend
- **CI/CD**: Github action
- **Additional**: Docker for containerisation

## Project Site

Explore our live platform here: [Virtual Adults](https://pcgzz-frontend.vercel.app/)

## Repositories

This project is organized into two main repositories:

- **Frontend Repository**: [Virtual Adults - Frontend](https://github.com/PCGZZ/PCGZZ-backend)
- **Backend Repository**: [Virtual Adults - Backend](https://github.com/PCGZZ/PCGZZ-backend)

Each repository has its own setup, configuration, and contribution guidelines, detailed below.

## Getting Started

### Frontend Setup

1. **Clone the Frontend Repository**:
    ```bash
    git clone <frontend-repository-url>
    ```

2. **Ensure Node.js and npm are installed**:
    ```bash
    node -v
    npm -v
    ```

3. **Navigate to Project Directory**:
    ```bash
    cd <frontend-project-directory>
    ```

4. **Install Dependencies and Prepare Git Hooks with Husky**:
    ```bash
    npm install && npm run prepare
    ```

5. **Download and Add `.env` File**:
   Place the `.env` file provided by the team into the root directory.

6. **Run Application**:
    - Development: `npm run dev`
    - Production: `npm run start`
    - Testing: `npm run test`

### Backend Setup

1. **Clone the Backend Repository**:
    ```bash
    git clone <backend-repository-url>
    ```

2. **Navigate to Project Directory**:
    ```bash
    cd <backend-project-directory>
    ```

3. **Install Dependencies and Prepare Git Hooks with Husky**:
    ```bash
    npm install && npm run prepare
    ```

4. **Download and Add `.env` File**:
   Place the `.env` file provided by the team into the root directory.

5. **Run Application**:
    - Development: `npm run dev`
    - Production: `npm run start`
    - Testing (still in process): `npm run test`

## Contribution Guidelines

### Contribution Workflow (Frontend and Backend)

1. **Create a Branch for a Specific Feature**:
    ```bash
    git checkout -b <branch_name>
    ```

2. **Develop the Feature with Commits**:
   Ensure commits follow the conventional format. Use Commitizen for consistency:
    ```bash
    npm run commit
    ```

3. **Push Branch to Remote Repository**:
    ```bash
    git push origin <branch_name>
    ```

4. **Create a Pull Request on GitHub**:
   Go to the respective repository on GitHub and issue a pull request for code review.

5. **Code Review and Merge**:
   Address feedback as needed, and after approval, merge into the main branch.

# Virtual Adults - PCGZZ

## Mission

At Virtual Adults, our mission is to empower psychology students by providing a realistic, AI-driven simulation platform where they can engage with virtual patients to practice and develop their skills. By creating a safe, interactive environment, we aim to bridge the gap between theory and real-world application, enhancing students' abilities to manage a variety of mental health scenarios.

## About the Platform

### 1. Purpose
The Virtual Adult Psychology Training Platform is a web application developed to enhance psychology students’ counseling skills by offering interactive, simulated experiences. Through AI-powered virtual adults, the platform provides a safe and controlled environment where students can practice therapeutic and counseling techniques. Educators create, configure, and personalise virtual adults using relevant scenarios, photos, and behavioral patterns, helping students gain practical, hands-on training.

 

### 2. Context of Use
The platform is designed for educational settings, such as university psychology courses and training programs, where educators create realistic virtual adult scenarios for students to practice counseling. AI-powered responses (e.g., Chat GPT 4.0, 4.0 Mini) create an interactive, lifelike experience that mirrors real counseling sessions. 
Educators can also assess students’ counseling performance through detailed transcripts and summary reports of student interactions, helping them provide targeted feedback and track progress effectively.

### 3. Key Features

- **Assignment Creation and Configuration**: Educators create assignments, uploading names, scenarios, photos, and narrative details to form distinct virtual adult profiles.
- **AI Model Selection**: Educators select AI models for each virtual adult based on budgetary needs, choosing from various models like Chat GPT 4.0 or 4.0 Mini.
- **Interaction Modes**: Educators can define if interactions are verbal or text-based, aligning with different pedagogical needs.
- **Student Transcripts and Summaries**: Educators can access detailed records of student sessions with virtual adults, including a summary for easy review and feedback provision.
- **Feedback Loop**: Through transcript reviews, educators assess student interactions, offering personalized guidance based on conversation analysis.
- **Student Access Control**: Only verified students listed in the admin-uploaded CSV file are granted access, ensuring controlled and secure use of the platform.

### 4. Target Audience
- Primary Users: Psychology Students

  - Psychology students, particularly those in clinical, counseling, or therapeutic training programs, use this platform to engage with virtual adults in realistic role-play scenarios.

  - Students practice assessments, diagnostic techniques, and counseling methods in a non-judgmental environment, developing competencies for real-world interactions.

- Secondary Users: Psychology Educators

  - Educators and trainers in psychology classes serve as administrators of the platform, creating custom assignments, uploading scenario data, and personalizing each virtual adult.

  - Educators assess student performance through transcript records, helping track skill development and providing feedback based on the interactions.

### 5. Technology Stack

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

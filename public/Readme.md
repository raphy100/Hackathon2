                      TeacherHub
        The Problem in Education:
  In many schools today, both teachers and students face challenges in managing and accessing educational resources efficiently:

 Fragmented Resources: Lesson notes, assignments, and assessments are often scattered across emails, physical files, or different platforms, making it hard for teachers and students to keep everything organized.

 Time-Consuming Lesson Planning: Teachers spend hours preparing lessons manually, leaving less time for personalized instruction and student engagement.

 Limited Student Progress Insights: Traditional methods make it difficult for teachers to track individual student performance and overall class understanding in real-time.

 Inefficient Communication: Without a centralized platform, students may miss important announcements, assignments, or feedback from teachers.         
          
              Project Description
 TeacherHub is a comprehensive educational platform designed to empower teachers and students by providing a centralized, all-in-one solution for class management. Teachers can easily upload lesson notes, administer tests, and monitor student progress. A key feature of the platform is an integrated AI tool that assists teachers in planning lessons, making the preparation process more efficient and creative.

 For students, the platform offers a streamlined experience to access course materials, submit assignments, and track their own academic journey.

                   Features
  Teacher Dashboard: A dedicated interface for teachers to manage all their classes and students.

  Dynamic Content Management: Teachers can upload and organize lesson notes in various formats, accessible to students anytime.

  Assessment Tools: Create and deploy quizzes and tests to evaluate student understanding.

  Student Progress Monitoring: A clear and intuitive view for teachers to track individual student performance and overall class progress.

 AI-Powered Lesson Planning: A unique feature that uses generative AI to help teachers draft and structure lesson plans.

 Secure File Storage: All lesson notes and educational materials are securely stored and delivered via Firebase Storage.

 Authentication: Secure user sign-up and login for both teachers and students using Firebase Authentication.

            Technologies Used
      Frontend: HTML, CSS, JAVA SCRIPT
     Backend & Database:

 Firebase: This project is built entirely on the Firebase ecosystem for a serverless, scalable backend.

 Firebase Authentication: Handles all user authentication and role-based access.

 Cloud Firestore: The main database for storing all structured data like users, classes, assignments, and grades.

 Firebase Storage: Used to store and serve all uploaded files, such as lesson notes and student submissions.

 Cloud Functions: Deployed to run the AI lesson-planning tool. They act as the bridge between the teacher's request and the generative AI model.

             AI Integration:

 Gemini API for generating lesson plans and content.

 Installation and Setup
 Prerequisites
 Node.js (v18 or higher)

npm or yarn

 A Firebase project with Firestore, Authentication, and Storage enabled.

         Steps
  Clone the repository:

                Bash
 git Repository: https://github.com/raphy100/Hackathon2.git

 Project Structure
 teacherhub/
├── public/
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Main application pages (Teacher, Student, etc.)
│   ├── firebase/         # Firebase initialization and service files
│   ├── api/              # API calls and logic (including AI)
│   ├── assets/           # Images, icons, etc.
│   ├── App.jsx
│   └── main.jsx
├── .env.local
└── package.json
Contributing
We welcome contributions! If you would like to help improve TeacherHub, please follow our contribution guidelines.

License
This project is licensed under the MIT License.

Sources

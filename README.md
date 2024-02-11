# Online Course Django Application

This application can be used as a platform for managing and delivering online courses efficiently. With its intuitive interface and powerful features, both instructors and students can seamlessly interact and engage with course content.

## Features

- **User Authentication**: Signup and login functionality.
- **Course Management**: Instructors can create, edit, and delete courses, including adding lessons, assignments, and exams.
- **Enrollment System**: Students can browse available courses and enroll in them. Instructors can view enrolled students and track their progress.
- **Lesson Content**: Rich text editor support for creating engaging lesson content with also support for uploading media.
- **Assignment Submission**: Students can submit assignments online, and instructors can review and grade them.
- **Exam Functionality**: Create exams with multiple-choice questions, view scores, and results.
- **Admin Panel**: Powerful admin panel for managing users, courses, enrollments, and site settings.

## Installation
You can run the application locally by following the below steps:
1. Clone the repository: `git clone https://github.com/yourusername/online-course-django.git`
2. Navigate to the project directory: `cd online-course-django`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up environment variables: Copy the `.env.example` file to `.env` and update with your configuration.
5. Apply database migrations: `python manage.py migrate`
6. Create a superuser account: `python manage.py createsuperuser`
7. Run the development server: `python manage.py runserver`

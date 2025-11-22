CGPA Calculator & Generator
Overview
The CGPA Calculator & Generator is a user-friendly application designed to help students calculate their Cumulative Grade Point Average (CGPA) quickly and accurately. This tool simplifies the process of converting individual course grades into an overall academic performance metric, making it easier for students to track their academic progress.

Features
Easy Grade Input: Simple interface for entering course details and grades

Flexible Grading Systems: Supports both 4.0 and 5.0 grading scales

Automatic Calculation: Instantly computes CGPA based on course credits and grades

Multiple Course Support: Handle unlimited number of courses per semester

Results Export: Save and export your CGPA results for future reference

Semester Management: Organize courses by semester for better tracking

User-Friendly Interface: Clean, intuitive design for easy navigation

Technologies/Tools Used
Frontend: HTML5, CSS3, JavaScript

Backend: Node.js with Express.js

Database: MongoDB (for user data storage)

Authentication: JWT (JSON Web Tokens)

Styling: Bootstrap 5.0

Version Control: Git

Package Manager: npm

Installation & Setup
Prerequisites
Node.js (version 14 or higher)

MongoDB (local installation or MongoDB Atlas account)

Git

Step-by-Step Installation
Clone the Repository

bash
git clone https://github.com/your-username/cgpa-calculator.git
cd cgpa-calculator
Install Dependencies

bash
npm install
Environment Configuration

Create a .env file in the root directory

Add the following environment variables:

text
PORT=3000
MONGODB_URI=mongodb://localhost:27017/cgpa-calculator
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
Database Setup

Ensure MongoDB is running on your system

Or update the MONGODB_URI in .env file with your MongoDB Atlas connection string

Start the Application

bash
# Development mode
npm run dev

# Production mode
npm start
Access the Application

Open your web browser and navigate to http://localhost:3000

Testing Instructions
Manual Testing
Basic Calculation Test

Add 3-4 courses with different grades and credit hours

Verify the CGPA calculation matches manual computation

Test with both 4.0 and 5.0 grading scales

Edge Cases

Test with minimum/maximum grade values

Verify behavior with zero credit courses

Test with large number of courses

User Interface Testing

Navigate through all application pages

Test form validations and error messages

Verify responsive design on different screen sizes

Automated Testing
bash
# Run unit tests
npm test

# Run integration tests
npm run test:integration

# Run all tests with coverage
npm run test:coverage
Usage Guide
Calculating CGPA
Add Courses: Click "Add Course" to input course details

Enter Information: Provide course name, credit hours, and grade

Select Grading Scale: Choose between 4.0 or 5.0 scale

Calculate: Click "Calculate CGPA" to see your result

Save Results: Optionally save your calculation for future reference

Managing Semesters
Create multiple semesters to organize your academic progress

View semester-wise and cumulative CGPA

Edit or delete previous entries as needed

Support
For support, bug reports, or feature requests, please contact:

Email: support@cgpacalculator.com

GitHub Issues: Project Issues Page

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
We welcome contributions! Please see our CONTRIBUTING.md file for guidelines on how to contribute to this project.

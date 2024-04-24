# ElevateU

ElevateU is a virtual tutor platform developed as part of the Google Girl Hackathon project, aimed at enhancing basic education through adaptive learning. The platform dynamically assesses learners' understanding levels and provides personalized learning pathways to optimize their educational experience.

## Installation

To run ElevateU locally, follow these steps:

1. **Clone the Repository:** 
   ```
   git clone https://github.com/suh-1408/ElevateU.git
   ```

2. **Navigate to the Project Directory:**
   ```
   cd ElevateU
   ```

3. **Install Dependencies:**
   ```
   npm install
   ```

4. **Set Up SQLite Database:**
   - Make sure SQLite3 is installed on your system.
   - Run the following command to create the necessary tables:
     ```
     npm run db:migrate
     ```

5. **Start the Server:**
   ```
   npm start
   ```

6. **Access the Application:**
   - Once the server is running, access the application at `http://localhost:3000` in your web browser.

## Usage

ElevateU offers a seamless learning experience:

- **Registration/Login:** Users can register or log in to their accounts to access personalized learning content.
  
- **Assessment:** The platform assesses the learner's understanding level at every step using quizzes, interactive exercises, or other assessment methods.

- **Content Curation:** Based on the assessment results, ElevateU dynamically curates relevant educational content, including lessons, videos, quizzes, and interactive activities.

- **Progress Tracking:** Users can track their learning progress, view achievements, and receive recommendations for further improvement.

## Technologies Used

- **Frontend:** TypeScript with TSX (React)
- **Backend:** Django, Node.js
- **Database:** SQLite3
- **Models:** OpenAI API

## Contributing

Contributions are welcome! If you'd like to contribute to ElevateU, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

---

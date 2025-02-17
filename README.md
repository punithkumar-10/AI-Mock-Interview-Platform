# AI Mock Interview Platform

## Overview

The AI Mock Interview Platform is an innovative application designed to help job seekers enhance their interview skills through realistic, AI-driven mock interviews. Leveraging advanced technologies, this platform simulates real-world interview scenarios, providing users with comprehensive feedback to improve their performance.

## Features

- **AI-Powered Interview Simulation**: Engage in dynamic mock interviews where AI generates questions tailored to your chosen field, mimicking the spontaneity of real interviews.

- **Real-Time Feedback**: Receive immediate, constructive feedback on your responses, focusing on content, delivery, and overall communication skills.

- **Customizable Interview Settings**: Select specific industries, roles, and difficulty levels to tailor the interview experience to your preparation needs.

- **Comprehensive Performance Analytics**: Access detailed reports analyzing your strengths and areas for improvement, helping you track progress over time.

## Technologies Used

- **Frontend**: Developed using [Next.js](https://nextjs.org/) and styled with [Tailwind CSS](https://tailwindcss.com/) for a responsive and intuitive user interface.

- **Backend and Database**: Utilizes Firebase for backend services and database management, providing real-time data synchronization and user authentication.

- **AI Integration**: Incorporates the [Gemini API](https://geminiapi.com/) to generate intelligent, context-aware interview questions and feedback.

## Getting Started

To set up the AI Mock Interview Platform locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/punithkumar-10/AI-Mock-Interview-Platform.git
   cd AI-Mock-Interview-Platform
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Configure Environment Variables**:

   Create a `.env` file in the root directory and add the necessary environment variables as specified in `.env.example`.

4. **Run Database Migrations**:

   ```bash
   npx drizzle-kit up
   ```

5. **Start the Development Server**:

   ```bash
   npm run dev
   ```

   The application should now be running on `http://localhost:3000`.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

We extend our gratitude to the developers and communities of [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [PostgreSQL](https://www.postgresql.org/), [Drizzle ORM](https://orm.drizzle.team/), and the [Gemini API](https://geminiapi.com/) for their invaluable tools and support.

---

For more information, visit the [GitHub repository](https://github.com/punithkumar-10/AI-Mock-Interview-Platform). 

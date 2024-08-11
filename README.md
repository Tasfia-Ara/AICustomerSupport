## AI-Powered CS Mentor](http://ec2-3-147-126-99.us-east-2.compute.amazonaws.com/)

**Introduction:**
Have you ever wished you had a CS mentor at your fingertips? Well, now you do!
The **AI-Powered CS Mentor** is an advanced application leveraging Generative AI to assist users with a wide range of Computer Science-related queries. From interview preparation to selecting the optimal tech stack, this application serves as a personalized mentor, guiding users through their CS journey.

**Core Features:**

1. **Interview Preparation Guidance:**
   - Provides tailored advice on technical interview preparation, including coding challenges, system design, and behavioral questions.
   - Offers curated study plans, practice questions, and mock interview scenarios to help users excel.

2. **Programming Language Recommendations:**
   - Suggests the best programming languages based on user goals, industry trends, and project requirements.
   - Compares languages across various domains (web development, data science, mobile apps) to assist users in making informed choices.

3. **Tech Stack Consultation:**
   - Recommends optimal technology stacks for different projects, such as web applications, mobile apps, and AI/ML models.
   - Provides insights into the latest tools, frameworks, and libraries, complete with pros and cons for each option.

4. **Learning Resources and Roadmaps:**
   - Generates personalized learning paths tailored to users' skill levels, from beginner to advanced.
   - Suggests high-quality resources, including online courses, tutorials, and documentation, to enhance the learning experience.

5. **Real-Time Q&A:**
   - Delivers accurate and up-to-date responses to any CS-related questions in real-time, using a vast data repository.
   - Explains complex concepts, assists with debugging code snippets, and offers advice on best practices.

**Technical Details:**

- **Frontend:** The application is built using **React.js**, ensuring a responsive and user-friendly interface.
- **Generative AI Integration:**
  - Initially connected to the OpenAI API, but after encountering a 500 error, the application was switched to **OpenRouter.ai**, which now successfully provides generative AI responses to user prompts.
- **Deployment:**
  - The application is deployed on **Amazon Web Services (AWS) EC-2 instances**.
  - **Caddy** is used as a reverse proxy, routing all incoming traffic from port 3000 to port 80, ensuring seamless access and performance.

**User Experience:**
The AI-Powered CS Mentor offers an intuitive interface where users can either input questions directly or explore predefined categories. With conversational AI at its core, the application provides a smooth, engaging, and interactive experience, making it an invaluable tool for anyone involved in Computer Science.

**Target Audience:**
- **Students** preparing for technical interviews and exams.
- **Professionals** looking to stay current with the latest technologies.
- **Educators** in need of quick references and teaching materials.
- **Hobbyists and learners** eager to delve deeper into the field of Computer Science.

**Conclusion:**
The **AI-Powered CS Mentor** is a versatile and powerful tool designed to democratize access to high-quality Computer Science education. It caters to everyone, from beginners writing their first lines of code to seasoned professionals architecting complex systems, providing essential guidance and support for all.


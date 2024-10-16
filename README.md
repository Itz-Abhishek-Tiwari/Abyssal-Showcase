
### **Portfolio Builder with AI-Powered Content Generation**

#### **Project Overview**
This project is a web-based platform that allows users to create personalized portfolios with a unique URL that can be shared with others. The platform offers a user-friendly interface for creating, customizing, and managing online portfolios. Additionally, an AI-driven content generation feature is integrated to help users generate relevant and professional content based on their resumes. This tool is designed for individuals looking to showcase their work, skills, and experience in a clean, professional portfolio.

#### **Key Features**
- **User Registration & Authentication**: Secure user login and registration system to manage personal portfolios.
- **Portfolio Customization**: Users can input personal details such as bio, work experience, and skills to build a portfolio.
- **AI-Powered Content Generation**: AI integration to automatically generate content based on user-provided resumes or input data, helping users create compelling portfolio content.
- **Unique Shareable URLs**: Each portfolio is assigned a unique URL, allowing users to easily share their profiles online.
- **Responsive Design**: A clean and responsive design to ensure portfolios look great on all devices (desktop, tablet, mobile).

#### **Tech Stack**
- **Frontend**: ReactJS for a dynamic and interactive user interface.
- **Backend**: Django with Django Rest Framework (DRF) to handle user data, portfolio management, and AI requests.
- **AI Integration**: (Planned) Integration with OpenAI or another AI service to generate portfolio content based on resume data.
- **Database**: PostgreSQL (or SQLite for local development) to store user profiles and portfolio data.

#### **Future Enhancements**
- **Template Selection**: Multiple portfolio templates for users to choose from and customize.
- **Custom Domains**: Option for users to link their custom domains to their portfolios.
- **Social Media Integration**: Auto-fill portfolio content from LinkedIn, GitHub, etc.
- **Real-time Collaboration**: Allow users to collaborate and edit portfolios in real-time.

#### **Setup and Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Itz-Abhishek-Tiwari/Abyssal-Showcase.git
   ```
2. Navigate to the project directory:
   ```bash
   cd backend
   ```

##### **Backend Setup (Django)**
3. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations and start the Django server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

##### **Frontend Setup (ReactJS)**
5. Navigate to the frontend directory and install dependencies:
   ```bash
   cd frontend
   npm install
   ```
6. Start the React development server:
   ```bash
   npm start
   ```

#### **Contributing**
Contributions are welcome! Please feel free to submit issues or pull requests.

---

This description outlines the project's purpose, features, tech stack, and setup instructions, providing a clear understanding for users and contributors.

# Promptopia - A Prompt Sharing Application

Promptopia is a web application that allows users to create, share, and explore prompts. Built with the power of **Next.js**, it provides a robust and scalable platform with secure authentication and seamless user experiences.

## 🚀 Features

- **Prompt Sharing**: Users can post prompts for others to view and use.
- **Authentication**: Secure login and user management with account creation.
- **Profile Management**: Users can edit and manage their posted prompts.
- **Fast Rendering**: Optimized performance with server-side rendering using Next.js.
- **Database Integration**: Smooth handling of dynamic content and large datasets using MongoDB.
- **Responsive Design**: A clean, intuitive, and responsive interface.

## 🛠️ Tech Stack

- **Frontend**: Next.js, Tailwind CSS.
- **Backend**: Node.js.
- **Database**: MongoDB.
- **Authentication**: Google Cloud Platform (GCP).
- **Hosting**: Vercel for seamless deployment.

## 🔧 Prerequisites

Before running the project locally, ensure you have the following installed:

- **Node.js**: v16 or later
- **MongoDB**: Local or cloud instance
- **Git**: For cloning the repository

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shiva-2103/Promptopia_Next.git
   cd Promptopia_Next
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Setup environment variables:
   Create a ```.env``` file in the root directory.
   Add the following variables:
   ```env
   MONGODB_URI=<Your_MongoDB_URI>
   NEXTAUTH_URL=<Your_App_URL>
   GOOGLE_CLIENT_ID=<Your_Google_Client_ID>
   GOOGLE_CLIENT_SECRET=<Your_Google_Client_Secret>
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and navigate to ```http://localhost:3000.```

## 🌐 Live Demo
Check out the live version of the application here: Promptopia Live

## 📂 Project Structure
  ```
  Promptopia_Next/
│
├── components/        # Reusable components (e.g., Navbar, Form)
├── models/            # Mongoose models for database schema
├── pages/             # Next.js page routes
├── public/            # Static assets
├── styles/            # Global and component-specific styles
├── utils/             # Helper functions and utilities
├── .env               # Environment variables
├── package.json       # Project dependencies
└── README.md          # Documentation
  ```

## 🚀 Deployment
This project is hosted on Vercel. For redeployment:

1. Connect your repository to Vercel.
2. Add the required environment variables in the Vercel dashboard.
3. Deploy and preview changes live!

## 🌟 Future Enhancements
- Add search functionality for prompts.
- Enable categories and tags for better organization.
- Implement a "Like" or "Bookmark" feature for prompts.
- Add support for dark mode.

## 🧑‍💻 Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a pull request.

```csharp

This `README.md` provides a professional overview of your Promptopia project, focusing on installation, features, and usage. Adjust any information based on your project specifics.

```





   

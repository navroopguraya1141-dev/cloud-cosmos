Project Overview


  AI Text Summarizer is a web application that uses Google’s Gemini API to automatically summarize large text passages.
  It features Firebase Authentication, Firestore database integration, and a Next.js (React + TypeScript) frontend for a smooth and secure user experience.

⸻

Problem Statement

In today’s fast-paced digital world, people often struggle to read long articles, blogs, or research papers efficiently.
Our goal was to create a smart summarization tool that provides concise and meaningful summaries using AI, saving users valuable time and improving productivity.

⸻

Solution Summary


We built an AI-powered web app where users can log in via Firebase Auth, input long texts, and receive instant AI summaries generated through the Gemini API.
All user summaries are securely stored in Firebase Firestore for easy access and management.

⸻

Tech Stack

	  •	    Frontend: Next.js (React + TypeScript), Tailwind CSS
	  •  	Backend / API: Gemini Generative AI API
	  • 	Database: Firebase Firestore
	  • 	Authentication: Firebase Auth (Google Login)
	  • 	Cloud / Hosting: Vercel
	  • 	Version Control: Git + GitHub

Project structure

       	root/
        ├── app/                         # Next.js App Router pages
        ├── components/                  # Reusable components (Navbar, Hero, etc.)
        │   └── ui/
        ├── config/                      # Configuration files
        │   ├── firebaseConfig.ts
        │   └── AIConfig.ts
        ├── hooks/                       # Custom React hooks
        │   └── useGetUserInfo.ts
        ├── public/                      # Static assets
        ├── .env.local                   # Environment variables
        ├── package.json
        ├── next.config.ts
        ├── tsconfig.json
        └── README.md
⸻

  Setup Instructions

  Follow these exact steps to run your project locally:
   1. Clone the repository
   git clone https://github.com/navroopguraya1141-dev/cloud-cosmos.git
   cd cloud-cosmos

   2. Install dependencies
  
   npm install

   3. Create and configure environment variables
   
   touch .env.local

   4. Run the development server
   
   npm run dev


Deployment

Live Demo URL:
 https://aitext-sum.vercel.app/

GitHub Repository:
https://github.com/navroopguraya1141-dev/cloud-cosmos

The app is deployed on Vercel with Firebase backend and Gemini API integration.

⸻

Demo Video (Mandatory)

YouTube Link:
https://youtu.be/8sGzeSGjNkc?feature=shared

The demo video (2–3 minutes) shows:

	•	Firebase Authentication (Google login)
	•	Entering and summarizing text
	•	AI-generated summaries from Gemini API
	•	Saving and retrieving summaries from Firestore
	•	Deployed web app on Vercel

⸻

Features

	•	End-to-end working web app with AI summarization
	•	Firebase Authentication for secure user login
	•	Firestore integration for storing summaries
	•	Gemini API for generating concise text summaries
	•	Responsive UI built with Next.js and Tailwind CSS
	•	Real-time data management and smooth user flow

⸻

Technical Architecture

         Frontend (Next.js) → Firebase Auth (User Login) → Gemini API (Text Summarization) → Firestore (Save Results)

  Flow:
  
	     1.	User logs in via Firebase Authentication.
	     2.	User enters or pastes a text block.
    	 3.	The request is sent to Gemini API (via AIConfig).
	     4.	Gemini model (“gemini-2.0-flash”) generates a short summary.
	     5.	The summary is displayed in the frontend and saved to Firestore.


  References
  
	•	Firebase Documentation
	•	Google Gemini API
	•	Next.js Documentation
	•	Tailwind CSS


Acknowledgements

  Special thanks to:
  
	•	Firebase for Authentication & Firestore database
	•	Google Gemini API for AI summarization capabilities
	•	Vercel for seamless deployment
	•	Next.js for building a fast, scalable frontend





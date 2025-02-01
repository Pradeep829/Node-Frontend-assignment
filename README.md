# Node-Frontend-assignment

This repository contains my solution for the chatbot setup UI/UX assignment. The application was built using ReactJS to demonstrate the mobile-responsive and intuitive design required for onboarding new businesses with chatbot integration.

You can view the live version of the application here:
https://chatbot-pradeep-b034c4.netlify.app/

Features

**1. User Registration:**
Users can register by entering their name, email, and password.
Alternatively, users can sign in using Google.

**2. Setup Organization:**
Users can enter their company name, website URL, and description.
The application auto-fetches the meta-description from the company’s website (using dummy data for now).
Displays the list of scraped webpages, including the status (scraped/pending).

**3. Chatbot Integration & Testing:**
Users can test the chatbot by viewing a dummy integration on their website.
The integration process is made simple with clear instructions for both self-integration and sending the instructions to a developer.
When the integration is successful, a confetti animation appears with options to explore the admin panel or start interacting with the chatbot.
How to Run the Project Locally

**Prerequisites:**
Node.js (version 14 or above)
A code editor like VS Code
Navigate to the project directory:
cd chatbot_assignment_pradeep

**Install dependencies:**
npm install

**Start the development server:**
npm start
The application should now be running at http://localhost:3000.

**Google Sign-In Details**
I used the @react-oauth/google library to implement the Google Sign-In feature.
The Google Sign-In button will work for the following URLs:

1)localhost:3000

2)Deployed Link: 
https://chatbot-pradeep-b034c4.netlify.app/

If you choose email registration, you will need to enter the verification code 123456 to complete the registration process.

**Technologies Used**
ReactJS
@react-oauth/google for Google sign-in
CSS for styling and responsiveness
Dummy data for showcasing the flow

**Note**: 
The Google sign-in feature only works on localhost:3000 or the deployed link. Email verification is required during registration. Use the code 123456 to verify the email.

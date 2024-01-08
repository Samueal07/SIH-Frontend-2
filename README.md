# सुरक्षा - Rescue Agency Communication App

![1st](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/6a4822d5-a4ef-4535-85e6-e75bca490700)

### Problem Statement 1440 - Smart India Hackathon 2023

**Description:** 
The application, सुरक्षा, addresses the specific need for Rescue Agency to Agency Communication. It provides a comprehensive solution enabling agencies to communicate, share, and request resources during calamities.

### Features:

1. **Centralized AES Secured Database:** 
   - Agency Details
   - Agency Resources
   - Resources Alert/Request

2. **Unique Email Authentication:**
   - Only designated agency email IDs can receive OTPs for registration.
      ![auth](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/dc677c9b-c717-42b0-9464-d022bd4353ff)



3. **Automated Agency Details:**
   - Admins can manually or auto-fill details using Google Maps integration.
     ![agency](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/a9d979f7-9387-4633-bcaa-9cc14eefbbcc)


4. **Agency Interaction:**
   - View other registered agencies and their available resources on a customizable map.
     ![maps](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/27119373-e9c9-45e9-8b16-dad21ee4c4ed)

   - Real-time resource request and response during calamities.
     ![request1](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/66bd9697-3866-490c-80d9-f538bd2b2510)


5. **Broad Reach:**
   - Facilitates communication from NDRF to local agencies during emergencies.
     ![realtime](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/1b6e102a-3b6e-42b6-80b2-8142d5b64362)


6. **Resource Management:**
   - Database structured with tags for various resource categories.
   - Real-time allocation based on requests.
     ![request2](https://github.com/Samueal07/SIH-Frontend-2/assets/99087302/fa8745c8-6eef-47e2-84d5-4c1ef98353de)


7. **Disaster Location Notification:**
   - Agencies can pin disaster locations, sending notifications to nearby registered agencies within a 100 km radius.

### Tech Stack:

- **React-Native:** App Development
- **Google Maps:** Info Auto-Fill & Map Functionality
- **MongoDB:** Flexible Database
- **WebSocket, React-Native pdf:** Real-time Request & Report Generation
- **AES+JWT Custom Algo:** Encrypting Sensitive Data





### How to Use:

To get started with this application, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Samueal07/SIH-Frontend-2.git
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up necessary configurations:**
   - Ensure you have the required API keys for Google Maps (if applicable) in your environment variables.
   - Check and update any necessary configurations in the app, such as database connections or environment-specific settings.

4. **Run the application:**

   ```bash
   npm run dev
   ```
   This command will start the development server and launch the application on your local machine.

Make sure you have Node.js and npm installed beforehand.

### Contributors:

- Samueal Dsouza
- Tushar Maurya
- Bhavesh Mankar
- Shreyas Jagadale
- Sarthak Kulkarni
- Ankita Mandhare


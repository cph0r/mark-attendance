# 🚀 AutoMATE: The Attendance Ninja 🥋

**Tired of manually marking your attendance everyday on greyt-hr ? Say goodbye to those tedious tasks and let AutoMATE handle it for you! 🤖**

### 🌟 Features

- ✅ **Automated Attendance:** AutoMATE stealthily logs in your greythr account everyday at time of your choice, marks your attendance, and disappears like a ninja.
- 📆 **Custom Scheduling:** Set up your daily schedule, and AutoMATE will ensure you're present at all the right virtual places at the right time.

### 💡 Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/cph0r/mark-attendance.git

2. **Deploy on Netlify**

   a. add new project
   ![add-new-project](https://github.com/cph0r/mark-attendance/assets/40307242/b1e07f9e-9350-40ce-aeab-8e588c50c92c)

   b. configure your deployment
   ![config-your-repo](https://github.com/cph0r/mark-attendance/assets/40307242/bf358c1c-0e71-4b3b-b8d3-e75c23021d72)

   c. build command sohuld be 

   ```bash
   npm run start

4. **Set credentials as environment variables on netlify**

    variable names should be 'email' and 'password' in small and without quotes

5. **Create Trigger on Zappier**

   a. login to zapier, and create a new zap

   b. Set up trigger as zapier event and select time that you want to trigger it, select weekends to false 
<img width="1708" alt="Screenshot 2023-10-19 at 3 15 45 PM" src="https://github.com/cph0r/mark-attendance/assets/40307242/ad958ef5-0760-44f7-a9a0-3e4d4374439b">

   c. Link up netlify deply as destination
<img width="1702" alt="Screenshot 2023-10-19 at 3 17 55 PM" src="https://github.com/cph0r/mark-attendance/assets/40307242/f2684dda-5c5f-4e8e-aa79-32453bede4af">


5. **Sit back and Relax**

### Improvements and further scope

1. Any puppeteer scripts can be added in the puppeteer-script.js file to virtually mimic any action on any website
2. Add dynamic loading of secret credentials for eveyone to use use without creating their own netlify deployments


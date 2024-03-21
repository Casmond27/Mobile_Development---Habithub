HabitHub Application
Welcome to HabitHub – Crafting a Better You, Brick by Brick.
Getting Started
Follow these instructions to successfully run the HabitHub application on your device.
Prerequisites
Before you begin, ensure you have the following installed:
Node.js (Download and install from https://nodejs.org/)
Expo CLI (Install globally using npm install -g expo-cli)
Once you have Node.js and Expo CLI installed, you can proceed with running your Expo
application:
1. Open a terminal from Visual Studio Code.
2. Change to the directory where your app is stored using the cd command. Replace
/file_directory with the actual path to your app's directory: cd
/file_directory
3. To run the application, use the following command: npx expo start
4. For iPhone or Android users, you can scan the QR code generated by Expo Go to
download and test the app on your mobile device. For web users, you can press
"W" to load and view your application in a web browser.
Here's how to do it:
For iPhone or Android users:
1. Open the Expo Go app on your mobile device.
2. Scan the QR code displayed in your terminal or in Expo DevTools on your
computer using the QR code scanner built into the Expo Go app.
3. Your app must load on a mobile device to be tested.
For internet users:
1. After running npx expo start, a new browser window or tab will
automatically open with your Expo application.
2. If it doesn't open automatically, look for the URL displayed in your
terminal, usually starting with http: //localhost or http: //127.0.0.1.
Copy and paste this URL into your web browser's address bar. Once the
web page is loaded, you can interact and test your application in a web
browser. Remember to keep your terminal open when testing the
application as it will provide information about the development server
and potential bugs.
This will start your Expo project, and you can begin developing and
testing your mobile application.
Using the App
HabitHub features several key pages to help you develop and track your habits:
HOME PAGE:
This is your dashboard, displaying a list of your tracked habits. It will display the
current date and allow the creation of default activity by clicking the "Create
Activity" button
DETAIL PAGE:
Click on a habit to view more details such as the marked date on the calendar and the
progress of the activity. If the progress is 100%, a "Complete" button will appear for
you to finish the activity and it will update on the Overall page.
ADD ACTIVITY:
Choose and add a new habit from a set of default habits provided. Set your priority,
start date, and end date, and proceed to submit. The habit submitted will be displayed
on the home page with the image assigned to it.
ADD CUSTOM ACTIVITY:
Create a custom habit with specific details tailored to the user's goals. This is when
the habit you want to develop is not found in the application. In the Custom Activity
form, you can add the habit name, set the habit type such as gain or lose, set the
priority, start date, and end date, and proceed to submit. Same as the Add Activity
form, the habit submitted will be displayed on the home page.
OVERALL PAGE:
View an overview of all habits completed by you. This page has a point system where
the point is awarded based on priority and the higher the point you get, the higher
rank badge you get.
SETTINGS PAGE:
Customize the app settings, including language preferences and view profile settings.
The language preference will show a list of languages available to change but not
every language will work. Preferably try German, Chinese, or Japanese only as some of
the language does not work and may crash the server side. The view profile allows you
to view and update your profile.
Thank you for choosing HabitHub to accompany you on your journey to positive change
and personal growth!

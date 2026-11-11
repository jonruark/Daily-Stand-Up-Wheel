# Agile Stand-up Spinner

A web based, interactive tool designed to bring energy and efficiency to daily meetings. This application uses a customizable spinner wheel to select team members, tracks individual turn durations, and celebrates meeting completion with visual rewards. It also functions as an installable Progressive Web App (PWA) for mobile and desktop devices.

## Key Features

* **Interactive Spinner Wheel**: A high speed, physics based wheel used to randomly select the next speaker.
* **Instant "Go Now" Option**: Allows any team member to start their turn immediately from the To Do list without waiting for a wheel spin, automatically aligning the wheel to them.
* **Automatic Timer System**: A global count up timer starts on the first spin or manual selection to track the total meeting duration.
* **Turn Duration Tracking**: Automatically logs how long each person speaks and displays it in the completed list.
* **Attendance Management**: Use checkboxes to skip team members who are out of the office today without removing them from your permanent list.
* **Holiday Themed Palettes**: A popup settings menu allows you to switch between various color themes, including Vibrant Mix, Valentine's Day, St. Patrick's Day, Fourth of July, Halloween, Thanksgiving, and Christmas.
* **Color Stability & Dynamic Refresh**: Participants maintain consistent individual colors throughout a session, and colors are automatically re-randomized when starting a fresh stand-up.
* **Performance Recognition**: Once the meeting ends, the app bolds the name of the fastest speaker and rewards them with celebration emojis.
* **Confetti Animations**: A celebratory confetti blast triggers upon clicking "End Stand-up."
* **Progressive Web App (PWA)**: Includes manifest and service worker configuration so you can install the spinner directly to your Android or desktop home screen and use it offline.
* **Persistent Storage**: Saves your team names, completion states, turn times, and theme preferences to browser local storage.

## How to Use

1. **Setup your Team**: Add team member names in the "To Do" section.
2. **Manage Attendance**: Use the checkboxes next to names to include or exclude specific people from the wheel.
3. **Choose Who Speaks**:
   * Click **SPIN!** to let the wheel pick the next person at random.
   * Or click **Go now** next to any person's name in the To Do list to jump straight to their turn.
4. **Rotate Speakers**: Click **SPIN!** or **Go now** for the next person. The previous speaker will automatically move to the "Completed" section with their elapsed speaking time logged.
5. **Finish**: Once the last active participant is up, the button changes to **End Stand-up**. Click it to log their time, stop the timer, and trigger the confetti.
6. **Reset**: Click **Start New Stand-up** to return everyone to the To Do list with randomized colors for the next meeting.

## Customization

Click the **Settings Gear** icon in the top right corner to open the Settings modal. Select your preferred holiday theme from the dropdown menu to instantly restyle the wheel and confetti.

## Progressive Web App (PWA) Installation

When hosted on GitHub Pages or any HTTPS server:
* **Android (Chrome)**: Tap the browser menu or look for the banner prompt to select "Add to Home screen" / "Install app".
* **Desktop (Chrome/Edge)**: Click the install icon in the address bar to install it as a standalone desktop app.

## Local Development

1. Clone this repository.
2. Open `geminiwheel.html` directly in any modern browser, or serve the directory using a lightweight HTTP server (such as `npx serve` or Python's `python -m http.server`) to test PWA service worker features locally.

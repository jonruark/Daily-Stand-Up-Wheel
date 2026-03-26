Agile Stand-up Spinner
======================

A web based, interactive tool designed to bring energy and efficiency to daily meetings. This application uses a customizable spinner wheel to select team members, tracks individual turn durations, and celebrates meeting completion with visual rewards.

Key Features
------------

*   **Interactive Spinner Wheel**: A high speed, physics based wheel used to randomly select the next speaker.
    
*   **Automatic Timer System**: A global count up timer starts on the first spin to track the total meeting duration.
    
*   **Turn Duration Tracking**: Automatically logs how long each person speaks and displays it in the completed list.
    
*   **Participation Management**: Use checkboxes to skip team members who are out of the office today without removing them from your permanent list.
    
*   **Holiday Themed Palettes**: A settings menu allows you to switch between various color themes, including Valentine's Day, St. Patrick's Day, Fourth of July, Halloween, and Christmas.
    
*   **Performance Recognition**: Once the meeting ends, the app bolds the name of the fastest speaker and rewards them with celebration emojis.
    
*   **Confetti Animations**: A celebratory confetti blast triggers upon the final click of "End Stand-up."
    
*   **Persistent Storage**: The application saves your team names, completion states, and theme preferences to your browser local storage.
    

How to Use
----------

1.  **Setup your Team**: Add team member names in the "To Do" section.
    
2.  **Manage Attendance**: Use the checkboxes next to names to include or exclude specific people from the current wheel.
    
3.  **Start the Meeting**: Click the "SPIN" button. The timer will start automatically on the first spin.
    
4.  **Rotate Speakers**: After each person speaks, click "SPIN" again. The previous speaker will be moved to the "Completed" section with their time logged.
    
5.  **Finish**: Once the last person is selected, the button changes to "End Stand-up." Click it to stop the timer and trigger the confetti.
    
6.  **Reset**: Click "Start New Stand-up" to clear the board and assign a new, randomized color set to your team members for the next session.
    

Customization
-------------

Click the **Settings Gear** icon in the top right corner to access the Theme Menu. You can switch between several vibrant palettes to keep the meeting environment fresh and festive.

Technical Details
-----------------

*   **Language**: Pure HTML5, CSS3, and Vanilla JavaScript.
    
*   **Portability**: This is a single file application. No external dependencies, libraries, or installations are required.
    
*   **Assets**: All graphics (icons and wheel) are rendered using inline SVG and HTML Canvas for maximum performance and zero loading times.
    

Local Development
-----------------

Simply clone the repository and open geminiwheel.html in any modern web browser.

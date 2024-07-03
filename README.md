# PRODIGY_WD_02
Project Overview
The Stopwatch Web Application is a responsive and visually appealing stopwatch tool designed to provide an accurate and user-friendly time-tracking experience. This project leverages HTML, CSS, and JavaScript to create an interactive and functional stopwatch with various features such as start, pause, reset, restart, and lap functionalities.

Features
1. Stopwatch Display
The core feature of the application is the stopwatch display, which shows the elapsed time in a digital format (hours, minutes, seconds, and milliseconds). The display is designed to be large and clear, making it easy to read at a glance.

2. Responsive Design
The application is built with responsiveness in mind, ensuring that it looks great and functions well on devices of all sizes, from mobile phones to large desktop monitors. The CSS is crafted to adjust the layout and elements gracefully based on the screen size.

3. User Controls
The stopwatch includes a set of control buttons that allow users to:

Start: Begin the timer.
Pause: Temporarily halt the timer without resetting the elapsed time.
Reset: Set the timer back to zero and clear any recorded laps.
Restart: Stop and reset the timer, then immediately start it again.
Lap: Record the current time as a lap, which is displayed below the timer.
Reset Laps: Clear all recorded laps.
4. Lap Recording
Users can record multiple laps during a single timing session. Each lap is displayed in a list below the timer, allowing users to track individual segments of their timing session. This feature is particularly useful for activities like running or swimming, where tracking split times is essential.

5. Modern Design Aesthetics
The application features a modern and clean design, utilizing the Roboto font for a sleek look. The color scheme includes a calming blue background with a contrasting dark container and bright timer display, making the interface both attractive and easy to use.

Technical Details
HTML Structure
The HTML structure is straightforward and semantic, ensuring the content is well-organized and accessible. The main components include:

A container div that holds all the elements.
A title (Stopwatch) to provide context to the user.
The timer display to show the elapsed time.
An unordered list to display recorded laps.
A set of buttons for user interaction.
CSS Styling
The CSS is designed to enhance the visual appeal and usability of the application. Key styles include:

A flexible box layout for the container, centering it on the screen.
Stylish and responsive buttons with hover effects for better user interaction.
A polished timer display with a prominent font size and color scheme.
JavaScript Functionality
JavaScript is used to handle the stopwatch functionality. Key functions include:

start(): Initiates the timer and updates the display at regular intervals.
pause(): Pauses the timer and preserves the elapsed time.
reset(): Resets the timer and clears all laps.
restart(): Resets and starts the timer immediately.
lap(): Records the current time as a lap and displays it in the lap list.
resetLap(): Clears all recorded laps.
Implementation Details

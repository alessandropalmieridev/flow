# Pomodoro Timer

A simple Pomodoro timer implemented in HTML, CSS, and JavaScript with flow/rest phases, cycles counter, and total time tracking.

## Features

- **Flow & Rest settings:** User can configure minutes for work (flow) and break (rest).
- **Start/Stop Button:** Circular button toggles timer.
- **Phase Indicator:** Displays current phase (`FLOW`, `REST`, `IDLE`) with color coding.
- **Countdown Timer:** Shows remaining time in mm:ss.
- **Stats:** Tracks number of cycles completed and total time worked.
- **Input Validation:** Prevents invalid input for flow/rest minutes.
- **Responsive Design:** Works on desktop and mobile screens.
- **Sound Notification:** Beep when switching phases.

## Colors

| Element            | Color   |
| ------------------ | ------- |
| Flow phase         | #007aff |
| Rest phase         | #ff3b30 |
| Background         | #1c1c1e |
| Font color         | #f5f5f7 |
| Input label        | #6e6e73 |
| Button border/icon | #ff9500 |

## Usage

1. Open `index.html` in a browser.
2. Set Flow and Rest durations.
3. Click the **play button** to start the timer.
4. Click the **stop button** to reset.

## TODO

- [ ] Fix slight decentering of the start/stop button.
- [ ] Add configurable notification sounds.
- [ ] Add multiple language support (i18n).
- [ ] Store cycles and total time in local storage for persistence.
- [ ] Improve mobile layout and responsiveness.

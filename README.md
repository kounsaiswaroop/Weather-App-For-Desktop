# Desktop Weather App 🌦

A simple, no-frills weather app for your desktop that fetches weather updates with a single click!

## Setup Instructions

Follow these steps to set up the weather app:

1. **Open Notepad** on your computer.
2. Copy and paste the following lines of code into Notepad:

   ```batch
   @echo off
   curl wttr.in/yourcityname
   pause

`@echo off`: hides command details in the terminal.  
`curl wttr.in/yourcityname`: fetches the current weather for your city.  
`pause`: keeps the terminal window open to view the weather details.  

Save the file as `weather.bat` on your desktop.

## Usage

Double-click on the `weather.bat` file on your desktop whenever you want to check the weather! The app will open a command prompt window, retrieve, and display the latest weather information for your location.

## Example

To check the weather in London, you would edit the code as follows:

```batch
@echo off
curl wttr.in/London
pause


## Additional Notes

- Replace `yourcityname` with your city name (e.g., `Paris`, `NewYork`) or postal code.
- Requires an internet connection to fetch weather details from [wttr.in](https://wttr.in).

Enjoy quick weather updates directly on your desktop with ease!

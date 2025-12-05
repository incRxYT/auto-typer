# auto-typer
ever had a school assignment on typing.com well i think auto typer can help 
⌨️ Auto Typer HTA
A lightweight Windows application that simulates keyboard typing at 120 WPM with 100% accuracy. Perfect for typing practice, filling forms, or automating repetitive text entry.
🌟 Features

Fast & Accurate: Types at 120 WPM (adjustable) with perfect accuracy
Real Keyboard Simulation: Uses Windows SendKeys to simulate actual keystrokes
Progress Tracking: Live character count and percentage completion
Easy to Use: Simple copy-paste interface
No Installation: Runs directly as an HTA file
Stop Anytime: Pause typing with a single click
Special Characters: Handles all special characters, line breaks, and formatting

🚀 Getting Started
Prerequisites

Windows 7 or higher
No additional software required!

Installation

Download the hta from the releases
Double-click the file to run
That's it!

📖 How to Use

Paste Your Text: Copy any text and paste it into the text area
Click "Start Typing": Press the Start button
Switch Windows: You have 3 seconds to click into your target window (Google Docs, Word Online, typing practice site, etc.)
Watch It Type: The app will automatically type your text at 120 WPM

Pro Tips

Use with PowerToys Text Extractor (Win + Shift + T) to grab text from anywhere on screen
Perfect for typing practice websites
Great for filling out repetitive forms
Use the Stop button if you need to pause

⚙️ Customization
Want to change the typing speed? Edit line 154 in the code:
javascriptvar delay = 100;  // 100ms = ~120 WPM
Speed Reference:

50ms = ~240 WPM (very fast)
100ms = ~120 WPM (default)
200ms = ~60 WPM (moderate)
400ms = ~30 WPM (slow)

🎯 Use Cases

Typing Practice: Maintain consistent speed on typing trainer websites
Form Filling: Quickly fill repetitive form fields
Testing: Test text input fields in applications
Accessibility: Assist users who have difficulty typing
Content Entry: Speed up data entry tasks

🛠️ Technical Details

Technology: HTA (HTML Application)
Scripting: JavaScript + Windows Script Host
Method: ActiveX WScript.Shell SendKeys
Compatibility: Windows 7, 8, 10, 11

⚠️ Limitations

Windows only (uses Windows Script Host)
Cannot inject directly into browser tabs (requires manual window switching)
Cannot take screenshots or perform OCR (use PowerToys Text Extractor instead)
Requires focus on target window to type

🤝 Contributing
Feel free to fork this project and submit pull requests! Some ideas for contributions:

Adjustable speed slider in the UI
Multiple text profiles/templates
Keyboard shortcuts to start/stop
Sound effects or notifications
Dark mode theme

📝 License
This project is open source and available under the MIT License.
🙏 Acknowledgments

Built with help from Claude AI cuz my code is trash and somehow barly works
Inspired by the need for consistent typing practice
Thanks to all users who provided feedback!

📧 Contact
Have questions or suggestions? Open an issue on GitHub!<img width="1840" height="942" alt="Screenshot 2025-12-05 140640" src="https://github.com/user-attachments/assets/4c50e874-462c-405e-8b66-e71232500d07" />
<img width="1474" height="818" alt="Screenshot 2025-12-05 140633" src="https://github.com/user-attachments/assets/c92a8eeb-6515-4c5d-95f8-677e5c7374c3" />
<img width="481" height="57" alt="Screenshot 2025-12-05 140723" src="https://github.com/user-attachments/assets/9d11ab27-8d95-4a95-9927-04289d04da56" />
<img width="3439" height="1439" alt="Screenshot 2025-12-05 140719" src="https://github.com/user-attachments/assets/aab77aee-9fcd-4a3a-b599-cc896d677166" />
<img width="764" height="600" alt="Screenshot 2025-12-05 140657" src="https://github.com/user-attachments/assets/ad16c617-4deb-4217-9c87-252c39f5ffb6" />
<img width="1105" height="405" alt="Screenshot 2025-12-05 140648" src="https://github.com/user-attachments/assets/bc25a942-b68f-4f21-80d3-a1fef01ea6cd" />
<img width="55" height="74" alt="Screenshot 2025-12-05 140644" src="https://github.com/user-attachments/assets/88b4772d-e9e9-4b63-a131-6b2e2dd79003" />

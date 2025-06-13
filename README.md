# Weekly Checklist Web Application

This is a simple, mobile-friendly web application for tracking your weekly to-do items. It is designed for easy use on both desktop and mobile browsers, with progress saved automatically in your browser (using localStorage).

## Features
- **Collapsible daily sections** for each day of the week
- **Check/uncheck tasks** as you complete them
- **Progress is saved** in your browser (no login required)
- **Reset all** button to clear your progress
- **Modern, clean, touch-friendly design**

## How to Use
1. **Open the app:**
   - Visit [https://krizzle6.github.io/To-Do-Checklist/](https://krizzle6.github.io/To-Do-Checklist/) in your browser (works great on your phone!)
   - Or, open `index.html` locally in any web browser
2. **Check off items** as you complete them. Your progress is saved automatically.
3. **Reset All** to clear all checkmarks and start fresh.

## Customizing Your Checklist
- Edit the `index.html` file to change the days or tasks. The checklist data is in the `checklistData` JavaScript object near the top of the file.
- You can also edit `weekly_checklist.md` and regenerate the HTML if you want to automate updates.

## How It Works
- The app is a single HTML file with embedded CSS and JavaScript.
- No server or backend is required.
- All data is stored in your browser's localStorage, so your progress is private and device-specific.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is open source and available under the MIT License.

# Field Work Tracker

A Progressive Web App for tracking field service work, time, expenses, and tasks.

## Features

- ⏱️ **Time Tracking**: Track drive time and work time for each job
- 🗺️ **GPS Auto-Detection**: Automatically detect arrival when you stop after driving >15mph for >0.25 miles
- 📋 **To-Do Lists**: Create task lists for each job, check off completed items, track progress
- 👤 **Customer Info**: Store customer name, contact, facility, work scope
- 💰 **Expense Tracking**: Log expenses with categories and receipt photos
- 📊 **Daily & Weekly Reports**: Comprehensive reports with all time and expense details
- 💾 **Offline Support**: All data saved locally in your browser
- 📱 **Installable**: Add to home screen for app-like experience

## Quick Start

### Option 1: Use Online (Recommended)

1. Visit your GitHub Pages URL: `https://yourusername.github.io/repo-name`
2. On mobile, tap "Add to Home Screen"
3. Grant location permissions for GPS auto-detect
4. Start tracking!

### Option 2: Download and Use Locally

1. Download `index.html`
2. Open it in your browser
3. Works immediately!

## How to Use

### Starting a Job

1. Click **"Headed to Job"**
2. Fill in customer details
3. Add initial to-do tasks (optional)
4. Click **"Start Job"**

### During the Job

- Turn on **"Auto-Detect Driving"** for automatic arrival detection
- Or manually click **"Arrived Onsite"** when you get there
- Click **"📋 Manage Tasks"** to view/update your to-do list
- Check off completed tasks as you work
- Add new tasks on the fly

### Ending the Job

1. Click **"Left Site"** when done
2. Choose **"Another Job"** or **"Conclude Day"**

### Adding Expenses

1. Click **"💰 Add Expense"** anytime
2. Enter description, amount, category
3. Upload receipt photo (optional)
4. All expenses tagged to current date

### Viewing Reports

1. Click **"Reports"** tab
2. Choose **Daily** or **Weekly**
3. Select date
4. See complete breakdown of:
   - Drive time and work time
   - All jobs with task completion
   - All expenses with totals

## GPS Auto-Detection

For best GPS performance:
- Use HTTPS (GitHub Pages provides this automatically)
- Install as PWA (Add to Home Screen)
- Grant location permissions when prompted
- Keep auto-detect ON while driving to jobs

The app will automatically detect when you arrive at a job site by monitoring:
- Speed must exceed 15 mph
- Distance traveled must exceed 0.25 miles
- Then detects when you stop (speed ≤15 mph)

## Data Storage

- All data stored locally in browser localStorage
- Data persists between sessions
- No account required
- No data sent to servers
- Export/backup not yet available (coming soon!)

## Browser Support

Works on:
- ✅ Chrome (Android & Desktop)
- ✅ Safari (iOS & Mac)
- ✅ Edge
- ✅ Firefox

## Installation

Already installed on GitHub Pages! Just visit the URL and use it.

To update the app:
1. Upload new `index.html` to your repository
2. GitHub Pages updates automatically
3. Refresh the page on your device

## Troubleshooting

**GPS not working?**
- Make sure location permissions are granted
- HTTPS is required (GitHub Pages has this)
- Try installing as PWA for better GPS access

**Data disappeared?**
- Check if you're in the same browser
- Private/Incognito mode doesn't save data
- Clearing browser cache deletes all data

**App not installing?**
- Only works on HTTPS or localhost
- Try a different browser
- Some browsers don't support PWA install

## Support

This is a simple single-file PWA. All functionality is contained in `index.html`.

For issues or questions, refer to the code or create an issue in this repository.

## License

Free to use and modify for personal or commercial use.

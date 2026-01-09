# Claude Job Search Shortcuts

This repository contains backup copies of my Claude Chrome extension shortcuts for job hunting. Use these to quickly set up the same shortcuts on another machine.

## Shortcuts Included

1. **`/screen`** - Analyzes a page of job search results and categorizes postings into HIGH/MEDIUM/LOW/SKIP priority
2. **`/quick-scan`** - Quick YES/MAYBE/NO assessment of a single job posting
3. **`/analyse-job`** - Comprehensive job posting analysis with detailed assessment framework
4. **`/cover-letter`** - Generate a tailored cover letter for a job posting
5. **`/apply`** - Fill out job application forms with my personal information

## How to Import These Shortcuts

### On Your Current Machine (Backup):

1. Open Claude Chrome extension
2. Go to **Settings → Prompts**
3. You should see your "/" shortcuts listed
4. Take a screenshot or note the content of each shortcut
5. Copy the JSON from `shortcuts.json` in this repo to verify you have them all

### On a New Machine (Restore):

1. Install the Claude Chrome extension
2. Open the extension and go to **Settings → Prompts**
3. Click **"Create shortcut"** for each entry:
   - Set the **Trigger** (e.g., `/screen`)
   - Paste the **content** from the `shortcuts.json` file in this repo
   - Save each shortcut
4. Test each one by typing `/` in the Claude chat

## File Structure
```
├── shortcuts.json    # All shortcuts in JSON format
├── README.md        # This file
└── BACKUP_DATE.txt  # Optional: track when you last backed up
```

## Updating This Backup

When you add new shortcuts to Claude:
1. Update the `shortcuts.json` file with the new prompt
2. Commit with a message like: "Add new shortcut: /my-new-command"
3. Push to GitHub

## Tips

- Keep this repo **public** so you can access it from any machine
- Update it whenever you create new shortcuts or modify existing ones
- Consider adding a `BACKUP_DATE.txt` file with the date you last synced
- The `shortcuts.json` format makes it easy to share shortcuts with others or migrate between devices

---

**Last Updated:** [Add today's date]

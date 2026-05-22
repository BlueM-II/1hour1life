# Life of a Minos — Animation Planner

This is a **planning tool for your Minecraft movie**. It helps you organize all 22 scenes, track their story, music, and production status in one place.

## What Does It Do?

- **Scene Organization**: Plan all 22 scenes of your movie
- **Story Details**: Write the full story for each scene
- **Production Tracking**: Track status (Idea → Story Written → Recorded → Animated → Edited → Done)
- **Music & Sound**: Plan music mood, sound effects, and ambience for each scene
- **Trailer Planning**: Build a teaser without spoiling the movie
- **Auto-Save**: Everything saves to your browser automatically

## How to Use It

1. **Open the file**: Open `index.html` in any web browser
   - Double-click it, OR
   - Right-click → Open in browser
   
2. **Go through the tabs**:
   - **Overview**: Write your core story idea and production notes
   - **Scene Map**: See all 22 scenes at a glance
   - **Trailer / Server Ad**: Plan your movie teaser
   - **Music & Sound**: Plan audio elements

3. **Edit each scene**:
   - Click any scene number on the left sidebar
   - Write the scene story, music direction, sound effects, etc.
   - Everything saves automatically ✓

4. **Backup your work**:
   - Go to "Overview" tab
   - Click "Download Backup" to save your data as a file
   - Keep this file somewhere safe!

## Important Notes

⚠️ **Your data is stored in your browser only** — if you clear your browser data or use a different device, you'll lose everything. Always download backups!

To use on different devices:
1. Download a backup on Device A
2. Copy the backup file to Device B
3. (We can add restore feature if you need it!)

## File Structure

```
website/
├── index.html      (the only file you need - open this!)
└── README.md       (this file)
```

## Firebase Hosting

This project is also configured for Firebase Hosting.

If you want to publish it publicly, run:

```bash
npm install -g firebase-tools
firebase login
firebase deploy
```

The site's public folder is `website/`.

That's it! Just open `index.html` locally or deploy with Firebase Hosting. 🎬

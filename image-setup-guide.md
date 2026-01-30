# Image Setup Guide

## Quick Fix Steps:

### Method 1: Direct Save
1. Right-click the cyberpunk image in chat
2. Save as `profile.jpg` in your project folder
3. Refresh your browser

### Method 2: Alternative Filename
If the above doesn't work:
1. Save the image as `surya-profile.png` or `avatar.jpg`
2. Update the HTML src attribute to match your filename

### Method 3: Check File Location
Make sure your file structure looks like this:
```
your-portfolio-folder/
├── index.html
├── styles.css
├── script.js
├── profile.jpg  ← Your image should be here
└── README.md
```

### Method 4: Test with Browser Developer Tools
1. Open your portfolio in browser
2. Press F12 to open developer tools
3. Look for any error messages about the image
4. Check if the image path is correct

### Method 5: Use Base64 (Backup Solution)
If file saving doesn't work, I can convert the image to base64 code that embeds directly in the HTML.

## Troubleshooting:
- File must be in the same folder as index.html
- Filename must match exactly (case-sensitive)
- Try different formats: .jpg, .png, .jpeg
- Clear browser cache (Ctrl+F5)

Let me know which method works for you!
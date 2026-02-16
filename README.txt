CLAUDE CHAT ASSISTANT - DEPLOYMENT GUIDE
========================================

📦 FILES INCLUDED:
- index.html (your website with chat widget)
- api/chat.js (serverless function - keeps API key safe)
- vercel.json (configuration for Vercel)

🚀 DEPLOYMENT STEPS:

1. UPLOAD TO GITHUB:
   - Go to your GitHub repository
   - Upload all these files (keep api/chat.js inside the "api" folder)
   - Commit the changes

2. DEPLOY ON VERCEL (FREE):
   a. Go to https://vercel.com
   b. Click "Sign Up" and sign in with GitHub
   c. Click "Add New Project"
   d. Select your GitHub repository
   e. Click "Deploy" (Vercel will auto-detect everything)

3. ADD YOUR API KEY (IMPORTANT!):
   After deployment:
   a. Go to your project dashboard on Vercel
   b. Click "Settings" → "Environment Variables"
   c. Add new variable:
      - Name: ANTHROPIC_API_KEY
      - Value: [paste your API key from https://console.anthropic.com]
   d. Click "Save"
   e. Go to "Deployments" tab and click "Redeploy" on latest deployment

✅ DONE! 
Your site will be live at: your-project-name.vercel.app

The chat widget will appear in the bottom right corner!

💡 TIPS:
- The chat widget automatically shows Sarah's greeting when opened
- You can customize the colors in index.html (search for "#667eea" and "#764ba2")
- Free Vercel tier is perfect for personal projects
- Every GitHub push = automatic redeployment

NEED HELP? 
Check Vercel docs: https://vercel.com/docs

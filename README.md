Step 6: Initialize Git
git init
Step 7: Add Files
git add .
Step 8: Commit Files
git commit -m "First Commit"
Step 9: Create Repository on GitHub

Go to GitHub

Click:

New Repository

Name:

WAD-AWS-App

Click:

Create Repository
Step 10: Connect Local Folder to GitHub

Copy GitHub commands and run:

git branch -M main
git remote add origin https://github.com/YourUsername/WAD-AWS-App.git
git push -u origin main
PART D — Deploy on AWS Amplify from 0
Step 11: Login AWS

Go to Amazon Web Services Console.

Login.

Step 12: Search Amplify

Search:

Amplify

Open AWS Amplify

Step 13: Click Create App

Choose:

Host Web App
Step 14: Select GitHub

Choose:

GitHub

Click Continue.

Authorize GitHub.

Step 15: Choose Repository

Select:

Repository: WAD-AWS-App
Branch: main

Click Next.

Step 16: Build Settings

Keep default settings.

Click Next.

Step 17: Save and Deploy

Click:

Save and Deploy

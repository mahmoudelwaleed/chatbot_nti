# 0.create the remote 
# 1. Navigate to your project directory
cd path/to/your/project
# Example:
cd D:\nti\chatbot
# 2. Initialize the Git repository
git init
# 3. Create a README file (optional)
# 4. Add all files to staging
git add .
# 5. Make your first commit
git commit -m "Initial commit"
# 6. Rename the branch to 'main' (GitHub default)
git branch -M main
# 7. Add the remote repository (replace URL with your actual repo)
git remote add origin https://github.com/mahmoudelwaleed/chatbot_nti.git
# 8. Push the code to GitHub
git push -u origin main

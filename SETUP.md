# GitHub Repository Setup Instructions

1. Create a new repository on GitHub
   - Go to GitHub.com
   - Click 'New repository'
   - Name it 'vanilla-js-tailwind-template'
   - Check 'Template repository' under Settings
   - Add description: 'Template for vanilla JavaScript projects with Tailwind CSS'
   - Make it Public
   - Add README, .gitignore (Node), and MIT License

2. Initialize local repository and push:
   ```bash
   git init
   git add .
   git commit -m 'Initial commit: Template setup'
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/vanilla-js-tailwind-template.git
   git push -u origin main
   ```

3. On GitHub:
   - Go to repository settings
   - Under 'Template repository', check 'Template repository'
   - Configure branch protection rules if desired
   - Enable GitHub Pages if you want to show a demo

4. Usage:
   - Click 'Use this template' on GitHub
   - Name your new project
   - Clone and start developing


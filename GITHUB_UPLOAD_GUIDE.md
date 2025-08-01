# Complete Guide: Uploading AfricaCrypto to GitHub

This comprehensive guide will walk you through uploading your AfricaCrypto project to GitHub from scratch.

## 📋 Prerequisites

Before starting, ensure you have:
- A GitHub account ([sign up here](https://github.com/join))
- Git installed on your computer ([download here](https://git-scm.com/downloads))
- Your AfricaCrypto project files ready

## 🚀 Step-by-Step Upload Process

### Step 1: Prepare Your Project

1. **Download/Export your project files** from Lovable
2. **Organize your project structure** - ensure all files are in the correct folders
3. **Review the files** - make sure you have all necessary components

### Step 2: Create GitHub Repository

1. **Log into GitHub** and navigate to your dashboard
2. **Click the "+" icon** in the top right corner
3. **Select "New repository"**
4. **Fill in repository details**:
   - Repository name: `africacrypto` (or your preferred name)
   - Description: "Cryptocurrency education platform for African communities"
   - Set to **Public** (recommended for educational projects)
   - ✅ **DO NOT** initialize with README (you already have one)
   - ✅ **DO NOT** add .gitignore (project already has one)
   - ✅ **DO NOT** choose a license (you already have LICENSE file)
5. **Click "Create repository"**

### Step 3: Initialize Git in Your Project

Open terminal/command prompt in your project folder and run:

```bash
# Navigate to your project directory
cd path/to/your/africacrypto/project

# Initialize git repository
git init

# Add all files to staging
git add .

# Create initial commit
git commit -m "Initial commit: AfricaCrypto education platform"
```

### Step 4: Connect to GitHub Repository

```bash
# Add your GitHub repository as remote origin
git remote add origin https://github.com/YOURUSERNAME/africacrypto.git

# Verify the remote is added correctly
git remote -v
```

**Replace `YOURUSERNAME`** with your actual GitHub username!

### Step 5: Push to GitHub

```bash
# Push your code to GitHub
git push -u origin main
```

If you encounter an error about "main" vs "master" branch:
```bash
# Rename branch to main if needed
git branch -M main
git push -u origin main
```

## 🔧 Essential Files Checklist

Ensure your repository includes these files:

### ✅ Core Files
- [ ] `README.md` - Project documentation
- [ ] `package.json` - Dependencies and scripts
- [ ] `package-lock.json` - Locked dependency versions
- [ ] `LICENSE` - MIT License file
- [ ] `.gitignore` - Files to ignore in git
- [ ] `index.html` - Main HTML file
- [ ] `vite.config.ts` - Vite configuration
- [ ] `tailwind.config.ts` - Tailwind CSS configuration
- [ ] `tsconfig.json` - TypeScript configuration

### ✅ Source Code
- [ ] `src/` folder with all components
- [ ] `src/components/` - React components
- [ ] `src/pages/` - Page components
- [ ] `src/hooks/` - Custom React hooks
- [ ] `src/contexts/` - React contexts
- [ ] `src/lib/` - Utility functions
- [ ] `src/integrations/` - Third-party integrations

### ✅ Documentation
- [ ] `CONTRIBUTING.md` - Contribution guidelines
- [ ] `.env.example` - Environment variables template

## 🔐 Environment Variables Setup

1. **Create `.env.example`** (already done in this guide)
2. **Never commit actual `.env` files** with real credentials
3. **Document required environment variables** in README
4. **For deployment**, add environment variables in your hosting platform

## 🌐 Setting Up for Deployment

### Option 1: Vercel (Recommended)

1. Go to [vercel.com](https://vercel.com)
2. Sign up/login with GitHub
3. Click "New Project"
4. Import your GitHub repository
5. Configure build settings:
   - Build Command: `npm run build`
   - Output Directory: `dist`
6. Add environment variables in Vercel dashboard
7. Deploy!

### Option 2: Netlify

1. Go to [netlify.com](https://netlify.com)
2. Sign up/login with GitHub
3. Click "New site from Git"
4. Choose your repository
5. Configure build settings:
   - Build Command: `npm run build`
   - Publish Directory: `dist`
6. Add environment variables in Netlify dashboard
7. Deploy!

## 📝 Repository Management Best Practices

### Branching Strategy
```bash
# Create feature branch
git checkout -b feature/new-module

# Make changes, then commit
git add .
git commit -m "Add: Module 8 trading basics"

# Push feature branch
git push origin feature/new-module

# Create Pull Request on GitHub
# After review and merge, switch back to main
git checkout main
git pull origin main
```

### Commit Message Convention
- `Add:` for new features
- `Fix:` for bug fixes
- `Update:` for modifications
- `Remove:` for deletions
- `Docs:` for documentation

Examples:
```bash
git commit -m "Add: Module 8 trading principles"
git commit -m "Fix: Quiz navigation bug on mobile"
git commit -m "Update: Improved wallet security content"
git commit -m "Docs: Add deployment instructions"
```

## 🐛 Troubleshooting Common Issues

### Issue: "remote origin already exists"
```bash
git remote remove origin
git remote add origin https://github.com/YOURUSERNAME/africacrypto.git
```

### Issue: "failed to push some refs"
```bash
git pull origin main --rebase
git push origin main
```

### Issue: Large files or build folders
Make sure your `.gitignore` includes:
```
node_modules/
dist/
.env
.env.local
.DS_Store
```

## 📊 GitHub Repository Settings

After uploading, configure these settings:

### Repository Settings
1. **Description**: Add project description
2. **Topics**: Add relevant tags (`cryptocurrency`, `education`, `react`, `africa`)
3. **Website**: Add your deployed site URL
4. **Issues**: Enable for bug reports
5. **Discussions**: Enable for community

### Branch Protection (Recommended)
1. Go to Settings → Branches
2. Add rule for `main` branch
3. Enable "Require pull request reviews"
4. Enable "Require status checks"

## 🎯 Next Steps After Upload

1. **Update README.md** with your actual GitHub URLs
2. **Set up GitHub Actions** for automated testing (optional)
3. **Create issues** for planned features
4. **Add contributors** if working with a team
5. **Share your repository** with the community

## 📞 Need Help?

If you encounter issues:
1. Check GitHub's [official documentation](https://docs.github.com)
2. Search for solutions on [Stack Overflow](https://stackoverflow.com)
3. Create an issue in your repository for project-specific problems

## 🎉 Congratulations!

Your AfricaCrypto project is now on GitHub! You can:
- Share the repository URL with others
- Deploy to hosting platforms
- Collaborate with other developers
- Track issues and feature requests
- Build a community around your project

**Repository URL format**: `https://github.com/YOURUSERNAME/africacrypto`

---

**Happy coding and welcome to the open-source community! 🚀**

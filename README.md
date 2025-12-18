# Himanshu Choudhary - Cyberpunk Portfolio

A modern, responsive cyberpunk-themed portfolio website showcasing projects, skills, and achievements.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Cyberpunk Aesthetic**: Neon colors, glitch effects, and gaming-inspired design
- **Interactive Elements**: 
  - Animated custom cursor with glow effects
  - Smooth scroll animations
  - Mobile sidebar navigation
  - Terminal-style sections
  - Glitch text effects
- **Smooth Animations**: Scroll-triggered animations and transitions
- **Modern Tech Stack**: Pure HTML, CSS, and JavaScript

## Live Demo

Visit the deployed portfolio: [Your Render URL]

## Deployment on Render

### Prerequisites
- GitHub account
- Render account (https://render.com)

### Steps to Deploy

1. **Initialize Git Repository** (if not already done)
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial commit: Cyberpunk portfolio"
   ```

2. **Push to GitHub**
   - Create a new repository on GitHub
   - Push your code:
     ```bash
     git remote add origin https://github.com/yourusername/portfolio.git
     git branch -M main
     git push -u origin main
     ```

3. **Deploy on Render**
   - Go to https://render.com
   - Sign in with GitHub
   - Click "New +" → "Web Service"
   - Select your portfolio repository
   - Configure:
     - **Name**: himanshu-portfolio (or your preferred name)
     - **Environment**: Node
     - **Build Command**: `npm install`
     - **Start Command**: `npm start`
     - **Plan**: Free (or choose your preferred plan)
   - Click "Create Web Service"

4. **Wait for Deployment**
   - Render will automatically build and deploy your project
   - Your portfolio will be live at: `https://your-service-name.onrender.com`

### Local Development

```bash
# Install dependencies
npm install

# Run locally
npm start

# Visit http://localhost:3000
```

## Project Structure

```
portfolio/
├── index.html          # Main portfolio page
├── server.js           # Express server
├── package.json        # Dependencies and scripts
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## Technologies Used

- HTML5
- CSS3 (with animations and gradients)
- JavaScript (ES6+)
- Express.js (for serving)
- Font Awesome (for icons)
- Google Fonts

## Customization

- Edit `index.html` to update content
- Modify CSS variables in the `<style>` section for colors
- Update project links and information
- Change social media links

## License

MIT License - feel free to use this portfolio template for your own projects!

## Author

Himanshu Choudhary
- Email: 1130himanshu@gmail.com
- GitHub: https://github.com/Himanshu8850
- LinkedIn: https://www.linkedin.com/in/himanshu-choudhary-178618245/

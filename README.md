# My Portfolio
A modern, responsive personal portfolio website to showcase my projects, skills, and professional background.

## 🌟 Overview
This portfolio is built to highlight my work as a Frontend Developer, Full-Stack Engineer, UX Designer and serve as a central hub for potential employers, collaborators, or clients to learn about my experience and projects.

### Key Features
- Responsive design (works on mobile, tablet, and desktop)
- Project showcase with descriptions, tech stacks, and live demos/github links
- Skills section with proficiency indicators
- About me / professional background
- Contact form/links for easy outreach
- Dark/light mode toggle (optional)

## 🚀 Live Demo
Check out the live version of the portfolio:  
<a href="https://decentcoders.netlify.app/" target="_blank">
https://decentcoders.netlify.app/
</a>
## 🛠️ Tech Stack
| Category       | Technologies                                                                 |
|----------------|------------------------------------------------------------------------------|
| Frontend       | HTML5, CSS3, JavaScript, Vue,Nuxt, Tailwind CSS (or Bootstrap) |
| Build Tools    | Vite (or Webpack), npm/yarn/pnpm                                             |
| Deployment     | Netlify (or Vercel, GitHub Pages)                                            |
| Other          | Git, Figma (for design), Font Awesome (icons)                                |



## 🔧 Getting Started
### Prerequisites
- Node.js (v16+ recommended)
- npm/yarn/pnpm (package manager)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-portfolio-repo.git
   cd your-portfolio-repo
   ```

2. Install dependencies:
   ```bash
   # Using npm
   npm install

   # Using yarn
   yarn install

   # Using pnpm
   pnpm install
   ```

3. Run the development server:
   ```bash
   # npm
   npm run dev

   # yarn
   yarn dev

   # pnpm
   pnpm dev
   ```

4. Open [http://localhost:300](http://localhost:300)  

### Build for Production
```bash
# npm
npm run build

# yarn
yarn build

# pnpm
pnpm build
```
The production build will be generated in the `dist/` (or `build/`) folder.

## 📝 Customization
- Update `src/data/projects.js` to add/remove your projects
- Modify `src/data/skills.js` to update your skills and proficiencies
- Edit `src/pages/About.js` to update your professional bio
- Change colors/themes in `src/styles/globals.css` (or Tailwind config)
- Update the contact form settings (if using a service like Formspree)


⭐️ If you like this portfolio template, feel free to star the repo or fork it for your own use!

### Notes to Customize:
1. Replace all placeholder text (e.g., `your-username`, `your.email@example.com`, tech stack, links) with your actual information.
2. Add/remove sections based on your needs (e.g., remove "Screenshots" if you don’t have them, add a "Testimonials" section if relevant).
3. Update the tech stack to match what you used (e.g., if you used Vanilla JS instead of React, adjust that).
4. Add screenshots to the `public/screenshots/` folder (or remove the section if you don’t want to include them).
5. If you’re not using a deployment service like Netlify, remove the Netlify status badge.
6. Adjust the project structure to match your actual folder setup.

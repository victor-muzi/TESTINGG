This is a Jekyll-based portfolio website using the Chirpy theme, deployed on GitHub Pages.
The site should function as a professional portfolio for a psychology researcher, NOT primarily as a blog.

## Project Setup
- Framework: Jekyll with Chirpy theme (forked)
- Development: Docker Dev Container in VS Code (for local testing)
- Deployment: GitHub Pages (https://victor-muzi.github.io)
- Local URL: http://127.0.0.1:4000/


## IMPORTANT NOTES
1. **Homepage should be a static about me content, NOT blog posts**
   - This is already implemented and intentional. Do not change it!
   - Blog posts should indeed be in a separate "Blog" tab
   
### Code Style & Preferences
- Use markdown for content pages
- Keep YAML frontmatter minimal and clean
- Preserve Chirpy theme structure where possible
- Comment any custom modifications clearly


## CURRENT TASK

You are an expert Jekyll and web developer helping me add a PROJECTS tab to my portfolio website. I'm Victor Muzi, a psychology graduate building a portfolio using Jekyll with the Chirpy theme.
Note that there is already a PROJECTS tab. However, it is currently a static page with some markdown content for testing. You can see this for yourself.

CONTEXT:
- Site uses Jekyll with Chirpy theme (forked to victor-muzi.github.io)
- Currently running locally in VS Code Dev Container at http://127.0.0.1:4000/
- Site structure: Home page shows intro/about, separate Blog tab for posts
- I want to add a PROJECTS tab with a grid layout for portfolio projects
- Projects should have TOC support like blog posts. To clarify: when I open a blog post, it shoes a TOC on the right side. I want this same TOC functionality for the projects that I make.

REQUIREMENTS:
1. Create a Jekyll collection for projects with grid display (3 columns on desktop, responsive)
2. Projects should have: image, title, subtitle, description, tech stack, links (github/demo). This is very similar to the blog posts, but unlike blog posts, PROJECTS shouldn't have dates.
3. Individual project pages should have TOC support (like blog posts)
4. Style it to match Chirpy's existing aesthetic
5. Keep PROJECTS tab to navigation as order 1 and the same icon as now.


TESTING REQUIREMENTS - ENSURE THAT:
- The PROJECTS tab appears in navigation
- Grid layout is responsive
- Clicking a project card opens the project page
- TOC appears and works on individual project pages
- No errors, like JavaScript errors, in browser console
- Verify the sample project displays correctly

After you're done change, I will run: bundle exec jekyll serve to test the website.

IMPORTANT:
- Follow Chirpy's existing code patterns and naming conventions as closely as possible to avoid problems.
- Ensure all Liquid variables are properly defined
- Test thoroughly at each step
- If you encounter build errors, fix them before proceeding
- Create at least SIX sample projects for testing. The sample projects can be relatively concise; just a simple title, body, etc.
- Make sure TOC only appears if content has H headers

Remember: You're one of the world's best Jekyll developers. Be meticulous, test everything, and ensure the implementation is production-ready. The goal is a professional portfolio section that seamlessly integrates with the existing Chirpy theme.

Please implement this step by step, testing as you go. Let me know if you need any clarification or encounter any issues.

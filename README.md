# Task: Build a Multi-Page AI Developer Portfolio Website for Konde Keerthi

Act as a senior full-stack developer, Next.js specialist, UI/UX designer, and portfolio architect. Build a complete, responsive, professional developer portfolio website for me.

**Important: Do not create only a README file. Build an actual multi-page website with navigation buttons that open separate pages for each section.** Implement the website directly in the current working directory.

## 1. My Profile Details

- Name: Konde Keerthi
- Role: programmer
- Organization: PCS, Police Department (Chief Office)
- Education: B.Tech in Electronics and Communication Engineering
- Interests: AI-assisted development, web development, data analytics, automation, and DevOps.

## 2. Technology Stack

Use the following technologies:

- Frontend: Next.js, HTML, CSS
- Programming approach: Reusable components and clean code
- Version control: Git and GitHub
- AI coding tools: OpenCode and Cline
- Deployment: Vercel or Netlify
- Other tools: CLI-based development tools

First inspect the current project directory. If a Next.js application already exists, work with its existing structure and dependencies. If the directory is empty, create a suitable Next.js application structure.

Use JavaScript unless the existing project already uses TypeScript.

## 3. Website Design

Create a modern, professional portfolio with the following design:

- Dark background with blue and purple gradient accents.
- Clean typography and attractive spacing.
- Modern cards with subtle borders, rounded corners, and shadows.
- Smooth hover effects and subtle transitions.
- Responsive design for desktop, tablets, and mobile phones.
- Consistent navigation across every page.
- Professional AI and technology-inspired visual style.
- A polished footer on every page.

Avoid excessive animations, unnecessary elements, and clutter.

## 4. Navigation Buttons and Separate Pages

Create a navigation bar at the top of every page. Each navigation item must be a working button or link that opens its corresponding page.

Create these pages:

### Page 1: Home

Route: `/`

Include:

- A welcoming heading: "Hi, I'm Konde Keerthi."
- Professional title: "AI Developer | Web Development | Data Analytics"
- A short introduction about my current role and education.
- A professional hero section.
- A "View My Skills" button linking to `/skills`.
- A "Explore My Projects" button linking to `/projects`.
- A "Contact Me" button linking to `/contact`.
- A GitHub button that opens my GitHub profile once the correct URL is configured.

Use attractive typography and a modern dark-tech design.

### Page 2: About Me

Route: `/about`

Include:

- My current role as an AI Developer at PCS, Police Department (Chief Office).
- My B.Tech in Electronics and Communication Engineering.
- My interest in AI-assisted software development.
- My interest in building practical web applications and data-driven solutions.
- My focus on continuous learning and problem-solving.

Use a professional profile layout with clearly organized information.

### Page 3: Skills

Route: `/skills`

Organize my skills into cards or grouped sections.

**Web Development**

- HTML
- CSS
- Next.js

**Database & Analytics**

- SQL
- Power BI

**AI-Assisted Development Tools**

- Cline
- OpenCode
- CLI-based AI coding tools

**Version Control**

- Git
- GitHub

**Deployment & Hosting**

- Vercel
- Netlify

**DevOps & Workflows**

- CLI tools
- Development workflows
- DevOps practices

Important design requirement:

Display each technology's icon followed immediately by its name on the same line.

For example:

HTML icon — HTML
CSS icon — CSS
Next.js icon — Next.js

Use individual icons rather than combining all icons into a single image. Use reliable icon sources, appropriate alt text, and consistent icon sizes.

Do not claim unverified proficiency levels.

### Page 4: Tools

Route: `/tools`

Create a dedicated page for the tools I use.

Include cards for:

- Cline
- OpenCode
- Git
- GitHub
- Next.js
- Vercel
- Netlify
- CLI development tools

Each card should include:

- Tool icon or logo.
- Tool name.
- A short, accurate description of its purpose.
- An official website link when appropriate.

Use consistent card dimensions and responsive layouts.

### Page 5: Projects

Route: `/projects`

Create a professional projects gallery.

Initially, include three editable placeholder project cards.

Each card should contain:

- Project title.
- Short description placeholder.
- Technologies placeholder.
- GitHub repository link placeholder.
- Optional live demo link.

Do not invent actual projects, repository links, achievements, or completed applications.

Make it easy to add real projects later by updating a reusable project data structure.

If a repository or demo URL has not been configured, do not display a broken link.

### Page 6: Currently Learning

Route: `/learning`

Include my learning interests:

- AI-assisted software development.
- AI-powered applications.
- Modern web development with Next.js.
- Application deployment.
- Automation and DevOps workflows.
- CLI-based development tools.

Present these as learning interests rather than verified expertise.

Use attractive cards with short descriptions and suitable icons.

### Page 7: GitHub Statistics

Route: `/github`

Include:

- GitHub profile overview.
- GitHub statistics card.
- Most-used languages card.
- Contribution streak card if a reliable service is available.
- A button linking to my GitHub profile.

Use a configurable GitHub username, such as `YOUR_GITHUB_USERNAME`.

Do not invent GitHub statistics. Load them from a suitable external service where available.

If the statistics service fails or is unavailable, display a helpful fallback message and keep the rest of the page functional.

### Page 8: Contact

Route: `/contact`

Create a professional contact page containing:

- GitHub profile link.
- LinkedIn profile link.
- Professional email address.
- Portfolio links where appropriate.

Use placeholders for details I have not provided.

Add attractive contact cards with icons and working links once the real details are configured.

Do not invent contact details.

Do not create a fake contact form that appears to send messages without a working backend.

## 5. Navigation and Button Functionality

This is a critical requirement.

- Every navigation button must work.
- Each section must have its own URL and page.
- Use Next.js routing correctly.
- Highlight the current page in the navigation bar.
- Keep the navigation consistent across all pages.
- Add a mobile navigation menu for smaller screens.
- Add hover and focus states to buttons.
- Ensure all links have meaningful destinations.
- Add a consistent logo or text brand using "KK" or "Konde Keerthi".
- Include a footer with links to the main pages.

Do not implement all pages as hidden sections on a single page. I specifically want separate pages with separate routes.

Use Next.js App Router if starting a new project. If an existing project uses another valid routing structure, preserve it where reasonable.

## 6. Shared Components

Create reusable components, such as:

- `Navbar`
- `Footer`
- `Button`
- `SkillCard`
- `ToolCard`
- `ProjectCard`
- `SocialLinks`

Keep the components organized and avoid duplicating navigation or layout code.

Use a shared layout so the header, navigation, and footer remain consistent on every page.

## 7. Responsive Design and Accessibility

Ensure that:

- The website works on desktop, tablet, and mobile.
- Cards adapt to screen width.
- Navigation remains usable on mobile.
- Images have meaningful alt text.
- Buttons and links are keyboard accessible.
- Text has sufficient contrast.
- The website does not have horizontal overflow.
- All routes render without errors.

## 8. GitHub README

Create a separate root-level `README.md` that:

- Introduces me professionally.
- Summarizes my skills and tools.
- Explains the portfolio's page structure.
- Provides instructions for running the website locally.
- Explains how to configure GitHub, LinkedIn, email, and project links.
- Explains how to deploy the website using Vercel or Netlify.

The README is documentation for the website, not a replacement for the actual multi-page application.

## 9. OpenCode Implementation Instructions

Perform the implementation directly in the current working directory.

1. Inspect the existing files and determine whether a Next.js project already exists.
2. Preserve existing useful code and configuration.
3. Create or update the required application files.
4. Implement every page and shared component.
5. Add the required CSS and responsive styles.
6. Install dependencies only when necessary and with my permission where the environment requires approval.
7. Configure navigation, icons, and placeholder links.
8. Run the available lint, build, and other relevant checks.
9. Fix errors caused by the implementation.
10. Verify that every navigation route is implemented and that buttons have working destinations.
11. Do not delete unrelated files or overwrite existing work unnecessarily.
12. Do not push to GitHub or deploy publicly without my explicit permission.

Do not stop after describing the implementation. Create the actual files and code.

## 10. Final Deliverables

Provide:

- A complete working multi-page portfolio website.
- All required page routes.
- Reusable components and responsive styling.
- A separate `README.md`.
- Instructions for starting the project locally.
- A list of placeholders I must replace.
- Instructions for publishing the website through Vercel or Netlify.

At the end, summarize the files created, checks performed, and any remaining tasks.

**Success criteria:** I should be able to start the application, click each navigation button, open every separate page, view my technical skills and tools, and navigate back to the other pages without errors.

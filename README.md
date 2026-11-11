# Gitonga Muchiri Personal Portfolio

This is my personal portfolio website. I used HTML and CSS to introduce myself, share my education, interests, skills and project ideas, and provide my contact details.

## Files in this project

- `index.html` — page structure, content and a small script for the mobile menu and contact form
- `style.css` — external stylesheet, responsive layout and hover effects
- `images/gitonga-profile.jpg` — profile photograph

## What the website includes

- Semantic HTML elements (`header`, `nav`, `main`, `section`, `footer`)
- Home, About, Skills, Projects, a learning table and Contact sections
- Lists, a table, hyperlinks, image and contact form
- CSS Grid and Flexbox layouts
- Responsive navigation for smaller screens
- Mobile-friendly design and interactive hover states

## Opening the website on your computer

Download or clone the repository, then open `index.html` in a web browser. No build tools are required.

## Publishing with GitHub Pages

1. Create a public GitHub repository named `personal-portfolio`.
2. Upload `index.html`, `style.css`, the `images` folder and this README.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

## Things to check before publishing

- Confirm that the email address and phone number in `index.html` are correct before publishing.
- The supplied profile photograph is saved locally as `images/gitonga-profile.jpg`.
- Review the education details, interests and project descriptions so they accurately reflect your experience. Projects marked **PROPOSED** are concepts, not completed work.

## Suggested Git commits

1. `Initialise portfolio project structure`
2. `Add semantic HTML portfolio sections`
3. `Create responsive CSS layout and visual theme`
4. `Add project cards and skills section`
5. `Add contact form and mobile navigation`
6. `Write project documentation and prepare GitHub Pages`

## Testing checklist

- [ ] All navigation links move to the correct section.
- [ ] Profile image loads correctly.
- [ ] Contact email is correct.
- [ ] Contact form opens the user's email application.
- [ ] Layout is usable on desktop and mobile.
- [ ] No horizontal overflow appears on a phone-sized screen.
- [ ] HTML and CSS have been checked for errors.
- [ ] Desktop and mobile screenshots have been captured for submission.

## About the contact form

There's no backend. When someone hits send, a bit of JavaScript builds a `mailto:` link from what they typed and opens their email app, so nothing is stored or delivered by the site itself. A form service (Formspree, Netlify Forms and so on) would be needed for real submissions.

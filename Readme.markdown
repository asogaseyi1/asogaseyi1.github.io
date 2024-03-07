---
layout: page
title: Read me
permalink: /README/
---

## Title
Hosting and Formatting Resume on GitHub Pages with Markdown

## Purpose
The purpose of this README is to provide practical steps for hosting and formatting a resume using Markdown on GitHub Pages or Codeberg Pages. It also aims to relate these steps to the general principles of current Technical Writing, as explained in Andrew Etter's book Modern Technical Writing.

## Prerequisites
To follow the steps outlined in this README, you should have a resume formatted in Markdown. If you're unfamiliar with Markdown, you can find a good tutorial [here](https://www.markdowntutorial.com/).
to host it as a static website on Github pages, I initially had to download Ruby and Jekyll onto my system, You would need to do that as well.

## Instructions
### Step 1: Format Your Resume in Markdown
1. Open a text editor.
2. Create a new file and save it with a `.md` extension.
3. Format your resume using Markdown syntax. Include headers, bullet points, and other formatting as necessary.

### Step 2: Create a GitHub Account (if you don't have one)
1. Go to [GitHub](https://github.com/).
2. Sign up for a new account if you don't already have one.
3. Verify your email address and complete the registration process.

### Step 3: Create a New Repository for Your Resume
1. Log in to your GitHub account.
2. Click on the "+" icon in the top right corner and select "New repository."
3. Name your repository (e.g., `resume`) and add a description if desired.
4. Choose whether to make your repository public or private.
5. Click on "Create repository."

### Step 4: Upload Your Resume Markdown File to the Repository
1. Open the repository you just created.
2. Click on the "Add file" dropdown and select "Upload files."
3. Choose your Markdown resume file from your computer and click on "Open."
4. Once the file is uploaded, click on "Commit changes."

### Step 5: Enable GitHub Pages
1. Go to the "Settings" tab of your repository.
2. Scroll down to the "GitHub Pages" section.
3. Under "Source," select "main" branch or "master" branch depending on your repository settings.
4. Click on "Save."

### Step 6: Create the site with jekyll
1. Clone your repository into a local folder using git clone in the command line
2. run jekyll in the repository with the command "jekyll new --skip-bundle ."
3. Open the GemFile created by jekyll
4. Comment out the line that begins with gem jekyll
5. Edit the line with "# gem githup-pages" removing the # and putting the version number after the arrow
6. Save and close the GemFile, then run bundle install on your command line
7. add, commit, and push your changes to your repository. 

### Step 7: Access Your Hosted Resume
1. After enabling GitHub Pages, scroll back down to the "GitHub Pages" section in the repository settings.
2. You'll see a link to your hosted resume. It will typically be in the format `https://<username>.github.io/<repositoryname>/`.
3. Click on the link to view your hosted resume in the browser.
   
   ![This is how mine turned out](resume.gif)

   The above is how my resume turned out.

## More Resources
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Codeberg Pages Documentation](https://docs.codeberg.org/codeberg-pages/)
- [Creating a site with jekyll Documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)


## Authors and Acknowledgements
Credit to the modern writer Resume template on Google Docs.
My group members Anmol Singh and Zander Apalit



## FAQs
### Why is Markdown better than a word processor?
Markdown offers a lightweight and straightforward syntax for formatting text, making it easy to write and maintain documents without the clutter of a traditional word processor. It also allows for version control and seamless integration with platforms like GitHub.

### Why is my resume not showing up?
If your resume is not showing up after enabling GitHub Pages, double-check that your Markdown file is named correctly (typically `index.md` for the main page, I found that 'README.md' works in absence of that as well) and that it's located in the root directory of your repository. Also, ensure that GitHub Pages is enabled for the correct branch (usually `main` or `master`). If you're still having issues, review the GitHub Pages documentation or seek assistance from me or the GitHub community.
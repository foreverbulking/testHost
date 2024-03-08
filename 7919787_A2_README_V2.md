# Resume Hosting Guide

Welcome to my GitHub repository, where I, Nishan Sanyasi, demonstrate the process of hosting a Markdown-formatted resume using GitHub Pages. This README not only guides you through hosting your own resume but also applies the principles of modern technical writing as recommended by Andrew Etter.

## Purpose

The main objectives of this document are to:
- Illustrate a practical application of hosting a resume on GitHub Pages, providing a hands-on example.
- Discuss how this process embodies Andrew Etter's Modern Technical Writing principles, particularly the use of lightweight markup languages, static site generators, and distributed version control systems.
- Offer insights into creating and managing effective technical documentation using platforms like GitHub, complemented by tools such as Jekyll for a more refined control over the website's layout and design.

## Prerequisites

To effectively follow this guide, you should have:
- A GitHub account, enabling you to host and manage your files on a distributed version control platform.
- An introductory level understanding of Markdown and Git, essential for creating and maintaining technical documents and code.
- Your resume formatted in Markdown, which allows for straightforward content creation and formatting.

## Instructions

### 1. Set Up Your GitHub Repository
1. **Visit GitHub**: Navigate to [GitHub](https://github.com) and log in.
2. **Create a New Repository**: Click the '+' icon in the top-right corner and select 'New repository'.
3. **Name Your Repository**: Type `<yourusername>.github.io` as the repository name, replacing `<yourusername>` with your actual GitHub username. Keep other options default.
4. **Create Repository**: Click the 'Create repository' button.

### 2. Prepare Your Resume
1. **Write Your Resume**: Open your favorite text editor, write your resume using Markdown, and save the file as `index.md`.
2. **Locate Your Resume**: Move or save your `index.md` file to a known location on your Mac for easy access.

### 3. Publish Your Resume
1. **Open Terminal**: Find the Terminal app in your Applications > Utilities folder and open it.
2. **Navigate to Your Resume**: Type `cd path/to/your/resume`, replacing `path/to/your/resume` with the actual path where your `index.md` is located, then press Enter.
3. **Initialize Git**: Type `git init` and press Enter to initialize a new Git repository.
4. **Connect to GitHub**: Type `git remote add origin https://github.com/<yourusername>/<yourusername>.github.io.git`, replace `<yourusername>` with your GitHub username, and press Enter.
5. **Add Your Resume**: Type `git add index.md` and press Enter to add your resume file to Git.
6. **Commit Your Changes**: Type `git commit -m "Publish my resume"` and press Enter to commit your resume file to your repository.
7. **Upload Your Resume**: Type `git push -u origin master` and press Enter to push your resume to GitHub Pages.

Your resume is now live and can be viewed at `https://<yourusername>.github.io`.



## More Resources

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/): A comprehensive guide to Markdown formatting.
- [Setting up a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll): Instructions for integrating Jekyll for more sophisticated site layouts.
- [Andrew Etter's Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS): Essential reading for understanding the principles behind modern documentation practices.
- [Markdown Guide - Basic Syntax](https://www.markdownguide.org/basic-syntax/): Basic syntax reference for Markdown formatting.

### Find my resume at "foreverbulking.github.io"

![ScreenRecording2024-03-05at5 20 19PM-ezgif com-video-to-gif-converter](https://github.com/foreverbulking/foreverbulking.github.io/assets/63769634/0310b37a-d7f1-4dfa-8be5-9c455b2f509a)

## Authors and Acknowledgements

- Nishan Sanyasi, for creating and maintaining the resume content and this guide.
- A special thanks to all the contributors to the Jekyll and GitHub Pages communities, whose templates and documentation have made this project possible.

## FAQs

**Q: Why is Markdown preferred over traditional word processors for technical documentation?**
A: Markdown's lightweight and readable format makes it easier to write, edit, and share documentation, especially within version control systems. Its simplicity and portability align with Andrew Etter's principles for efficient technical writing.

**Q: Why might my resume not appear immediately on my GitHub Page?**
A: After updating your repository, it can take a few minutes for GitHub Pages to process and publish the changes. Ensure your repository and file names are correct, and double-check your Git commands. If the problem persists, verify your GitHub Pages settings in the repository settings.

**Q: How do I update my resume once it's on GitHub Pages?**
A: Edit the `index.md` file with your updates, save it, then run `git add index.md`, `git commit -m "Update resume"`, and `git push origin master` in the Terminal. The changes will reflect on your GitHub Page shortly after.

**Q: What should I do if I get a 'permission denied' error when trying to push to GitHub?**
A: This usually happens if you haven't set up your SSH key or if your GitHub access token has expired. Check GitHub's documentation on setting up a new SSH key or updating your access token.

**Q: Can I add images or other media to my Markdown resume?**
A: Yes, you can! Markdown allows you to embed images using the syntax `![Alt text](URL_to_image)`. However, remember that your resume should be professional, so only add media that enhances your application.

**Q: How can I view my Markdown file before pushing it to GitHub?**
A: You can use a Markdown editor that has a preview feature, or install a Markdown preview extension in your text editor. This lets you see how your document will look before publishing it.

**Q: What if I want to use a different theme for my GitHub Pages site?**
A: GitHub Pages supports Jekyll themes, which you can specify in your repository settings. Browse the available themes in the 'Theme Chooser' section and select one that suits your resume style.

**Q: Why should I use Git commands in the terminal instead of a GUI tool?**
A: Using Git commands in the terminal helps you understand what each operation does and gives you more control. While GUI tools are convenient, terminal commands can offer more flexibility and a deeper understanding of Git.



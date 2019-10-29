# How to Host Your Resume Using GitHub Pages, Jekyll, and Markdown

Welcome to this guide on hosting your Resume online using GitHub Pages and Markdown. 

Sections in this guide:
1. [Audience](#audience)
2. [Getting Started](#getting-started)
3. [Prerequisites](#prerequisites)
4. [Instructions](#instructions)
    1. [Converting Your Resume](#converting-your-resume)
    2. [Adding Your Resume to GitHub](#adding-your-resume-to-github)
    3. [Customizing Your Page's Appearance](#customizing-your-pages-appearance)
5. [More Resources](#more-resources)
6. [Authors and Acknowledgment](#authors-and-acknowledgment)
7. [FAQs](#faqs)

---
## Audience  

This guide is intended for people who are new to using GitHub Pages, Jekyll, and Markdown. Experience with GitHub isn't required, but it will make the process of following the instructions easier. This guide will have you creating repositories and interacting with GitHub's website. 

---  
## Getting Started

Before getting to the instructions, I would recommend you read over some terminology to help your understanding. If you are familiar with these products or terms, feel free to skip ahead to Prerequisites.

### Markdown

Markdown is a markup language used to format text. It has become the most popular way to format READMEs and is widely used online.  

### Jekyll

Jekyll is a program that creates static webpages from text files formatted in markup languages like Markdown. You can customize the output appearance by applying different themes.

### GitHub

GitHub is a website that provides hosting for users' project repositories. GitHub provides users with the functionality to manage their projects using version control.

### GitHub Pages

GitHub Pages is a feature offered by GitHub. It provides users with the ability to freely host static webpages. GitHub Pages is fully integrated with Jekyll, meaning that the process of converting a Markdown file to a webpage is simple and straightforward.

---  
## Prerequisites

Here is what you will need before continuing:
1. An up-to-date resume.
2. A text editor of your choice. You should preferably use an editor that has Markdown preview functionality.
    *  Note:  This README was written on Visual Studio Code with the added extension GFM Preview. If you do not want to download any software, there are online Markdown editors like [Markdown Live Preview](https://markdownlivepreview.com/).
3. An account on GitHub. You can sign up for an account [here](www.github.com) if you do not have one.
    * Note: Be sure to select an appropriate username if you are creating an account, as it will be a part of your URL when you host your resume.

--- 
## Instructions

The goal of these instructions is to walk you through the steps of converting your resume into Markdown format and hosting it on GitHub. By the end, you will have a presentable resume you can share on the internet.

### Converting Your Resume  

The first section of these instructions will walk you through converting your existing resume into Markdown format.

1. Get the raw text from your resume.
    * Note: Depending on your resume's layout this may be a long process.
2. Copy your resume's raw text into your preferred editor.
3. Fix any spacing issues that occur previewing your Markdown.
    * Note: To write on a new line in Markdown you need to add two spaces at the end of the line or divide your lines with an empty line between them. Since they both provide different results, you can use them to space your resume out as desired. 
4. Create headers for the sections of the resume. You can do headers by adding `#` followed by a space and the header name. You can add one to six `#` symbols per header. The more `#` symbols you add, the smaller your header will become.  
    ```
    # Biggest Header
    ## Big Header
    ### Somewhat Big Header
    #### Somewhat Small Header
    ##### Small Header
    ###### Smallest Header
    ```
5. Create subheaders for the subsections of your resume by following the same process as the previous step. 
    * Note: Make sure to have your subheaders smaller than your headers.
    ```
    # Main Header
    ## Section Header
    ### Subsection Header
    ```
6. Add bullet points to areas in your resume that need them. You can do this by adding a `*` followed by a space and the text you want in the bullet. 
    ```
    * List Item 1
    * List Item 2
    * List Item 3
    ```
7. To create any nested lists, add a tab at the front of the bullet you are adding.
    ```
    * List Item 1
        * Inner List Item 1
        * Inner List Item 2
    * List Item 2
    * List Item 3
    ```

Result: You now have a resume formatted in Markdown.

If you are struggling with converting your resume to Markdown or want to do more than specified here, I recommend going through [this](https://www.markdowntutorial.com/) tutorial on Markdown. It only takes about 10 minutes to finish.

### Adding Your Resume to GitHub

Now that you have a properly formatted Markdown resume to work with, this section will cover the process of adding your resume to your GitHub account and setting it up on GitHub Pages.  

8. Log in to your GitHub account.  
9. Create a new repository by hitting the green button labeled "New".  
10. Enter the Repository name as "_`<yourusername>`_.github.io". 

![New Repository Screen](https://i.imgur.com/Wb3ms4b.png)

11. Leave the repository set to Public.  
12. Click the "Create repository" button.  
13. Click on the link on the Quick Setup that states "creating a new file".  
14. Name the new file "index.md".  

![Adding](https://i.imgur.com/GNxIngl.gif)

15. Copy and paste your Markdown-formatted resume into the text area.
    * Note: Later you will be adding your name in your theme's header. Do not copy and paste the header with your name from your Markdown-formatted resume.
16. Scroll to the bottom and click on the "Commit new file" button.  


Result: Your resume is now hosted on GitHub in a repository. A basic version of your resume is now accessible via https://_`<yourusername>`_.github.io/.

### Customizing Your Page's Appearance  

Finally, this section will cover some basic appearance settings to make your resume fit your style.

17. In your resume's repository, go to the Settings page.
18. Scroll to the GitHub Pages section of the settings. It should be listed near the bottom.

![Set Theme](https://i.imgur.com/NstQaKS.gif)

19. Click on the "Choose a theme" button.
20. Find a theme that you like.
21. Confirm your choice by hitting the "Select theme" button.
22. Go to the "Code" tab of your repository. There should now be a file listed in your repository named _config.yml.
23. Click on _config.yml to open it.
24. Click on the pencil icon to edit the _config.yml file.
25. Add your name as the title by adding "title: _`<Your full name>`_" on a new line.
26. Add a description under your name by adding "description: _`<Your description>`_" on a new line.

![Set Config File](https://i.imgur.com/LeyEGI2.gif)

26. Scroll to the bottom and click "Commit changes" to save the file.

Result: Your resume's webpage should be finished and ready to show off. You can access it via https://_`<yourusername>`_.github.io/.

---
## More Resources

If you are curious about learning more than what was covered here, feel free to read some of the following:

* [GitHub's Markdown Page](https://help.github.com/en/github/writing-on-github)
* [Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown Guide](https://www.markdownguide.org/)
* [Markdown Tutorial](https://www.markdowntutorial.com/)
* [Mike Dane's Jekyll Video Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

---
## Authors and Acknowledgment

Thank you to the following people who helped with editing:
* Daniel Gold  
* Zack Holmberg  

The theme used in my Resume was [Slate](https://markrobitaille.github.io/). Thank you to [all the contributors](https://github.com/pages-themes/slate/graphs/contributors) that worked on the theme.

---
## FAQs

### What do I do if my original resume has a complex layout?

> If your original resume has a complex layout, I recommend simplifying it before converting it to Markdown. Having your resume in a simple format that is grouped by headings will make it easier to convert to Markdown. It will also give you the opportunity to evaluate and update the content of your resume.

### Can I use a custom domain name for my resume's webpage?

> Yes, you can use a custom domain name for your resume's webpage. You will need to set the custom domain name in the GitHub Pages section of your resume's repository. Additionally, you'll need to change the settings on your domain name provider's website. For more details on how to accomplish this, [read this article](https://medium.com/@hossainkhan/using-custom-domain-for-github-pages-86b303d3918a).

### What do I do if I already have a website hosted on https://_`<myusername>`_.github.io?

> If your default GitHub Pages URL is already being used, you can name your branch whatever you prefer. For example, you could name the branch "Resume". In your "Resume" repository, go to the settings. In the GitHub Pages section, you can enable the webpage by changing the branch used from "None" to "Master branch". Now you can access your resume webpage via "https://_`<yourusername>`_.github.io/Resume".

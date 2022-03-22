# How Upload your Resume to GitHub

A practical guide on how to host and format a markdown resume on github, following the stpes laid out by Andrew Etter in his book Modern Technical Writting.

**Prerequisites:**  
1. Resume formatted in markdown.
2. Github account
3. Andrew Etter's book Modern Technical writting

### **Navigate and GitHub Homepage**  
Log-in to your GitHub account and navigate to the [GitHub](github.com) homepage.  

### **<ins>Creating a Repository</ins>**
1. On your GitHub homepage create a new repository by clicking 'New' under 'Recent Repositories' on the leftside of the page.
2. Set your repository name to be [GitHubUserName].io
    * ex. If your username is "example-name" then your Repository should be named "example-name.io"
3. Ensure that your repository is set to **Public**
4. Check the box lablled 'Add a README file'
    * This will auto generate an empty README.md file which will be used later.

### **<ins>Adding Files</ins>**

You will be adding 2 additional files for a total of 3 files (including your README.md)
* Your Resume
* A Configuration File


#### **Your Resume**
1. Create a new file by selecting **Create new file** under the **Add file** drop down.
2. Name this file **index.md**
3. Inside of index.md paste your **markdown formatted resume**
4. Write a description for your file commit
    * This is important for *Distributed Version Control* as highlighted in Etter's book.
5. Finally, Commit your file by pressing **Commit new file**.

#### **Configuration File**
1. Create another new file by selecting **Create new file** under the **Add file** drop down.
2. Name this file **_config.yml**
    * This will be a YAML file, which is commonly used configuration file
    * We will be using the basic jekyll theme 'slate' this can be changed later
3. Add these 2 lines to your file
```
theme: jekyll-theme-slate
title: Your Name 
```
5. Add a commit description 
6. Commit your file by pressing **Commit new file**


### **<ins>Navigate to your resume website</ins>**
Simply navigate to **'GitHubUserName.github.io'** where GitHubUserName is your GitHub username.  
Your resume formatted in **markdown** with the jekyll theme **slate** should appear with the title **Your Name**

![How to get to your resume website](https://i.imgur.com/5Wv492j.gif)

### **<ins>More Resources</ins>**
1. A useful [tutorial](https://agea.github.io/tutorial.md/) for GitHub flavoured Markdown.
2. [Andrew Etter's book Modern Technical Writting](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
3. A [tutorial](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages) for making static websites with jekyll and GitHub 

### **<ins>Authors and Acknowledgments</ins>**

Thanks to [Ben Balter](https://github.com/benbalter) and [contributors](https://github.com/pages-themes/slate/graphs/contributors) for their work on the jekyll slate theme


### **<ins>FAQ</ins>**

#### **1. Why is Markdown better than a word processor?**

Markdown is useful for fast and easy formatting without having to use your mouse. Unlike word processors such as word, which require you to change between typing and navigating, all that can be done in markdown without lifting your hands. 

#### **2. All I see is a GitHub page where is my resume?**

Ensure that you have navigated tot he appropriate web address. While looking at your repository click on the address bar (it should read *github.com/your-name/your-name.github.io*) and remove "*github.com/your-name/*" leaving only "*your-name.github.io*" which will be your static resume website



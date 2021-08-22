## Project Online Resume

### The goal of this project is to practice working with HTML and CSS.

**Basic functionality:** We will be creating a web page with your personal resume, with all relevant information and links, for example to your LinkedIn profile and GitHub account.

Below is an example of a resume webpage:

<img src="./examples/full_sample.png" width="500" />

To see the page in more detail, have a look in the `examples` folder. There are screenshots of the full resume page, and of the top and bottom parts separately.

---

### For starters

1. Create a new folder on your local computer with the name: personal-resume-website
1. Track your code with Git by using git init in the terminal
1. Create an index.html file with the general template code
1. Create a style.css file and add this to your HTML file as a <link>
1. Make sure you have **Resume *yourname*** as the title in the HTML (this will show in the tab when your app runs in the browser)
1. Build the page according to the example, and feel free to add styling or elements you prefer.
1. The example webpage uses Poppins sans serif as font: [Poppins website](https://www.1001fonts.com/poppins-font.html).
1. Use a professional photographs of yourself that gives a good impression of you
1. Use Flexbox or CSS Grid to work with layout 
1. Feel free to use Bootstrap if you also want to practise that 😊
1. For icons visit [Fontawesome](https://fontawesome.com/v4.7/icons/)
1. To access those icons use this [link](https://cdnjs.com/libraries/font-awesome). You can copy the CDN link and add this in your HTML header as a stylesheet. NB: your own `style.css` file is always the last stylesheet in the `head` section of your HTML!
1. A good resume is just one page long and recruiters look at the resume only for a few seconds, so make sure the layout is inviting, not too much text, and clear headers that summarise the information in the section

---

### For more advanced students

1. Use media queries to make the page responsive so that it can be read on
  * mobile phone
  * tablet
  * desktop
1. Deploy the webpage on Netlify or Heroku and check that the URL includes your name: it must be clear that it is *your* personal resume 😊

---

## Please note:
If you want to download a project on your local machine, do not fork it but clone the repo locally, on your computer. After that, create a new repo in your own GitHub account *with exactly the same project name*, and link the local repo to the remote repo in your GitHub account (see below). Why should you clone and not fork? It will show the project as **your own project** and not a fork of someone else's project. You can use it as a project for your portfolio.

You can connect a local project to a new, empty GitHub repo [as follows](https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line). We can do this together during a CodeWomen coding session: it is very good to know this so that you can start a project locally and afterwards link it with a remote GitHub repo.

If you clone the project without forking it, you will have to change the 'remote origin' repository after cloning. Check the remote of your local project using `git remote -v`. You will probably see:  
`origin  https://github.com/CodeWomen-Barcelona/some-codewomen-project.git (fetch)`  
`origin  https://github.com/CodeWomen-Barcelona/some-codewomen-project.git (push)`

To link your local project to your own GitHub repo, you need to change the remote origin. Have a look at this article: https://devconnected.com/how-to-change-git-remote-origin/. With `git remote -v` you can again check if remote origin has been reset and now shows the name of your GitHub account.

PS: if you work for a company that has a corporate social responsibility policy and wants to support women in tech, then here is the link to the [fundraising overview of MigraCode](https://docs.google.com/spreadsheets/d/1Zs-Mmi39bcjVw2U-iEQWSHSjkb-EmET-j1WB2oJF45Q/edit#gid=0).

---
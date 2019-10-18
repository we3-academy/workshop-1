# Workshop 1

Build and Deploy Your Portfolio Website with Gatsby & Netlify

➡️ **[See a live link](//we3academy-w1.netlify.com)**

## Worskhop Instructions
Download and Install Dependencies
1. Node LTS 64 bit (comes with npm)
https://nodejs.org/en/download/

Open a command prompt or terminal and enter `node -v`, to see the version of node you just installed. Also, run `npm -v` to ensure that npm was installed correctly

2. Git
https://git-scm.com/downloads
Download the git client 64bit. Make sure git bash is checked and included. When it promots select "Git from the command line and also from 3rd party software"

3. If you don't have an IDE installed, you can download and install VS Code:
https://code.visualstudio.com/download

4. Install gatsby-cli
On your command prompt, enter `npm install -g gatsby-cli`

5. Select a starter template
https://www.gatsbyjs.org/starters/?s=portfolio&v=2 

Some good examples: 
https://www.gatsbyjs.org/starters/LekoArts/gatsby-starter-portfolio-cara/
https://www.gatsbyjs.org/starters/EmaSuriano/gatsby-starter-mate/
https://www.gatsbyjs.org/starters/smakosh/gatsby-portfolio-dev/
https://www.gatsbyjs.org/starters/LekoArts/gatsby-starter-portfolio-bella/

Make sure to checkout the github page for them to read more about how to customize and set it up. 

If you want to read more about Gatsby: 
https://www.gatsbyjs.org/
https://www.gatsbyjs.org/docs/quick-start

6. Once you select the starter template that you like, go to your command prompt or terminal and navigate to the folder where you want to create the site. 

Here's a link for basic cmd commands
https://gist.github.com/jonlabelle/e8ba94cd29b8f63fd7dd3c4f95c1d210

Once in the folder, follow the instructions to clone the starter template. It should look like:
`gatsby new name-of-folder https://linkhere`
For example `gatsby new gatsby-starter-portfolio-cara https://github.com/LekoArts/gatsby-starter-portfolio-cara`

7. Cool, now that you have your site setup, you can make any modifications to the .md files to personalize and customize your site.

BREAK TIME

8. Create an account on github if you don't have one already
https://github.com

9. Create a new repository on git, you can call it the same name as your project folder for ease of reference.
https://github.com/new

Make sure you uncheck the initialize readme option. Otherwise we'll have merge conflicts when we push.

10. Open git bash on your laptop. Navigate to your project folder on it using `cd folder/project`. Once there you should see the branch name you're on. Run the following commands `git add .` 
`git commit -m 'init commit'`

Git cheatsheet: 
https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf

11. Adding a remote repository 
`git remote add origin linktoyourgithubrepo` 
Replace linktoyourgithubrepo to the actual link from your repository.

12. Push your code to git 
`git push -u origin master`

13. Netlify. Create an account on netlify
https://www.netlify.com/
14. Connect the github repository and push code to deploy

## Installation

### With [`gatsby-cli`](https://www.npmjs.com/package/gatsby-cli)

```bash
$ gatsby new my-slides https://github.com/fabe/gatsby-starter-deck
```

### With `git clone`

```bash
$ git clone git@github.com:fabe/gatsby-starter-deck.git my-slides
$ cd my-slides
$ yarn
```

## Usage

Edit and extend your slides inside the `src/slides.md` file. Navigate with the arrow keys.

```bash
# To develop & write
$ yarn develop

# To build
$ yarn build
```


## Authors

- Radha Satam ([@radhasatam](https://twitter.com/radhasatam))

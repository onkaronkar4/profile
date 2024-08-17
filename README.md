# mywebpage

[Video tutorial](https://youtu.be/YN75YXaLFGM)

This is a template for creating a Quarto web site using RStudio.

To use it effectively you need to know how to push and pull from GitHub to RStudio using the Git panel buttons, which requires a working GitHub personal access token (PAT). If you don't have one setup, following [these instructions](https://happygitwithr.com/https-pat.html#tldr) in *Happy Git and GitHub for the useR* to set one up. (In short you will create a token for HTTPS and store it using **gitcreds**.)

In addition open RStudio and update to the latest version by clicking "Help" "Check for Updates". (This is necessary to ensure that Quarto is installed.)



### Render the web site (RStudio)

- [ ] 1. If you haven't already, click "Help" "Check for Updates" to make sure you have the latest version of RStudio (and thus have Quarto installed.)

- [ ] 2. Render the web site locally by clicking the "Build" tap on the right and then "Render Website".

- [ ] 3. Use `browseURL("docs/index.html")` to view your site locally (or just open `docs/index.html` in a browser).

- [ ] 4. If it looks good, commit and push all changed files to GitHub. 

(You will need to repeat steps 2 and 4 every time you wish to update the book online.)

### Next steps

- Add content to `index.qmd` as desired.

- Add content to `projects.qmd` as desired.

- Change the photo in the `img` folder to your photo.

- Choose a theme from [https://bootswatch.com/](https://bootswatch.com/) and replace "cerulean" in `_quarto.yml` with your prefered theme.

- Add additional tabs/sections by creating new `.qmd` files and listing them in `_quarto.yml` under `projects.qmd`.

### Additional features

Please consult the official guide to **quarto** web sites: [https://quarto.org/docs/websites/](https://quarto.org/docs/websites/)

### Last but not least

Once you've completed these steps, delete the content of this **README** and add a short description of your project with a link to the book URL. It would be appreciated if you add the following to the end:	

*This repo was initially generated from a Quarto template available here: https://github.com/jtr13/website-template.*

(And starring the repo would be nice too!)


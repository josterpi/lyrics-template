# lyrics-template
This is a repository that can be used as a template for a Github Pages site
that generates a mobile lyrics page.

## Setup

### Create a repository from this template

1. You need a Github account.
2. In the upper right corner, select "Use this template" and Create a new repository.
3. For the repository name, use `<your username>.github.io`
4. Create repository.
5. [Set up Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
   - In the new repository, click Settings.
   - In the "Code and automation" section of the sidebar, click Pages.
   - Under "Build and deployment", under "Branch", select the main branch and Save.
  
### Initial setup

Open and edit `index.html`. There are a few variables at the top of the file which are used for the lyrics page.
Ignore the `layout` variable. `title` is used for the page title and main heading. The others are used if this
page is shared on facebook.

If you want to enable easy sharing with a QR code, [create a QR code](https://qrcode.tec-it.com/en/Url) for the final destination
of the lyrics page and put it in the repository in a file named `qr-code.png`.

### Enter songs in lyris folder

The `_lyrics` folder contains markdown files that contain song lyrics. There are three Christmas carols to begin
with that demonstrate how to format the lyrics, with some variations. Some comments:

 - The top section (between the `---`) contains a single variable, the title of the song.
 - The basic format is a numbered list.
 - In markdown, the line breaks between lines in a verse are entered by ending each line with two spaces.
 - Note that for *Go, Tell It On The Mountain* the starting chorus doesn't have a number.
 - For the remaining choruses, indent the first line with three spaces in order to keep it in the numbered list.

If you're familiar with Git, you can clone this repository and enter lyrics on your own computer. If not, Github
allows you to "Add file" in the `_lyrics` directory and when looking at a file, you can click on the pencil to edit the file.

### View the page

1. Click on Settings.
2. In the "Code and automation" section of the sidebar, click Pages.
3. Click "Visit site" at the top of this page.

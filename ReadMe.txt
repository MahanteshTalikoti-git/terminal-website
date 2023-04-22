Winbox JS
https://nextapps-de.github.io/winbox/

Winbox JS GitHub:
https://github.com/nextapps-de/winbox

mkdir terminal-website
cd .\terminal-website\
cd . > index.html
cd . > style.scss  (in scss folder)
cd . > style.css   (in css folder)	
code .\index.html

sass --watch scss/style.scss css/style.css  (in a separate terminal window)
[on successful compilation, always style.css.map will be generated]

Valuable short cut:
div.item*3{Item $}

GitHub Pages:
Note: make sure main html file is always called "index.html" and GitHub Repo shld be always public
After code push, Navigate to Settings - Pages.
Under Build and deployment, choose source as Deploy from a branch
Branch: master
Click on Save 

Below msg will be displayed:
Your GitHub Pages site is currently being built from the master branch.

Generated URL: https://mahanteshtalikoti-git.github.io/sass_crash_course/
# Tutorial for managing the Fresh Produce website!

A crash course on git commands and maybe HTML/CSS for any level programmer 

## Intro
0. Make Github account lol
1. Install git
2. Install a text editor (Sublime, VSCode, Atom, etc.)
3. If you're in mac, open up your regular terminal. If Windows, use powershell because I'm lazy and can't remember the different commands for Windows command prompt

## Some basic commands for the terminal 
- `cd <name of repo>` goes to that folder
- `ls` lists all folders in current directory
- `pwd` tells you your current working directory
- `.` single period means 'current directory'. So if you do `cd ./<name of file>` it will look for a file in your current directory
- `..` two periods mean to go up a directory. So `cd ../<name of file>` will look for a file in the directory a level above

## Some basic git commands 
- `git clone <link to project>` clones that project folder into your current directory
- `git add .` adds all the files in your current directory
- `git commit -m '<write commit message>'` makes commit with a custom message. Double check your file changes too
- `git push` pushes your changes to remote thingie on Github
- `git pull` pulls latest version and changes from remote project stuff
- There's also this thing called branches but again I am lazy and usually don't make too many drastic changes...basically you can make different versions of your code on different 'branches' so that you can work on different features without risking messing up the master branch. This is really helpful for group projects if you want to split up the work or code different things, but since it's usually just one person making minor changes then you can look into it later if you're interested ^_^
- `git revert <commit reference>` is kind of like an undo button in case you want to revert changes but you also need to know which commit you want to revert to
- For more git commands the websites I linked at the bottom should be more in depth

## When making changes
- If you want to see changes on the site just on your own laptop, open the index.html file in Chrome so that the URL should be something like 'file:///Users/christinesun/GitHub/freshproductionsucla/index.html'. When making changes, be sure to save it each time and refresh the page again to see changes reflected. 
- Another helpful thing is the Inspect Element button! If you're not sure if the CSS will actually change the right thing, then you can change the HTML/CSS directly in the browser. Here's a neat cheat sheet on that: https://appletree.or.kr/quick_reference_cards/Web_Browsers/chrome-developer-tools-cheatsheet.pdf
- If you want that change to go onto the actual site, then do 
1. `git add .`
2. `git commit -m '<some comment message>'`
3. `git push`
- and then refresh freshproductions.art to see if the changes take effect (sometimes there might be a lag)
- Usually there shouldn't be any merge conflicts if there aren't multiple versions

## Useful websites for HTML/CSS
- https://www.codecademy.com/
- https://www.w3schools.com
- https://www.toptal.com/front-end/what-is-bootstrap-a-short-tutorial-on-the-what-why-and-how

## Useful site for git
- http://guides.beanstalkapp.com/version-control/common-git-commands.html
- https://git-scm.com/docs

## Useful site for all questions related to CS
- https://stackoverflow.com/
# js

## Setup
In your terminal, copy paste the code below to clone this repository and turn off `git` so that it's simply a copy of the folder structure in your IDE. You will NOT be able to push.
```bash
git clone git@github.com:hstatsep/js.git
cd js
rm -rf .git
echo "Done"

```

## Files/Folders
* `classwork` is a folder for organizing classwork, assignments, etc.
* `projects` is a folder for your when you want to make something large
* `sandbox` is a folder for when you want to try something small
* `templateFile.html` is a standalone template file to duplicate in order to practice small concepts
  * to duplicate, use either:
    * `cp templateFile.html sandbox/newFileName.html`
    * `cp templateFile.html classwork/newFileName.html`
* `templateFolder` is a template folder to duplicate in order to make large projects
  * to duplicate, use `cp -r templateFolder projects/newProjectName`

## Console
* In order to see errors and results of `console.log()`, first preview the HTML file.
* Then, you can do one of the following:
  * keyboard shortcut:
    * Mac: <kbd>Command</kbd> + <kbd>Option</kbd> + J
    * Windows/Chromebook: <kbd>Control</kbd> + <kbd>Shift</kbd> + J
  * right-click > inspect > switch to **console** tab
  * three-dots in the top-right corner > More tools > Developer Tools > **console** tab
* More information [here](https://developers.google.com/web/tools/chrome-devtools/console/javascript)

## Git alias commands
* Copy/paste the following into the terminal.
```
echo "alias gp=\"git add ." >> ~/.bash_profile
echo "git commit -m 'update repo'" >> ~/.bash_profile
echo "git push\"" >> ~/.bash_profile
echo

```
* If you still see the last command in your terminal, press <kbd>ENTER</kbd>
* Close the terminal and open a new one
* In the future, you can simply type `gp` to automatically add/commit/push all updated files in a repo
* You can continue to use `git add filename` if you would like to be more selective, and/or `git commit -m "message"` if you would like to be more specific


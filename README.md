# Task Manager

A simple task manager web page built with HTML and CSS.

## Features
- Display a list of tasks
- Show completed tasks with a clear visual style
- Easy to open locally in a browser

## Project files
- index.html � page structure
- styles.css � styling for the task list and completed tasks

## How to open it
1. Open the project folder in your browser or file explorer.
2. Double-click index.html, or open it in a browser using the "Open with" option.
3. You can also use a local web server if you want, for example:
   `python -m http.server 8000`
4. Then visit http://localhost:8000 in your browser.

## Git status
This project is set up as a Git repository and the main branch contains the merged feature work.

## Merge conflict note
A merge conflict happened because both the change-title-1 and change-title-2 branches modified the same line in index.html, specifically the h1 title. Git could not decide which change to keep automatically because both edits were on the same text block.

To resolve it, I removed the conflict markers (<<<<<<<, =======, >>>>>>>), kept a single final title, and then staged the file with git add, committed the merge, and pushed the result to GitHub.

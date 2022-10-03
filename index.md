# lqch's notes from Git, Github and Gitkraken

3-4 October 2022 

Notes from the course are on the [website](https://srse-git-github-zero2hero.netlify.app)

## About using git and github
Organising work of your own and with others

- Git allows you to save your work at important points in time
- Github is for sharing work
- Gitkraken is GUI for git

## Structure of github repository
- readme.md (markdown)
- license (markdown)
- contributing.md guidelines for contributors so that they know what they should do if they want to help out (markdown)
- code of conduct (markdown)
- issues use github issues to record and discuss tasks

To sync remote with local is push, 
to sync local with remote is pull

## Committing
Commit changes to have git create a snapshot of the file at its current stage
-Add file to staging area
-add informative commit notes
-commit to repository

In gitkraken create repo with Ctrl-I and open file with Ctrl-P
Once commit on local:
Local branch would be ahead of remote origin

Conflicts arise when changes are not committed in local and you are trying to pull

## Git tips
	1. Commit early and often
	2. Commit logical bits of work together
	3. Write meaningful commit messages
In case of fire, git commit push and leave building

If Rmarkdown in Rstudio, Rstudio supports git and github

## Websites with github pages
Markdown provides formatting on github

### Formatting 
**bold**
__italic__
~~strikethrough~~
>Quoted text

# Heading 1
## Heading 2
### Heading 3

```
code blocks
```
Inline `code`

Unordered list
	- unordered
	- bullet
	- points
	
Numbered list
	1. hello
	2. it's me

Website
[Link to another page](the url)

Adding images
!{}(link to image)

More in github's formatting guide

index.md is the default webpage

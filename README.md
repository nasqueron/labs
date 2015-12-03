# Nasqueron Labs
Labs space to test applications, demos, temporary content.

It's live at http://labs.nasqueron.org/.

## Building process

First, the site is bootstraped with the public/ content. It's where the homepage coul be customize.

Then, it creates subdirectories cloning static content repositories following the instruction of `conf/deploy.json`.

## To add a subdirectory from a Git repository

Add a new entry to the `conf/deploy.json` file:

```
{
	"name": "awesome-app",
	"repo": "https://github.com/awesomeness/awesome-app"
}
```

# Quick Setup Notes Hugo Web Site

## Set Up New Site

hugo new site .\ --force

Congratulations! Your new Hugo site is created in C:\_Repos\GitHub-JanVidarElven\BorgenGutta.github.io.

Just a few more steps and you're ready to go:

1. Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/ or
   create your own with the "hugo new theme <THEMENAME>" command.
2. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>\<FILENAME>.<FORMAT>".
3. Start the built-in live server via "hugo server".

Visit https://gohugo.io/ for quickstart guide and full documentation.

## Get Selected Theme as Submodule

Customize to refer Github User and Repo as Theme Source:

git submodule add https://github.com/halogenica/beautifulhugo .\themes\beautifulhugo

## Copy config.toml

Copy the contents of the config.toml file from the theme exampleSite to root, and customize to your own values and preference.

## Copy archetypes

Copy archetypes from theme and replace archetypes at root. 

## New content file

hugo new borgengutta.github.io\index.md

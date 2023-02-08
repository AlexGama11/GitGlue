<p align="center"><img src=".readme/logo.svg">
  <br><br>
<img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg">

# Overview 
Do you want to showcase a github repository or profile on your website? Instead of leaving a simple link, use this tool to create embedded HTML github tiles. It uses GitHub's API to grab the information, so no need to worry about updating html. You can pin profiles, single repositories, or even all repositories linked to an individual profile! The only difference between my project, and the original or other forks, is that I made mine incorporate github's dark mode colour scheme.

## Usage
Simply iframe this code and set the html **data** field with a GitHub profile, repository, or repositories tab url.
```html
<link rel="stylesheet" href="https://alexgama11.github.io/GitGlue/css/gitstyle.css">

<script src="https://alexgama11.github.io/GitGlue/GitHubPinner.js"></script>
<div data="https://github.com/SOMERANDOMUSER?tab=repositories" class="github-pinner" style="visibility: hidden;"></div>
```

## Preview
<p align="left"><img src=".readme/profile-example.png" width="550px"><br>
<img src=".readme/repo-example.png" width="1000px"></p>

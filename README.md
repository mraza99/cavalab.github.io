# Cava lab website

This is the code for the https://cavalab.org website. 

# How to add yourself

1. Fork this repo and make a new branch.
2. Add a **square** profile picture **less than 200 KB** to `assets/images/` named something like `last-name-first-name.png`.
3. Make a new file named `last-name-first-name.md` in the `_members` folder with a header and bio following [this example](https://raw.githubusercontent.com/cavalab/cavalab.github.io/gh-pages/_members/01_lacava-william.md)
4. edit `_data/authors.yml` to add an entry for yourself, for example:

```yaml
bill:
  name: "My Name, PhD"
  avatar: "assets/images/last-name-first-name.png"
  bio: "Postdoctoral Fellow"
  links:
    - label: "Email"
      icon: "fas fa-fw fa-envelope"
      url: "mailto:my.email@childrens.harvard.edu"
    - label: Website
      icon: &personal "fas fa-user"
      url: "http://personal-website.com"
    - label: Google Scholar
      icon: &scholar "fas fa-graduation-cap"
      url: "https://scholar.google.com/citations?user=me&hl=en"
    - label: Github
      icon: &github "fab fa-fw fa-github"
      url: "https://github.com/me"
    - label: Twitter
      icon: &twitter "fab fa-twitter"
      url: "https://www.twitter.com/me"
    - label: LinkedIn
      icon: &linkedin "fab fa-linkedin" 
      url: "https://www.linkedin.com/in/me/"
```

For the links, you just have to change the `url` field. 
You can also remove any you don't want. 

5. Commit your changes, push to your fork, and [open a PR on this repo](https://github.com/cavalab/cavalab.github.io/compare).

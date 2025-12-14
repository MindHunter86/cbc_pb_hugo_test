# HOWTO: You first blog

## Step - by - step
1. Fork me!
2. Go to github.com/yourname/yourrepo/`actions` -> Press button "I Understand"
3. Go to settings -> Pages -> Source -> Github Actions
4. Make changes in configs wrote below
5. Go to github.com/yourname/yourrepo/`actions` -> check you last `run`
6. In last run or in main page of your repo (in aside block) find link to you new blog
7. OR go to `yourname`.github.com/`yourrepo`/

## Configs
### Must have changes after forking
#### hugo.yaml
```
baseURL: https://mindhunter86.github.io/cbc_pb_hugo_test/
title: My First Blog
copyright: Darth Vader

params:
  headline:  My First Blog in WWW
  description: Today we learn how to create your first blog in the Internet
  github: "https://github.com/"
  email: "superdeveloper@example.com"
```

### New post copy-paste header
```
+++
title = "Here are some update of my life"
description = "I've seen smth amazing and it changed my life."
date = 2015-12-14T11:11:11Z
author = "Me"
+++
```

# Useful links
- GitHub Education :
  - https://github.com/education
  - https://education.github.com/pack
- HUGO documentation :
  - Your first steps with HUGO (quick start) :
    - https://gohugo.io/getting-started/quick-start/
  - How to deploy to GitHub :
    - https://gohugo.io/host-and-deploy/host-on-github-pages/
  - Your post's content format (Markdown, HTML, ...) :
    - https://gohugo.io/content-management/formats/
- Lesson's theme documntation :
  - https://github.com/jbub/ghostwriter
- Step-by-step manual for blog creation :
  - https://www.freecodecamp.org/news/your-first-hugo-blog-a-practical-guide/
- Some blog examples :
  - https://hugo-coder.netlify.app/posts/markdown-syntax/
  - https://adityatelange.github.io/hugo-PaperMod/
- HUGO themes :
  - https://themes.gohugo.io/tags/blog/

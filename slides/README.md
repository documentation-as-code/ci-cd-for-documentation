---
marp: true
theme: default
style: |
  header {
    position: absolute;
    left: 50%;
    top: 33px;
  }
  section header a { color: white;}
paginate: true
header: '[🐤 @ojacques2](https://twitter.com/ojacques2) & laurent.gil@dxc.com'
---

<!--backgroundImage: url('https://github.com/documentation-as-code/ci-cd-for-documentation/raw/main/slides/title.jpg')-->
<br/>
<br/>
<br/>
<br/>

## CI and CD for documentation
...in 2020

---
<!--backgroundImage: url('https://github.com/documentation-as-code/ci-cd-for-documentation/raw/main/slides/simple.jpg')-->

Our story and how we solved our problems

# 🏰🦄🤴👸🐴👻⚔

---
# Why CI and CD for documentation?

* Documentation next to the code
* Hyper fast browsing (static web sites / no database)
* Test / lint your doc
* Open / Inner source documentation
  * Decrease effort
  * Battle test your documentation

---

# 🤯
Microsoft uses "Documentation as code" (and many others)

---

# Result
(mkdocs)

![bg center 60%](https://github.com/documentation-as-code/ci-cd-for-documentation/raw/main/slides/doc-site.jpg)

---
![bg right 90%](https://github.com/documentation-as-code/ci-cd-for-documentation/raw/main/slides/vscode.jpg)
# Authoring

This is (mostly) markdown:
Use your favorite code editor.

---

![bg left 90%](https://github.com/hediet/vscode-drawio/raw/master/docs/drawio-png.gif)
# Authoring (1)

## Pimp your editor with extensions

* [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) (for syntax)
* [Draw.io](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) (for drawings)
* [PlantUML](https://github.com/qjebbs/vscode-plantuml) (for diagrams as code)
* [Marp](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) (for slides)

---
![bg right 90%](https://github.com/documentation-as-code/ci-cd-for-documentation/raw/main/slides/codespaces.jpg)

# Authoring (2)

## GitHub CodeSpaces or GitPod

* Edit directly from the browser
* Make it easy for tech writers:
  no `git clone/branch/push`
  `git reset origin/main --hard`

---
# Authoring (3)

## Pick a tool

* [Jekyll](https://jekyllrb.com/) 🤐
* [MkDocs](https://www.mkdocs.org/) + [material theme](https://squidfunk.github.io/mkdocs-material/): closest to plain markdown, great for tech docs
* [Hugo](https://gohugo.io/): powerful, blazing fast
* [Marp](https://marp.app/): slides as code, mostly markdown

---
# Orchestrating

* GitHub Actions
* GitLab CI
* Jenkins (`Jenkinsfile`)
* AWS code pipeline
* Azure DevOps

---
# CI: Testing (1)

## Linter

- [github super-linter](https://github.com/github/super-linter)


## Spelling

- [spellcheck-github-actions](https://github.com/rojopolis/spellcheck-github-actions)

---
# CI: Testing (2)

## 404 links

[markdown-link-check](https://github.com/tcort/markdown-link-check)

---
# CI: Testing (3)

## Style / voice

[Vale](https://github.com/errata-ai/vale)

---
# Publishing (CD)

## GIT Hosting
GitHub, GitLab, Bickbucket

## Web hosting
[GitHub pages](https://pages.github.com/), [GitLab pages](https://docs.gitlab.com/ee/user/project/pages/), [Netlify](https://www.netlify.com/), an AWS S3 bucket, ...

---

# Thank you! 🙏

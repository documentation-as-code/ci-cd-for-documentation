---
marp: true
theme: default
paginate: true
footer: '[🐤 @ojacques2](https://twitter.com/ojacques2) & laurent.gil@dxc.com'
header: 'All Day DevOps 2020'
---

<style>
header {
  position: absolute;
  left: 100px;
}
footer {
  position: absolute;
  left: 900px;
  height: 35px;
}
</style>

<!--backgroundImage: url('https://github.com/angegar/addo-daac/raw/main/slides/title.jpg')-->
# CI and CD for documentation
# ...in 2020

---
<!--backgroundImage: url('https://github.com/angegar/addo-daac/raw/main/slides/simple.jpg')-->
# Why CI and CD for documentation ?

* Documentation next to the code
  * Link code version and documentation version
* Hyper fast browsing (static web sites / no database)
* Test / lint your doc
* Open / Inner source documentation
  * Decrease support team workload
  * Battle test your documentation

---

# 🤯
Microsoft uses "Documentation as code" (and many others)

---

# Result
(mkdocs)

![bg center 60%](https://github.com/angegar/addo-daac/raw/main/slides/doc-site.jpg)

---
![bg right 90%](https://github.com/angegar/addo-daac/raw/main/slides/vscode.jpg)
# Authoring

This is (mostly) markdown:
Use your favorite code editor.

---

![bg left 90%](https://github.com/hediet/vscode-drawio/raw/master/docs/drawio-png.gif)
# Authoring

## Pimp your editor with extensions

* [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) (for syntax)
* [Draw.io](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) (for drawings)
* [PlantUML](https://github.com/qjebbs/vscode-plantuml) (for diagrams as code)
* [Marp](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) (for slides)

---
![bg right 90%](https://github.com/angegar/addo-daac/raw/main/slides/codespaces.jpg)

# Authoring

## GitHub CodeSpaces or GitPod

* Edit directly from the browser
* Make it easy for tech writers:
  no `git clone/branch/push`
  `git reset origin/main --hard`

---
# Authoring

## Pick a tool

* [jekyll](https://jekyllrb.com/) 🤐
* [mkdocs](https://www.mkdocs.org/) + [material theme](https://squidfunk.github.io/mkdocs-material/): closest to plain markdown, great for tech docs
* [hugo](https://gohugo.io/): powerful, blazing fast
* [marp](https://marp.app/): slides as code, mostly markdown

---
# Hosting

## GIT Hosting
GitHub, GitLab, Bickbucket

## Web hosting
[GitHub pages](https://pages.github.com/), [GitLab pages](https://docs.gitlab.com/ee/user/project/pages/), [Netlify](https://www.netlify.com/), an AWS S3 bucket, ...

---
# Orchestrating

* GitHub Actions
* GitLab CI
* Jenkins (`Jenkinsfile`)
* AWS code pipeline
* Azure DevOps

---
# Testing (CI)

## Spelling

## Lint
- [GitHub super-linter](https://github.com/github/super-linter)
---
# Testing (CI)

## 404 links

---
# Testing (CI)

## Style / voice

---
# Publishing (CD)

---

# Thank you! 🙏
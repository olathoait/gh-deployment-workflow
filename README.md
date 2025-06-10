# gh-deployment-workflow
# GitHub Pages Deployment
Write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.

The goal of this project is to help you learn the notion of continuous integration and continuous deployment. You will write a simple GitHub Actions workflow to deploy a static website to GitHub Pages.

# Requirements
You are required to write a GitHub action that deploys any changes made to the index.html file to GitHub Pages. It should only deploy the file when the index.html file is changed.

Here are the steps to get you started:

- Create a GitHub repository for the project called gh-deployment-workflow for example.
- Repository should contain a simple index.html file saying “Hello, GitHub Actions!”
- It should also have a README.md file explaining the project.
- There should also be a deploy.yml file in the .github/workflows directory which contains the GitHub Actions workflow to deploy the website to GitHub Pages.
- Every push to the main branch that changes the index.html file should trigger the workflow to run and deploy the website to GitHub Pages.
- Website and any changes you make should be accessible at the GitHub pages URL for the repository e.g. https://<username>.github.io/gh-deployment-workflow/.

Stretch goal: You can also make this project more practical e.g. use some sort of a static site generator such as Hugo, Jekyll, Astro or similar generator to create a more complex website e.g. your own personal portfolio.
# 
After finishing this project, you will have a good understanding of the following concepts:

- GitHub Actions
- GitHub Pages
- Continuous Integration and Continuous Deployment
- Writing GitHub Actions workflows

Continue solving more projects for advanced CI/CD concepts.

```
@olathoait ➜ /workspaces/gh-deployment-workflow (main) $ git add index.html 
@olathoait ➜ /workspaces/gh-deployment-workflow (main) $ git commit -m "Add index.html with greeting message"
[main 96c2e65] Add index.html with greeting message
 1 file changed, 11 insertions(+)
 create mode 100644 index.html
@olathoait ➜ /workspaces/gh-deployment-workflow (main) $ git push orgin main
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
@olathoait ➜ /workspaces/gh-deployment-workflow (main) $ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 486 bytes | 486.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/olathoait/gh-deployment-workflow
   c7717b3..96c2e65  main -> main
```


# Configuring a publishing source for your github pages site

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

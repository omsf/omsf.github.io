# OMSF
OMSF website source code. 

## Adding a new project

1. Add a Markdown file to `content/programs/projects/`:

   ```markdown
   ---
   title: "Project name"
   image: "/images/project/project-name.svg"
   intro: "A short description shown on the projects page."
   more: true
   ---

   ## Project name

   Add the full project description and links here.
   ```

2. Add the project logo to `static/images/project/`. If the project has no logo, omit `image` from the front matter.
3. Preview the site with `pixi run hugo server`, then open a pull request.

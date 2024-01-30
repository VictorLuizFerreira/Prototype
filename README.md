# Prototype
Some api prototype using Vite, TypeScript, Shadcn/ui, Prisma, etc

## Steps

1. Create the repository on GitHub and clone it locally -> On VSCode use the key `control + q` on Mac and go to "Source Control",
do the Git Clone and paste the repository link; Every change you make you can do the commit and push to the repository.
Link of the documentation: https://learn.microsoft.com/en-us/azure/developer/javascript/how-to/with-visual-studio-code/clone-github-repository?tabs=activity-bar

2. Create a Vite project -> On VSCode use the key `control + q` on Mac and go to "Terminal", do the command `npm create vite@latest`; To chose: y, project-name, React, Typescript.
Link of the documentation: https://vitejs.dev/guide/#scaffolding-your-first-vite-project

3. Install the dependencies -> Enter on the project using `cd project-name` and use `npm install`.

4. Remove some files -> Remove: `README.md`, on `index.html` remove the line `<link rel="icon" href="/favicon.ico" />` and on `title` pull your project name, remove the `.eslintrc.js`, the folder `assets`, the `.css` files, take off the importations on `main.ts` and `App.tsx`.

5. Run the application -> `npm run dev`.
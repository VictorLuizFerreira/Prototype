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

6. Install the Shadcn/ui -> Install `tailwindcss`, `postcss`, `autoprefixer` using `npm install -D tailwindcss postcss autoprefixer` and do the init using `npx tailwindcss init -p`; On my `tsconfig.json` i put the config of the documentation inside the `compilerOptions`; Install the package in the documentation `npm i -D @types/node`; Update my `vite.config.ts` like in the documentation; Run the init command `npx shadcn-ui@latest init`; To chose: Yes, New York, Slate, src/global.css, Yes, No,
tailwind.config.js, @/components, @/lib/utils, No, Yes.
Link of the documentation: https://ui.shadcn.com/docs/installation/vite; https://tailwindcss.com/docs/customizing-colors

7. Install the Components -> Choose the components you want to use and install them using `npx shadcn-ui@latest add name-component`; You can install multiple components in one line, just separate them with a space.

8. Use the Components -> Import the components you want to use on your `App.tsx` and use them.

9. Import Lucid Icons -> Install lucid-react using the command `npm install lucide-react`; Import the icons you want to use on your `App.tsx` and use them.
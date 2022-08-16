# Angular Portfolio
Portfolio using Angular frontend framework and Materialize

### Deploying Angular Projects to GitHub (Method 1)
1. Create new empty repository
2. Create production build with `ng build --prod`
3. Check index.html and adjust base href to be like this: `<base href="/project-name/">`
4. Navigate to dist/project-name. Make a copy of index.html and rename it to 404.html. If you have a router in your Angular application, it not be available on GitHub pages and you'll get a 404 page. This is solved by telling the server what needs to be done when a page is not found.
5. git init to initialize git repo
6. git remote add origin <repository-url>
6. push changes to repository

### Deploying Angular Projects to GitHub (Method 2)
1. Go to angular.json and change the outputPath to "docs"
2. ng build --output-path docs --base-href angular-portfolio-v10



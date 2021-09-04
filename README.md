# Angular deployment instructions
## prereq: npm i -g angular-cli-ghpages

### Proceedure
1. cd my-app
2. ng build --base-href "https://efwoods.github.io"
3. ngh --dir dist/my-app
4. git checkout gh-pages
5. git commit -m 'deploy' --allow-empty
6. git push
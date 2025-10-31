mkdir express-sqlite-lab && cd express-sqlite-lab
npm init -y
git init
echo "console.log('Hello, Express + SQLite!')" > index.js
git add .
git commit -m "chore: init Node project with index.js"
npm i express better-sqlite3 morgan dotenv
npm i -D nodemon
git branch -M main
git remote add origin https://github.com/codeingn00b/Git-node-modules.git
git push -u origin main
# Create .gitignore manually 
# write in
node_modules/
.env
dist/
coverage/
.DS_Store
git rm -r --cached node_modules
git add .gitignore
git commit -m "fix: remove node_modules from tracking and add .gitignore"
git push
git check-ignore -v node_modules

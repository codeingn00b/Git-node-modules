mkdir express-sqlite-lab && cd express-sqlite-lab
npm init -y
git init
echo "console.log('Hello, Express + SQLite!')" > index.js
git add .
git commit -m "chore: init Node project with index.js"
npm i express better-sqlite3 morgan dotenv

# Dev tool (optional but recommended)
npm i -D nodemon
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/express-sqlite-lab.git
git push -u origin main

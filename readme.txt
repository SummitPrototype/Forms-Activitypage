Nieuw project in Git:
-Maak nieuwe github-repo op https://github.com/new 
	naampje
	.gitignore: GEEN! Zit al in het template
	License: MIT License
-clone with SSH: copy de link
-git clone <link>
-Wijzig base-route in nuxt.config.js in het huidige project
-npm install
-npm run dev


Bestaand project in Git: https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
-Maak nieuwe github-repo op https://github.com/new 
	naampje
	.gitignore: GEEN!
	License: GEEN!
-in Git Bash:
	-git init
	-git add .
	-git commit -m "initialize"
-Kopieer de SSH-link vanuit github-repo
-git remote add origin <repoLink>
-git remote -v
-git push origin master
-Wijzig base-route in nuxt.config.js in het huidige project
-npm install
-npm run dev

om te pushen naar githubPages: 
-npm run generate
-git add .
-git commit -m "generate docs"
-git push --set-upstream origin master
-in Repo-settings in Github GitHub Pages --> Source --> master brache /docs folder --> Save

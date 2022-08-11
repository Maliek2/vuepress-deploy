# vuepress-deploy


echo "# vuepress-deploy" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Maliek2/vuepress-deploy.git
git push -u origin main

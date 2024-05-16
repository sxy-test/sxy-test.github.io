# CreativityClassExp.github.io
ExpTest! Study Hard! Good morning!

git rm -rf .
bundle exec jekyll build
cp -r _site/* .
git add .
git commit -m "Deploy Jekyll site"
git push origin gh-pages

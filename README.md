# yzthewind.github.io
blog

cd my_website

rm -rf public

hugo  --theme=loveIt --baseUrl="https://yzthewind.github.io" --buildDrafts

cd ..

cp -r my_website/public/* ./

git add .

git commit -m "update article, :tada:"

git push

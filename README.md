rm -rf .next
rm -rf ./out 

pnpm run export 


cd ./out

git init 
git add .
git commit -m 'init'


git remote add origin https://github.com/xxx/xxx.git

git push -u origin master

cd -

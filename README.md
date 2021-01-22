# Use git
mkdir git
cd git
mkdir jx
cd jx
git init
vi README.md
git add README.md
git commit -m "add new file"
git status
git remote add origin https://github.com/yujishimizu0123/jx.git
git push origin master

# Split command 80M
split -b 80000000 file.zip
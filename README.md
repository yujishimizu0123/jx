# Use git
mkdir git<br>
cd git<br>
mkdir jx<br>
cd jx<br>
git init<br>
git remote add origin https://github.com/yujishimizu0123/jx.git<br>
<br>
# add git
vi README.md<br>
git add README.md<br>
git commit -m "add new file"<br>
git status<br>
git push origin master<br>
<br>
# Split command 80M
split -b 80000000 file.zip file.zip.<br>
<br>
# get data
git clone https://github.com/yujishimizu0123/jx.git
<br>
# Combine
cat file.zip.a* >> file.zip
<br>
# rm git
git rm README.md<br>
git commit -m "rm file"<br>
git status<br>
git push origin master<br>
<br>
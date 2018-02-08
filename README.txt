#Added this to test
echo "# test" >> README.mdi
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/azeemhashmani/test.git
git push -u origin master

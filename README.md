# Команды **Git**:

```
touch test.txt
mkdir dir

rm test.txt
rmdir dir

rm - r dir

cd ~
cd ..
cd .

ls
ls -a
ls -la

cp test.txt ~
cp -r dir ~

mv dir ~

cat test.txt
```
----
# Команды для локального и удаленного репозитория:

* Локальные:

```
git init
rm -r ./.git

git status

git add .
git add file.txt

git commit -m "My first commit!"

git log

```

* Удаленные:

```
git remote add origin <ССЫЛКА_SSH_РЕПОЗИТОРИЯ>
git remote -v

git clone <ССЫЛКА_SSH_РЕПОЗИТОРИЯ>

git push -u origin main 
git push
```
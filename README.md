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
----
# Компиляция в байт-код и работа с JAR файлами

## * Это компиляция класс(а-ов) в байт-код
```
javac -encoding UTF-8 <ИМЯ_КЛАССА>

javac -d bin -encoding UTF-8 *.java
```
## * Это запуск скомпилированного файл(а-ов) с байт-кодом
```
java -Dfile.encoding=UTF-8 <ИМЯ_ФАЦЛА_БЕЗ_РАСШИРЕНИЯ>

java -cp bin Practicum
```

## * Компановка в JAR
```
jar cfe <ИМЯ_СОЗДАВАЕМОГО_JAR>.jar <ИМЯ_КЛАССА_С_МЕТОДОМ_main> -C <СПИСОК_ФАЙЛОВ(bin)> .
```

## * Запуск JAR
```
java -jar <ИМЯ_JAR_АРХИВА>.jar
```
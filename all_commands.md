### 1.creating and renaming files and directory
```sh
mkdir test_dir
cd test_dir
touch example.txt
ls -l
mv example.txt renamed_example.txt
ls -l
```
mkdir -> to create a directory <br>
cd -> change the directory <br>
touch -> create a empty file <br>
mv -> rename or move file/directory <br>
ls -l -> long list <br>

### 2.viewing file contents
```sh
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```
cat -> display the content of a file <br>
head -n 5 -> display the top 5 lines of a file <br> 
tail -n 5 -> display the bottom 5 lines of a file <br>

### 3.searching for pattern
```sh
grep "root" /etc/passwd
```
grep -> search the pattern <br>

### 4.zipping and unzipping
```sh
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir
```
zip -r -> make the folder recursivly compress <br> 
unzip -> decompress <br>

### 5.downloading files
```sh
wget https://github.com/VinitKulkarni/gitPractice
```
wget -> download the content from the link <br>

### 6.changing permissions
```sh
touch secure.txt
ls -l
chmod 400 secure.txt
ls -l
```
chmod -> change mode(file/directory permission change) <br>
400 -> 4=read 0=None 0=None <br>

### 7.working with environment variables
```sh
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```
export -> to set the value to env variable <br>
echo -> to print value <br>

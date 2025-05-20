### 1.creating and renaming files and directory
mkdir -> to create a directory, cd -> change the directory, touch -> create a empty file, mv -> rename or move file/directory, ls -l -> long list
```sh
mkdir test_dir
cd test_dir
touch example.txt
ls -l
mv example.txt renamed_example.txt
ls -l
```

### 2.viewing file contents
cat -> display the content. head -n 5 -> display the top 5 lines, tail -n 5 -> display the bottom 5 lines
```sh
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

### 3.searching for pattern
grep -> search the pattern
```sh
grep "root" /etc/passwd
```

### 4.zipping and unzipping
zip -r -> make the folder recursivly compress, unzip -> decompress
```sh
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -d unzipped_dir
```

### 5.downloading files
wget -> download the content from the link
```sh
wget https://github.com/VinitKulkarni/gitPractice
```

### 6.changing permissions
chmod -> change mode(file/directory permission change), 400 -> 4=read 0=None 0=None
```sh
touch secure.txt
ls -l
chmod 400 secure.txt
ls -l
```

### 7.working with environment variables
export -> to set the value to env variable, echo -> to print value
```sh
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

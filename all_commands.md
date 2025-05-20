### creating and renaming files and directory
```sh
mkdir test_dir
cd test_dir
touch example.txt
ls -l
mv example.txt renamed_example.txt
ls -l
```

### viewing file contents
```sh
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd
```

### searching for pattern
```sh
grep "root" /etc/passwd
```

### zipping and unzipping
```sh
zip -r test_dir.zip test_dir
mkdir unzipped_dir
unzip test_dir.zip -f unzipped_dir
```

### downloading files
```sh
wget https://github.com/VinitKulkarni/gitPractice
```

### changing permissions
```sh
touch secure.txt
ls -l
chmod 400 secure.txt
ls -l
```

### working with environment variables
```sh
export MY_VAR="Hello, Linux!"
echo $MY_VAR
```

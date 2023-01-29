# workingDirectory

Mkdir folder1
Touch readme.md
Vim readme.md
i
This is an exercise for Bash (terminal) commands
esc
:wq 
CD folder1


## folder1

Mkdir subFolder1
Mkdir subFolder2
Mkdir subFolder3
CD subFolder1

rm -r subfolder3


### subfolder1

touch file1.txt
vim file1.txt
i
Exit saving this text
esc
:wq
touch file2.txt
vim file2.txt
i
This file will be deleted. Exit without saving
esc
:wq!
rm file2
ls // view current directory content
cat file1.txt
pwd // working directory path
cd ..
cd subfolder2



- file1

	- Exit saving this text

- file2

	- This file will be deleted. Exit without saving

### subfolder2

mkdir folderUnderSubfolder2
CD folderUnderSubfolder2
touch file3.txt
CD ../..
CD subfolder3



- folderUnderSubfolder2

	- file3

### subfolder3

- This folder will be deleted

## readme.md


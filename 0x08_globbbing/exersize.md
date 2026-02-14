### 1. make a script that echoes the files in a directory. (without using ls)
####    example:
```
            $ ./globbing_star
            file1.txt
            file2.txt
            directory1
            directory2
            globbing_star
```

### 2. make a script that do recursive globbing.
#### example:
```
        $ ./globbing_double_star
        file1.txt
        file2.txt
        dir1/file3.txt
        dir2/file4.txt
```

### 3. make a simple batch renamer script that does something like this.
```
        $ ls
        file1.txt file2.txt
        $ ./globbing_rename
        renaming all .txt files by adding 'new_' prefix:
        renamed file1.txt to new_file1.txt
        renamed file2.txt to new_file2.txt
        $ ls
        new_file1.txt file2.txt
```

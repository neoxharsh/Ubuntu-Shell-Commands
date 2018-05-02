### Ubuntu Command Library

---
> This repository is a list of basic and usefull commands that I find myself using often or have found from other sources.

> Sources will be listed below the relevant command.

> Please Note: This list is ongoing and feel free to add to this list.

#### Root Commands

---

> ##### Accessing Root Privileges

```bash
    sudo su
```

> ##### Exiting Superuser | Root access

```bash
    exit
```

#### File Directory Commands

---

> ##### Change Directory

```bash
    cd {foldername}
    Example: cd images
```

> ##### Listing all files in directory

```bash
    ls: List all files
    ls -lah:List all files with permissions
```

> ##### Copying a file

```bash
    cp {input_file} {output_filename/path}
```

> ##### Copying a folder

```bash
    cp -a {input_folder_path} {output_folder/path}
```

> ##### Moving or Renaming a file | folder

```bash
    mv {input_file} {folder_path}
    Note: You can have multiple input files as such: mv {input_file} {input_file} {folder_path}
```

> ##### Removing a file | folder

```bash
    rm {file/folder}

    In order to remove a folder with files in it: rm -r {folder_name}
```

> ##### Removing all files | folders from a directory

```bash
    rm -rf /path/to/directory/*
    -f: Force meaning we are not prompted for any yes or no
    -r: Recursive, will look through subfolders and recursively delete everything
```

> ##### Change all directory permissions (and sub folders) in specific folder

```bash
    find {filepath} -type d -exec chmod {permission_number} {} \;
```

> ##### Change all file permissions (and files in sub folders) in current folder

```bash
    find {filepath} -type f -exec chmod {permission_number} {} \;
```

#### Using Nano Editor

---

> ##### Opening a file with nano

```bash
    nano {path/to/file}
```

> ##### Copying a line

> ##### Saving a file

```bash
    Ctrl + o
    > This will prompt you for 'File name to write: '.
    > Once you have a file name chosen, pree 'Enter' to save
```

> ##### Closing a file

```bash
    Ctrl + x

    > If you have made changes to the file you will be asked to save changes with 'y' or 'n'
```

> ##### Removing a whole line

```bash
    Ctrl + k
```

> #### Uncut a line

```bash
    Ctrl + u
```

#### Using Vim Editor

---

> ##### Opening a file with vim

```bash
    vim | vi {path/to/file}
```

#### Other Useful Commands

---

> ##### Removing the last word typed

```bash
    Ctrl + w
```

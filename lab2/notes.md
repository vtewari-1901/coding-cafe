Answer 1) pwd also known as Print Working Directory outputs the absolute path of the location you are currently in.
Answer 2) ls -a lists ALL the files in the current directory including hidden files. plain ls lists the files but does NOT show the hidden files in the directory.
Answer 3) -rwxrwxrwx (first column). It reprents the file type and the file access permissions.
Answer 4) It works because your current working directory is your home folder, which directly contains the coding-cafe directory. The path is a relative path not absolute.
Answer 5) mv did two different job. First it moved the readme backup file from coding-cafe directory into week01 directory. Then in the second part, it renamed the README-backup.md file into old-readme.md in the directory itself.
Answer 6) There are 22 folders in my PATH.
Answer 7) Python3 lives in /usr/bin/python
Answer 8) My path differs from my neighbour's as we are on different operating systems. I am on Windows and he is on Mac, hence due to different platforms and installers, the path is different.
Answer 9) When I ran pyton3, the shell searched every directory listed in my system's PATH  looking for an executable named pyton3. Because of the typo, no file with that exact name exists in any of those PATH folders, so the shell failed to locate it and reported "command not found".
Answer 10) .venv is marked as a hidden folder so we could not see it in plain ls but saw it in ls -a.
Answer 11) We are now pointing to a virtual environment we just created, hence the .venv in the starting.
Answer 12) Activate started the virtual environment, so now we are now pointing to .venv/bin/python3
Answer 13) requests, urllib3, charset-normalizer, idna, and certifi appears in the second pip list output, but was absent from the first.
Answer 14) It puts us back to the original path outside the virtual environment. (/usr/bin/python3)
Answer 15) ls-h shortens the file size format to make it more readable, for eg. 50,000,000 would be seen as 50M.
Answer 16) Ctrl + C uses keyboard interrupt to stop whatever code is currently running within Python. Ctrl + D completely exits python itself.

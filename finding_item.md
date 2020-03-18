# Find Item in Bash
I learnt this watching the react loop 2019 conference videos.
To do this, you would have to run the following command on your terminal, inside the directory you want to search.
```bash
  ls -al | grep "<keyword of item>"
```
  
To count all the items that have the same search parameter, you do
```bash
  ls -al | grep "<keyword of item>" | wc -l
```
which is count the number of lines.

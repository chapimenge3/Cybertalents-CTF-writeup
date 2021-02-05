# Search in Trash

**Difficulty:** Easy  
**Points:** 50

## Challange Description

My HDD was destroyed in an accident. However, I was able to recover my recycle bin file . Can you know the flag ?

## Solution

### Required Tools & Skills

- Basic Linux commands
- [rifiuti](https://github.com/abelcheung/rifiuti2)

### Procedure

As the question says, the file that is provided is a recycle bin file. We can verify that by going to the terminal and typing:

```
$ file search-trash
search-trash: Windows Recycle Bin INFO2 file (Win2k - WinXP)
```

We then use the `rifiuti` tool to parse and dump the data from the tool. To do that, type:

`$ rifiuti search-trash`

The tool will list file names including the flag. Remove the `.txt` extension from the flag and submit.

****
**HAPPY HACKING!!!**  
**[Anonymously-Me](https://github.com/Anonymously-Me)**
****

# WCK-spellingbee-data

This is a repository to maintain a word list for WCKSpellingBee2 iOS app.

All the raw data (word lists) are saved in ***data/*** folder.
Run the following to split lines with multiple words... before running ***data/letsdoit.Rmd***.

```
%> tr ' ' '\n' < file
```

All the outputs (*.json files) are also saved in ***data/*** folder.  
Copy these files into ***wordList/*** folder.
Also, edit ***wordList/catalog.json*** file if the word list (json) file(s) is/are added.


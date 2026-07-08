 # Linux commands 

## Navigation 
- `pwd` - Shows my current directory.
- `ls`-Lists files and folders.
- `cd`- Changed destination.
- `cd ..`- Go up one directory.

## Creating Files and Folders 
- `touch`- Creates a new file.
- `mkdir` -  Creates a directory (folder).

## Managing Files
- ` cp` - To Copy File - (file name.md) (file name-backup.md).
    Example:
    ` cp dns.md dns-backup.md`
- ` mv` - To Rename File - filename.md filename.md
    Example:
    ` mv dns-backup.md dns-old.md`

## Viewing Files 
### `cat` 
Displays the entire contents of a file directory in the terminal.
Example: 
` cat git-notes.md`
Use when:
- Reading small files.
- Quickly checking the contents of file

--- 

### `less`
Opens a filr in a scrollable viewer.
Example:
`less git-notes.md`

Useful Keys:
- `down arrow`/` up arrow` - Move one line.
- `Space` - Next page.
- `b` - previous page.
- `/word` - search for a word.
- `n`- Go to the next search result. 
- `q` - Quit. 

Use when:
- Reading/ Searchign inside long files .
- Reading log files.

---

### `head`
Displays the first part of the file. 

Example:
` head git-notes.md` 
` head -5 git-notes.md`

Use when:
- Checking the begging of a file. 
- Looking at the first few lines of a log or configuration file. 

---

### `tail` 

Displays the end of a file. 

Example:
- ` tail git-notes.md`
- ` tail -5 git-notes.md`

Use when:
- Viewing the latest information in a file.
- Reading the newest entries in log files. 

---

### `tail -f` 

Continuously displays new lines added to a file. 

Example:
` tail -f server.log` 

Use when: 
- Watching a log file update in real time.
- Monitoring a running application or server. 

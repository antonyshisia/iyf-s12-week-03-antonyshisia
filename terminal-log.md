# Terminal Log

Practice session in `~/Documents/terminal-practice` using Git Bash.

## Commands Used

| # | Command | What it did |
|---|---------|-------------|
| 1 | `mkdir my-project` | I created a new folder called `my-project`. |
| 2 | `ls` | I listed the contents of the current folder, confirming `my-project/` exists. |
| 3 | `mkdir -p my-project/src/css` | i created `src` and `css` inside `my-project`. The `-p` flag creates any missing parent folders, so `src` was made automatically. |
| 4 | `ls` | I checked the current folder again. |
| 5 | `mkdir -p my-project/src/js` | I created the `js` folder inside `src`. |
| 6 | `mkdir -p my-project/src/images` | I created the `images` folder inside `src`. |
| 7 | `mkdir my-project/docs` | I created a `docs` folder inside `my-project`. |
| 8 | `mkdir my-project/tests` | I created a `tests` folder inside `my-project`. |
| 9 | `touch my-project/README.md` | I created an empty file called `README.md` inside `my-project`. |
| 10 | `ls -R my-project` | Listed everything inside `my-project` recursively (`-R`), including all subfolders, to verify the structure. |

```bash
cd ~/documents/iyf-s12-week-01-antonyshisia
mv accessibility-report.md devtools-exploration.md docs/
mkdir challenges
mv day-*.html css-day-*.html challenges/
ls -R
```

## How many HTML files are in the project 
 find . -name "*.html" | wc -l
15

## which files contain the word"conatct"
grep -rli "contact" --exclude-dir=.git .

## How many lines are ois your CSS file
$ wc -l css/styles.css
1029 css/styles.css

## What were your last 10 terminal commands?
history | tail -10
1. `ls`
2. `cp index.html about.html contact.html projects.html styles.css ../iyf-s12-week-02-antonyshisia/`
3. `cd ~/documents/iyf-s12-week-01-antonyshisia`
4. `find . -name "*.html" | wc -l`
5. `find . -name "*.html"`
6. `find . -name "*.html" | wc -l`
7. `find . -name "*.html" | wc -l`
8. `grep -rli "contact" --exclude-dir=.git .`
9. `wc -l css/styles.css`
10. `history | tail -10`

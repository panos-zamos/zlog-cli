# zlog-cli
zLog bash scripts

## install

- copy `lb` and|or `lt` to `~/bin` or make an alias what will execute those scripts
- make sure you have `~/Dropbox/logbook/` and `~/Dropbox/logtime/` directories

## lb
`lb` _(logbook)_ creates YYYY-MM-DD.md file in `~/Dropbox/logbook/` and opens it in default editor

**options:**

if there is an option `-y` it will open yesterdays file or if it is something else script will offer to create a directory with that name like `lb work` will create file in `~/Dropbox/logbook/work/` (will create that directory for you if it doesn't exists).

## lt
`lt` _(logtime)_ creates YYYY-MM-DD.md file in `~/Dropbox/logtime/` and appends a message to it

**options:**

`lt The quick brown fox jumps over the lazy dog` will add a line like 

_15:23:17 The quick brown fox jumps over the lazy dog_

`lt` without options will ask for input and each line append to the log file (empty line will end script)

`lt -e` will open log file in editior

## todo:

- [x] create a repo for `lb` & `lt` scripts
- [ ] use more from https://github.com/z017/shell-script-skeleton/blob/master/skeleton 
- [ ] enable config values
- [ ] check existing of `logbook` and `logtime` directories
- [ ] better documentation
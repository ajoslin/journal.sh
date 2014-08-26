journal.sh
----------

Take the effort out of journaling. Run `journal.sh` to effortlessly create a daily journal entry in the right folder, with your editor.

### Installation

Put this in your `.bashrc`/`.zshrc`/`.whateverrc`:

```sh
alias journal=/path/to/journal.sh/journal.sh
export JOURNAL_DIR=~/my-journal-entries
export EDITOR=vim
```

### Examples

If today is August 24th, open `~/my-journal-entries/2014-08-25.txt` in vim:

```sh
$ journal
```

Open the journal entry from May 15th, 2014:

```sh
$ journal 2014-05-15
```

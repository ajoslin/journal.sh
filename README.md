journal.sh
----------

Take the effort out of journaling. Run `journal.sh` to effortlessly create a daily journal entry in the right folder, with your editor.

### Installation

Put this in your `.bashrc`/`.zshrc`/`.whateverrc`:

```sh
alias journal=/path/to/journal.sh/journal.sh`
export JOURNAL_DIR=~/my-journal-entries
```

### Examples

`EDITOR=vi`, `JOURNAL_DIR=~/journal`

Open ~/journal/2014-08-25.txt in vi, if today was August 25th 2014.

```sh
$ journal
```

Open the journal from May 15th, 2014.

```sh
$ journal 2014-05-15
```

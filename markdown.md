## Part 1 task: Changing the name of the start parameter and its uses to base
key strokes:

`:0,64s/start/base/g<Enter>:wq<Enter>`

`:0,64s` : after going into vim, we type this command, which indicates to search whatever is entered next and replace every occurance within line 0 to line 64 with the next word separated by a slash "/". The reason that we gave it a range is so that we don't change anything outside the class like main.

`/start/base/g<Enter>`: this combo means to replace every occurance of "start" by "base" in this document

`:wq<Enter>`:saving and exit vim


## Commands I practiced:
~$ echo "Line 1" > notes.txt

~$ echo "Line 2" >> notes.txt


~$ echo "Line 3" | tee -a notes.txt

Line 3

~$ cat notes.txt

Line 1

Line 2

Line 3

~$ head -n 2 notes.txt

Line 1

Line 2

~$ tail -n 2 notes.txt

Line 2

Line 3


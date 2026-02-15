## Commands I practiced:
ubuntu@ip-172-31-28-192:~$ echo "Line 1" > notes.txt
ubuntu@ip-172-31-28-192:~$ echo "Line 2" >> notes.txt
ubuntu@ip-172-31-28-192:~$ echo

ubuntu@ip-172-31-28-192:~$ echo "Line 3" | tee -a notes.txt
Line 3
ubuntu@ip-172-31-28-192:~$ cat notes.txt
Line 1
Line 2
Line 3
ubuntu@ip-172-31-28-192:~$ head -n 2 notes.txt
Line 1
Line 2
ubuntu@ip-172-31-28-192:~$ tail -n 2 notes.txt
Line 2
Line 3


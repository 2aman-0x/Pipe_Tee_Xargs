<h1>Pipe Command basic explain and example.</h1>
<b>Pipes are used to redirect a stream from one program to another program.</b>

<b>- Use '|' symbol to separate two commands.</b><br>
<b>- example is like open a terminal screen then type ps -ef | grep httpd </b> 

```
1) Find NO. of files present in a directory.
cd /etc
ls -1 | wc -l


2) There are two files like name.txt and country.txt. Combine both files content using cat and sort it.
cat names.txt country.txt | sort


3) Find unique records from a file names.txt
cat names.txt | sort | uniq


4) How to see only 30-37th line in a file of 100 lines?
cat data.txt | head -38 | tail -7

```

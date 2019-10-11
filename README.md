Filtering

ls
*.txt
ls example?.txt -
ls ex*
ls *pp* - lists any file that has 2 ps in it


cs Amazing
touch cat.cat provis.sh miles.questions

# Linux Permission

Things users can do:
Read (r)
Write (w)
Execute (x)

Users that exist:
- owner
 - Typically the person/user who creates the file. However, it can be changed
- group
 - Every file belong to a single group. Groups have many users in it and gives acces
  to multiple people
- others
Everypme else not in a group or other owner.

ll = lists owner permison

Changing Permissions:

chmod [Permissions] [path/file]

head -3 reads to top 3 words from the file

wc words.txt = word count

## Streams, Redirects and Piping

Stream is a flow of data, they go from programs to hardware and vise versa
Every program we has 3 streams has connected to them

### Streams

STDIN
-Standard Input
- STIN code is 0
-
- STDERR
Standard output  =

= STDOUT
Standard Error

### Pipind and Redrects
Means we can join all these amazing command together

### Redirecting:

### This is redirecting of STDOUT
ls > list_of_ls.txt
wc words.txt > word_count.txt

cat words.txt >> word_count.txt

### This is redirecting of STDIN

wc < words.txt


ls missing_directory


### Redirecturing ST
ls | grep


Running the instantace of a program is call


## Process Management
ps = Processes

ps aux  = This lsts all the Processes

ps aux | grep vagrant

kill <proccess id>

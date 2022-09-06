echo Hello, World -script that prints “Hello, World”, followed by a new line to the standard output.
"(Ôo)' -script that displays a confused smiley
cat /etc/passwd -Display the content of the /etc/passwd file
cat /etc/passwd, /etc/hosts -Display the content of /etc/passwd and /etc/hosts
cat /etc/passwd /etc/hosts -Display the content of /etc/passwd and /etc/hosts
tail -n 10 /etc/passwd -Display the last 10 lines of /etc/passwd
head -n 10 /etc/passwd -Display the first 10 lines of /etc/passwd
grep -n 3 iacta -script that displays the third line of the file iacta
ls -la > ls_cwd_content -script that writes into the file ls_cwd_content the result of the command ls -la
rm -R *.js -script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
tail -1 iacta >> iacta -script that duplicates the last line of the file iacta
find ./* -type d -print | wc -l -script that counts the number of directories and sub-directories in the current directory
ls -t | head -script that displays the 10 newest files in the current directory
sort | uniq - script that takes a list of words as input and prints only words that appear exactly once
sort | uniq -u  -script that takes a list of words as input and prints only words that appear exactly once
grep "root" /etc/passwd -Display lines containing the pattern “root” from the file /etc/passwd
grep bin /etc/passwd | wc -l -Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -A 3 root /etc/passwd -Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
grep -v bin /etc/passwd -Display all the lines in the file /etc/passwd that do not contain the pattern “bin”
grep [[:alpha:]*] /etc/ssh/sshd_config -Display all lines of the file /etc/ssh/sshd_config starting with a letter
tr "Ac" "Ze" -Replace all characters A and c from input to Z and e respectively
tr -d [cC] -script that removes all letters c and C from input
rev -Write a script that reverse its input
cut -d":" -f 1,6 /etc/passwd | sort -script that displays all users and their home directories, sorted by users
ls -Rla *.gif -Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories
find . -type f -name “*.gif” | rev | cut -d’/’ -f1 | cut -d’.’ -f2,3 | 

rev | sort -Vf -script that lists all the files with a .gif extension in the current directory and all its sub-directories

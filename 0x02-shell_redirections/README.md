0x02-shell_redirections

echo 	Display a line of text
echo Display line of text
cat	Display file content
cat file1 file2 Display content of two files
tail Options file	print last part of a file
head -10 /etc/passwd 	Print first 10 lines of file
head -n file | tail -n 1	Displays third line of a file
echo "text" > file	Create new file with text
ls -la > ls_cwd_content	write content into a file
ls -1 iacta >> iacta duplicate last line of file
find -name "*.js" -type f-delete delete all regular files
find -mindepth 1 -type d | wc -l	count the number of directories and sub-directories
ls -t | head -10	displays 10 newest files in the directory
sort | uniq -u	takes a list of words as input and prints only words that appear exactly once
grep "root" /etc/passwd	dislay files containing pattern "root"
grep -c "bin" /etc/passwd	display number of lines that contain pattern "bin"
grep root /etc/passwd --after-context=3 	Display pattern root and 3 lines after
grep -v bin /etc/passwd display all the lines in the file

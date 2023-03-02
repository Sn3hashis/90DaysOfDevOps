1. To view what's written in a file.
2. To change the access permissions of files.
3. To check which commands you have run till now.
4. To remove a directory/ Folder.
5. To create a fruits.txt file and to view the content.
6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.
7. To Show only top three fruits from the file.
8. To Show only bottom three fruits from the file.
9. To create another file Colors.txt and to view the content.
10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.
11. To find the difference between fruits.txt and Colors.txt file.


===========================================================================================================

1. To view what's written in a file.

cat fileName

vi fileName

vim fileName

2. To change the access permissions of files.

chmod 777 fileName

3. To check which commands you have run till now.

history

4. To remove a directory/ Folder.

rm direcory name

rm -rf directoryname

5. To create a fruits.txt file and to view the content.

touch frutes.txt
cat frutes.txt

6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.

vi devops.txt add Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava. one in each line thn press "esc" + ":" + "!" to save the file

7. To Show only top three fruits from the file.

head -3 devops.txt

8. To Show only bottom three fruits from the file.

tail -3 devops.txt

9. To create another file Colors.txt and to view the content.

vi Colors.txt 
or
touch Colors.txt then cat Colors.txt

10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.

vi Colors.txt add ARed, Pink, White, Black, Blue, Orange, Purple, Grey.. one in each line thn press "esc" + ":" + "!" to save the file

11. To find the difference between fruits.txt and Colors.txt file.

diff devops.txt Colors.txt
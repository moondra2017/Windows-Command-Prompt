# Windows-Command-Prompt
Useful Commands




# CD

cd..
cd..\..

cd ' next directory name'

cd 'directory'\'next directory'  
#cd Moondra\documents

# DIR

dir  #dir of current directory

dir  /a   #hidden directory

dir /ad  # output all subfolders within directory

dir  *.txt   # output all text files within directory

dir  *.pgn  #all png files within directory

dir /s *.png   #all png files located within system

dir /s *.png |more     #all png files located within system displayed page by page (use spacebar to go to next page)

dir /s biotech.text   #searches for biotech.txt within system
(once  found copy outputted dir and `cd` into it)



# Output


dir > hello.txt    (output comannd `dir`'s output into hello.txt
echo "hello there" > hello.txt (write "hello there" to hello.txt)
type hello.txt   (print out hello.txt contents in command line)

type biotech.text > hello.txt  (copy the contents of biotech.text > hello.txt)


# Open Files

notepad dir.txt (use notepad to open dir.txt)

dir.txt  (dir.txt opened by default program)

EXEL.png (image file opened by default program)

mspaint

calc


# Make and delete directories


mkdir   test_folder

rmdir   test_folder

mkdir  apple\apple2     (make a directory with subdirectory)

rmdir  /s apple   (remove directory with subdirectory)

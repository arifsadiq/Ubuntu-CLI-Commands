# I) File Management
ls : Lists files and directories.

ls -a : Lists files including the hidden files

touch [filename] : Creates an empty file

cp [source] [destination] : Copies files from source to destination

mv [source] [destination] : Move files or Rename files

rm [file name] : Deletes a file

rm -r [path/to/dir] : Deletes a directory

# II) Directory Navigation
pwd : Displays the current directory path

cd [directory] : Change the current directory

mkdir [dirname] : Create a new directory

# III) File Permissions and Ownership
chmod [who][+/-][permissions] <file> : Changes file permissions

chmod u+x [file] : Make a file executable by its owner

chown [user]:[group] <file> : Change ownership of a file

# IV) Searching and Finding
find [dir] -name <search_pattern> : Find files and directories

grep [search_pattern] [file] : Searches for a pattern in files

# V) Archiving and Compression
tar -cvzf [name.tar.gz] [files] : Compresses files into a tar.gz archive

tar -xvzf [name.tar.gz] [destination] : Extracts a compressed tar file

# VI) Text Editing and Processing
nano [file] : Opens a file in the Nano text editor

cat [file] : Displays the contents of a file

less [file] : Displays the paginated content of a file

head [file] : Shows the first few lines of a file

tail [file] : Shows the last few lines of a file

awk ‘{print}’ [file] : Prints every line in a file

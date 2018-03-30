# File-System
A Simple File System for UNIX


# Description
This Repository contains the code for a simple file system implemented for UNIX. The File system is implemented using File System in User Space (FUSE) and has persistent storage capabilities.

# How to Run?
  # Compile 
  gcc -Wall fsys.c `pkg-config fuse --cflags --libs` -o fsys
  # Execute 
  ./fsys /PATH_TO_MOUNTPOINT 
  
# Basic Functionlity Supported  
  1. mkdir
  2. readdir
  3. open
  4. getattr 
  5. rmdir
  6. create 
  7. write 
  8. truncate
  9. unlink
  10. rename
  11. destroy 
  12. opendir
  13. rename

Here's what this program does/should do.

1. CD into project’s root directory.
2. PRINT .sol filenames recursively
3. PRINT the number of .sol files
4. PAUSE regularly so the user can see the script working
4. BOLD important text to improve user visibility
4. SUM lines of code in “all” .sol files recursively.
  1. BUT exclude .sol files we’ve audited before 
  2. AND .sol files that are public libs
  3. AND .sol files that are in testing folders
  4. AND .sol files that are exact duplicates of other .sol files 
  5. BUT include lines in .sol files that aren’t duplicates 
5. PRINT result
6. GENERATE surya describe
7. GENERATE surya inheritance
8. GENERATE surya call

As features are added to the main program, they will be added to this doc.

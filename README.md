# External-and-Internal-Filesystem-Fragmentation-
This program exhibits the memory management feature of OS, by implementing a filesystem.

## Functionalities provided:-
- Allows users to create a filesystem, comprising of files
- Delete files from filesystem to exhibit fragmentation
- Allows users to insert files from 'x' and 'x' positions in an index
- Provides total filesystem size after file creation
- Returns total calculated space of filesystem after file deletion

## Screenshots

Case 1 - The user wants to store a file.
- He/she is able to define the size of the file,as well as the data to be stored in a file
- The user has defined start of file of block froom 0 and ends it at 15
- The program' functionality enables it to insert the data,into the file,using an array
- The user wants to enter 7 data inputs.Accordingly the data is stored to an array

![Input1](https://user-images.githubusercontent.com/77625109/122107686-f6db7500-ce38-11eb-9273-e7db2b20a798.png)

Output -  Out of 15 total blocks ,7 were used and 8 are remaining free.

![Output1](https://user-images.githubusercontent.com/77625109/122107704-fe028300-ce38-11eb-9962-e0e6574e6e9b.png)

Case 2 - The user wants to enter a total of 2 files
- The starting extent for the two files to be created are specified
- The current state of the file system is displayed
- Now the data to be held by each file is entered,to be stored onto 2 alternate arrays

![Inpu2](https://user-images.githubusercontent.com/77625109/122107722-02c73700-ce39-11eb-84ed-3bb89022858f.png)

Output - 

![Output2](https://user-images.githubusercontent.com/77625109/122107741-065abe00-ce39-11eb-9080-5637687c884d.png)

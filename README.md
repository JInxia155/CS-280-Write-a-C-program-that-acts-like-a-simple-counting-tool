# CS-280-Write-a-C-program-that-acts-like-a-simple-counting-tool
Write a C++ program that acts like a simple counting tool


Download Link :https://programming.engineering/product/write-a-c-program-that-acts-like-a-simple-counting-tool/


Write a C++ program that acts like a simple counting tool for collecting information from textual files of documents prepared for a simple scripting language interpreter. An input file for the simple scripting interpreter includes two types of data, commented lines and scripting code lines. A commented line is recognized by either the two characters “##” or “//” at the beginning of the line, which would be skipped by the scripting interpreter. All other non-commented lines are considered as part of the scripting code, including any blank lines with whitespace.

The program for the simple counting tool should read lines from a file until the end of file. The program should prompt the user for the file name to read from. The program should open the file for reading, and if the file cannot be opened, it should print the message “File cannot be opened “, followed by the filename, and exit.

After reading the contents of the input file, the program should print out the total number of lines, the number of commented lines, the maximum length of commented lines, the maximum length of non-commented lines, the commented line of maximum length delimited by double quotes, and the non-commented line of maximum length delimited by double quotes. An example of an input file and the expected results after processing the file are shown below. Given the following file contents,

Line number
	

File contents
		

1
	

run
	

prog1

2
	

//
	

3
	

delete
	

4
	

### execute next command

5
	

delete myfile

6
		

7
		

8
	

copy file1 file2

9
		

10
	

// welcome to cs 280

11
	

print myfile

12
		

13
	

// terminate script

End of File marker
		
		

the generated results are as follows:

Submission Guidelines

    Please name your file as “RAx_firstinitial_lastname.cpp”. Where, “firstinitial” and “lastname” refer to your first name initial letter and last name, respectively, and “x” refers to the recitation assignment number (e.g., 1, 2, etc). Your program Submission is to Vocareum environment. Follow the link of Recitation Assignment 2 on Canvas in the Modules or Assignments pages to connect to the current assignment on Vocareum.

    Submissions after the due date are accepted with a fixed penalty of 25% from the student’s score. No submission is accepted after Wednesday February 1st, 2023, 11:59 pm.

Grading Table

            Testing Cases
            	

            Points

            Case 0: File cannot be found
            	

            1.0
            	

            Case 1: Empty File
            	

            1.0
            	

            Case 2: General script file 1
            	

            1.0
            	

            Case 3: All whitespace
            	

            1.0
            	

            Case 4: Non-commented lines only
            	

            1.0
            	

            Case 5: General script file 2
            	

            1.0
            	

            Compiles Successfully
            	

            1.0
            	

            Total
            	

            7
            	


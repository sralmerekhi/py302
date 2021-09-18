# py302

TABLE OF CONTENTS
I. INTRODUCTION
II. ANALYSIS
III. DESIGN
IV. CONFIGURATION
V. MAINTAINERS
I. INTRODUCTION
	This is an algorithm that calculates students grades based on the percentage they chose A. Ask user for the assignment percentage. B. Ask the 
	user for their grade on that assignment. C. Add the assignment amount to the total amount accumulator. D. Add the grade to the total 
	grade accumulator 
II. ANALYSIS
	This grading algorithm is designed to give significantly more weight to reward a student for their actions on Homework and Projects 
	throughout a semester, yet still have their Final and Midterm exams carry enough percentage weight without overwhelming their 
	total grade.
III. DESIGN 
Program start
	Declare and Initialize variables
		AssignmentGrade = 0
		TotalAssignmentAmount = 0
		
		TotalGrade = 0
		AverageGrade = 0
	Start Loop
		
		Record AssignmentType string
		
		Record AssignmentWeight value
	Until Weight = 1, End Loop 
	Start infinite loop
			Record assignment grade from the user input
			Record AssignmentType from user input			
			
			Multiply AssignmentGrade by AssignmentWeight 
			Add to TotalGrade
		If TotalAssignementAmount is greater than zero
			Output the AverageGrade as percentage of TotalGrade/TotalAssignment
		Else output zero as the assignment total amount
		Increment TotalAssignementAmount
	End Infinite loop
	Start the grading loop
			Where the average is less than 60, output grade as “F”
			Where the average is less than 70, output grade as “D”
			Where the average is less than 80, output grade as “C”
			Where the average is less than 90, output grade as “B”
		Otherwise the grade is “A”
	End loop
Program End
IV. CONFIGURATION
	This algorithm is designed for a linear approach to assigning grades to an individual student. It opens by defining assignment types 
	and the grading weight of the assignment. These can Each have an assigned type name that has an associated weight. 4 Generic assignment types can 
	be set as default if desire, with one of each weight set at 40%, 30%, 20%, and 10%
		
	Each grade is input and added towards the average grade.    
V. MAINTAINERS
	
	Salman Almerekhi 
	Jefferson LeVasseur


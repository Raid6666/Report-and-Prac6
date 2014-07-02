Blackbox versus Whitebox Testing
================================
Software testing is a means of affirming the quality of software and thus delivering an error-free application. Software process
is the process of executing a system or program with an intention of finding errors (Baresi & Pezze 2006). In the recent years,
software testing has developed into a different discipline giving room to different testing methods that have been analyzed
in this area. When testing programs and software, there are many types of tests that can be used. The two main test methods 
are black box and white-box testing. The formats are applied at every level of testing including unit, system, integration,
and acceptance tests (Baresi & Pezze 2006).

The phrase ‘Black Box’ is used to refer to the software treated like a Black Box. When the software is treated as a Black Box, 
the source code or system is not checked. The engineer involved in Black Box testing is only aware of the inputs and expected 
outputs, but does not know how the software changes the inputs into outputs. The test engineer tests software without having
the entire knowledge about its workings. Black box testing is called behavioral testing since an engineer wants to test how 
the software performs as a whole (Schroeder & Korel 2000).The testing is done when one knows the real users of the software, 
who generally lacks the knowledge of the code itself. In this testing, the test cases’ inputs are the driving factor.
Black box testing focuses on ways to increase the effectiveness of testing with minimum cost. 
The following three techniques can be used in choosing the inputs (Schroeder & Korel 2000).

I.	Boundary Value Analysis:
----------------------------
The approach focuses on testing the boundary values connected to the system. It tests the input domain’s boundaries that
may have the uppermost probability of giving incorrect outputs. 

II.	Error Guessing:
-------------------
A knowledgeable tester uses the approach to identify the defects and develop their equivalent test cases.

III.	Equivalence Class Partitioning:
-------------------------------------
imited functions are identified together with their corresponding expected outputs, valid inputs, and invalid inputs.
The approach seeks to identify classes of errors, reducing cases required. 


White box testing refers to the testing of the exterior functionality of the code by examining the program code, which 
realizes the exterior functionality. White box testing is a methodology that designs the test cases, which uses the application’s 
control structure in designing test cases. The testing, white box testing, tests the program code and its structure, 
and the interior design flow. White box, also called clear box, implies the testing of the code’s structural internals.
The testing allows an individual to peep into the ‘box’. The following tasks are usual of white box testing: logging, 
boundary tests, and use of assertions (Naik & Tripathy 2011).

When it concerns white box testing, the tester’s knowledge about the system emerges as the driving factor. It assists the tester
design test cases targeted at identifying defects in the interior working of the system. 
The following are white box testing’s techniques (Naik & Tripathy 2011).
I.	Decision Tests:
--------------------
Every decision directions need execution at one or more times in the life cycle of the testing.

II.	Branch Condition Tests:
----------------------------
Every condition in a decision needs testing for proper working.

III.	Statement Tests:
-----------------------
All of the statements in the code need a test case connected to it so that every statement is executed during the cycle 
of the testing. 

IV.	Data Flow Tests:
--------------------
It ensures that each variable and data used in the system undergoes testing by passing particular variables through 
every possible calculation. 

V.	Condition Tests:
--------------------
All the possible conditions within a decision for every decision undergo testing. 

VI.	Multiple Condition Tests:
-----------------------------
The test ensures that all points of entry in the code are tested. The testing must happen at least once in the life cycle
of the testing. 

Whereas black box testing centers on the software’s functionality, white box testing concentrates on the internal logic 
used in the system. Black box testing includes techniques such as equivalence partitioning, syntax testing, boundary value
analysis, and error guessing. White box-testing majors on techniques such as path testing, loop testing, and control structure.
Whereas a non-technical tester may be hired for functional testing, this is not possible for white box testing since it requires
the tester to understand the application’s technical aspects. Black box testing is instrumental in testing larger systems.
These tests are done from the end user’s point of view. Black box testing cannot be done without appropriate understanding of 
the specifications (Offutt 2002).

Whereas white box testing validates the interior structure and workings of a software code, the black box testing focus is 
to validate functional requirements (Offutt 2002). In order for one to do white box testing, it is essential to have 
the knowledge of the primary programming language. The modern day software systems employ different technologies and 
programming languages and it is hard know them all. 
The following are the process of writing black box test cases: (Schroeder & Korel 2000)

I.	A tester examines specifications and requirements of the system.

II.	The tester then explores the UI and functionality of the system in order to understand how the system’s processes can work.  

III.	The tester devises test cases with their valid inputs and subsequent outputs.  

IV.	Inclusion of some negative test cases together with their invalid inputs and outputs that are expected.  


The following are the process of writing white box test cases:

I.	The tester understands the system’s structure by analyzing its code.

II.	The tester comprehends the code’s weak spots that are prone to defects.

III.	The tester will develop test cases that will cover individual information and branches in the code.

IV.	The tester will also develop test cases that will test appropriate working of the functionalities and the system’s error
handing.  

Software testing helps to provide stakeholders with enough information concerning the quality of software under a test. The test
helps to provide an independent and objective view concerning software in order to permit an organization or individual
to understand and appreciate the risks of implementing software (Naik & Tripathy 2011). The quality process has an aim of 
improving software, assessing software’s product and making better the quality process. The quality process helps to provide
a framework for selection and arrangements of activities. The quality process ensures that necessary activities are organized
to detect every group of fault (Gao et al. 2003). The other types of software testing are unit testing, integration testing, 
functional testing, end-to-end testing, sanity testing, regression testing, load testing, usability testing, and stress
testing among other tests. 
 
References
===========
Baresi, L & Pezze, M 2006, An introduction to software testing. Electronic Notes in Theoretical		 Computer Science, 148(1),
pp. 85-110.

Gao, J, Tsao, HS & Wu, Y 2003, Testing and quality assurance for component-based software,		 Artech House.

Kan, SH 2002, Metrics and models in software quality engineering, Addison-Wesley Longman		 Publishing Co., Inc.

Naik, S & Tripathy, P 2011, Software testing and quality assurance: theory and practice, John		 Wiley & Sons.

Offutt, J 2002, Quality attributes of web software applications. IEEE software, 19(2).

Schroeder, PJ & Korel, B 2000, Black-box test reduction using input-output analysis, 25 (5), pp.		 170-178.

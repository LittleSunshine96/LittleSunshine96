
Team Name: MindingCoder’s
Name: Ciara Jones/ Cody Lombardi
Date:06/01/2022

 Hi today me and my partner created a program that will match a doctor with their chosen language and medical specialization to a matching country.
The solutions implemented in this program determine the country for which language option is chosen. In this case, the University of California Riverside annually selects 100 graduates to participate in the Doctors without Borders program. These physicians are matched based on specialized areas, language fluency, and preferences. Each pair of participants are given the opportunity to aid on-site physicians for 60 days. Currently, Doctors without Borders expand to over 10 countries.
   
   We used # include iostream to output each option: What language are you fluent in, Language option as well as each language to choose 
 from, What is your specialization along with specializations to choose from, and your chosen country. 
 We used the #include string to identify each country that would match a specific language. 
 Each of the following was used for calculation: #include <cstdlib>#include <ctime>#include <cmath>#include <time.h>. 
 #include <stdio.h> was used to perform various function for input and output. 
 To make sure that the outcome was random for the user we used a void generator for each choice. 

    [Final-languages-and-Spealist (2).zip](https://github.com/LittleSunshine96/LittleSunshine96/files/8850631/Final-languages-and-Spealist.2.zip)
[Final-languages-and-Spealist (2).zip](https://github.com/LittleSunshine96/LittleSunshine96/files/8850634/Final-languages-and-Spealist.2.zip)
Integers used were choice and second choice to determine each option choice. 
 The switch statement allows a variable to be tested for equality against a list of values. 
 Each value is called a case, and the variable being switched on is checked for each case. 
 We used char type to store characters and letters for the specialization. 
     
     Lastly, we used srand(time(0)); // to Initialize the random number generator for the program to initialize the random seed. 
 As well as the probability from the multiplication of the given languages and specializations which is five languages and five specializations. 
 The calculations that were used to solve this program included multiplication and division to provide an accurate probability for the program to run correctly.

START

//Declare variables
int choice;
int secondChoice;

PRINT "What language are you fluent in?"

//Used to create space
PRINT " "

//Prnts out list of different language options
PRINT "Language Options:"
PRINT "========================"

PRINT "1. English"
PRINT "2. Spanish"
PRINT "3. Mandarin Chinese"
PRINT "4. French"
PRINT "5. Arabic"
//Used to create space
PRINT " "

//
READ "You have chosen: choice"

//Switch statement used for the different language options
SWITCH(choice-1)
CASE 0:
PRINT "You have chosen English."
BREAK → PRINT "What is your specialization?: "


CASE 1:
PRINT "You have chosen Spanish."
BREAK → PRINT "What is your specialization?: "

CASE 2:
PRINT "You have chosen Mandarin Chinese."
BREAK → PRINT "What is your specialization?: "

CASE 3:
PRINT "You have chosen French."
BREAK → PRINT "What is your specialization?: "

CASE 4:
PRINT "You have chosen Arabic."
PRINT "What is your specialization?: "


//Used to create space
PRINT " "

//Prints out list of specializations
PRINT "Specialization Options:"
PRINT "=========================="

PRINT "1. Dermatology"
PRINT "2. Allergy and Immunology"
PRINT "3. Cardiology"
PRINT "4. Anesthesiology"
PRINT "5. Endocrinology"


//Used to create space
PRINT " "

//User enters specialization
READ "You have chosen: secondChoice"

//Switch statement used for the different options for switch(secondChoice


char (spealization);
SWITCH(spealization)
CASE 1:
PRINT "You have chosen Dermatology."
BREAK → PRINT "Your chosen country is: countries"

CASE 2:
PRINT "You have chosen Allergy and Immunology."
BREAK → PRINT "Your chosen country is: countries"

CASE 3:
PRINT "You have chosen Cardiology."
BREAK → PRINT "Your chosen country is: countries"

CASE 4:
PRINT "You have chosen Anesthesiology."
BREAK → PRINT "Your chosen country is: countries"

CASE 5:
PRINT "You have chosen Endocrinology."
BREAK → PRINT "Your chosen country is: countries"
generator (choice);

PRINT "The sample space is amount of languages multiplied by"
PRINT "number of specializations = 5 * 5 = 25"
PRINT " "
PRINT "The probability of choosing one language"
PRINT "and one occupation is 1/100 which is about 1.43%"

STOP

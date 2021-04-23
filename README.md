# Class_ID 106395: Compiler Construction Project #
<!-- The 6-Digits is Our Course ID-->
## Instructor: Sir Farooq Zaidi 

### PROJECT MEMBER ###
STD_ID | STD_Name
------------ | -------------
**62163** | **M.Burrair Wali** 
<!--This is the Group Leader's Name and his ID in bold-->

## Project Description ##
It's a simple Tiny C (Sub- set of C) compiler that uses a flex file to describe its tokens, which the YACC then parses.

## Sample Language Used ##
{
   int i;
   int j; 
   a = (i * j)/2.0;
}


# include#
#include<stdio.h>
int yywrap() {
    return 1;
}
int main(int argc,char *argv[])
{
if (argc > 1)
{
    FILE *fp;    
    fp = fopen(argv[1], "r");
	printf("Read File %s",argv[1]);
//    fp=fopen(argv[2],"w");     
    if (!fp)
    {
        fprintf(stderr, "failed open");
        exit(1);
    }
   yyin = fp;   
}
printf("Start Scaning\n");
printf("Enter Input:\n");
yylex();
return 0; 
}
                  
### Lexical Specification ###
"Keywords", "Identifiers - a,b", "Digits - 0-9", "Exponential", "if else", "While", "return", "void", "string/int/float/double", "Operators -+/etc", "Bracket - ()", "Square Brackets - []", "Braces - {}", "Comma - ,", "Semi-Colon - ;", "WhiteSapce - ", "Dot - .", "int Const", "real const"

## Problems Faced ##
The Main problem i faced is i was expecting i will get a partner so we could divide our project but at last i didn't get anyone. For me its new for us to make project on compiler as we heard from the starting semester CC is hard Course also i dodn't like or i was not good in automata so this course was quite unintrested. There was less material regarding what we need and the coding languge was little difficult becuase its near to low level language. There is also one more problem in starting i didn't know what i ahve to do but after giving time i was able to complete it even though i'm not perfect but i try my best.

### Problem 1: It's true we didn't learn with our heart and mind, how to code, because we didn't planed to code in our childhood. ###
As speaking truth not behaving to anyone, Right Now we have less choice to move anywhere and  instead of coding we can pursue our carrier in other fileds of Information Technology as it's has vast areas.

### Problem 2: The Main and and actual problem is our intermediate marks brings here in this field as i think sometimes, even i can debate on this because our education policy is too worst we judged by our marks not by our ability ###
well i can write so much in this particular fields as well as i can describe more but if i see its also our fault i don't know, why i dont like to read books or study well, for getting marks.
 

## References ##
- https://www.geeksforgeeks.org/flex-fast-lexical-analyzer-generator/
- https://youtu.be/Ql3drqJrR2Q
- https://github.com/jacobgarcia/tinyc-compiler
- 
- 
-  
- 

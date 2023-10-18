# Movies-Datasets
The data sets of korean drama from https://www.kaggle.com/datasets/ahbab911/top-250-korean-dramas-kdrama-dataset is used to create different function and to design dashboard using the MS Excel application. 
# Application of Different Function in Excel and Designing Dashboard 
# Text Functions

**LEN Functions**

  The **LEN functions**(length) is a function in excel categorized under text functions which returns the length of the specified string including the letters, numbers, characters, and all spaces. This function can be useful if we wish to get the length of a given text string as the number of characters in a given cell. To apply this function use the formula:
 
 **=LEN(text)**
 
For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =LEN(A2), would return _**14**_. This shows that there are 14 characters in the text **Move to Heaven**.

  <img width="501" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/676b7bf6-fe6f-43a2-aca8-2a608b12ee3d"> <img width="306" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/369aa898-9e30-43da-9d1f-f4112a67ab3f">


**UPPER Function**

  The UPPER function in Excel allow you to convert all characters in a supplied text string to uppercase/capital letters. Using the formula:

 **=UPPER(text)**

 For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =UPPER(A2), would return _**MOVE TO HEAVEN**_. This shows that all the letter in the text is in uppercase. 


  <img width="531" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/2cbb1549-2162-4e60-9beb-a8dc2e54293b"> <img width="287" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/4710b0a6-cb9e-4c72-ada4-e3b1cb65531f">


**LOWER Function**

 The LOWER function in Excel is the reciprocal of UPPER Function. This allow you to convert all characters in a supplied text string to lowercase. Using the formula:

 **=LOWER(text)**

 For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =LOWER(A2), would return _**move to heaven**_. This shows that all the letter in the text is in lowercase. 

<img width="541" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/1126efd7-8ffd-4bed-9eb6-01412106b987"> <img width="317" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/9af2ac48-fa4a-43a8-ad8f-b76c9beb5f3f">


**LEFT Function**

  The LEFT Function is used to retrieve or extract a chosen amount of substring from a string counting from the left side of excel cell. To apply this function use the formula:

  **=LEFT(text,[number_of_characters])**

  Parameters

  text - The string that you wish to extract

  
  number of characters - Optional. It indicates the amount of of characters you want to extract starting from the left most part of string. If this parameter is omitted, only 1 characteris returned.

  For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =LEFT(A2,3), would return _**Mov**_. 3 count from the left of the text "Move to Heaven" is "Mov".
  

<img width="379" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/e2624e57-9efd-4a9b-bebb-2e5a30a00738"> <img width="458" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/c4c7cc19-7d42-4c8e-9371-48727a0aa584">


**RIGHT Function**

  The RIGHT Function is used to retrieve or extract a chosen amount of substring from a string counting from the right side of excel cell. To apply this function use the formula:

  **=RIGHT(text,[number_of_characters])**

  Parameters

  text - The string that you wish to extract 
  
  
  number of characters - Optional. It indicates the amount of of characters you want to extract starting from the right most part of string. If this parameter is omitted, only 1 characteris returned.

  For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =RIGHT(A2,5), would return _**eaven**_. 3 count from the left of the text "Move to Heaven" is "eaven".
  
<img width="381" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/45458e79-c046-4254-99f4-dbf73b9d5e3e"> <img width="475" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/342d1ebb-b27e-457e-be31-730440b2bc9f"> 

	
# Math Functions

**GCD Function**

The GCD Function is a numeric function that returns the Greatest Common Divisor of two or more integer without remainder. The GCD is the greatest common factor that divides them. The syntax of this function is:

**=GCD(num1,num2,...)**

For example, in the 2nd row we have the **rank** (B2)  and **episodes** (C2) of the first drama entitled "Move to Heaven". Using the syntax = GCD(B2,C2), the GCD of the 2nd row is 1.

<img width="377" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/6064769c-c334-423b-bc80-697d7f04a067"> <img width="332" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/4be12085-a33e-4e97-bc95-e4c2e703c09f">


**SQRT Function**

The sqrt function is a basic mathematical function that returns the positive squareroot of the given number. Square root is the number, that when multiplied by itself will gives the original number. IF the return is negative it will become error. You can use the 


**=SQRT(number)**

For example, you want to find the sqrt of the number of episode in row 3 column 3 (B3). Using the syntax =SQRT(B3), the return sqrt will be 4. 


<img width="315" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/be7df806-b623-4a3f-9e96-ed20c1e33c03"> <img width="283" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/8864c982-8adf-49be-be3b-fb613bbb847a">


**MIN & MAX Function**

The MIN & MAX Function is a basic math function that can be used to measure the smallest and largest value from the set of data. The minimum is for smallest value while the maximum is for the largest value. The syntax for this functions is as follows:

**=MIN(number1,number2...)**                                     **=MAX(number1,number2...)**

For example, we have set of value from the number of episodes ranging from B2:B251. Using the syntax = MIN(B2:B251) the minimum episode will be 1 while for syntax = MAX(B2:B251) the maximum episode will be 133.

<img width="479" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/11972137-5a8e-4d93-9e3e-b03e64286f10"> 

<img width="321" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/188d229d-7b3f-457b-b0b6-7585040b28af"> <img width="256" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/11f4c685-5924-4505-8056-20ac9d17d8e2">


**MEDIAN Function**

The MEDIAN FUnction is under the basic math function that determine the middle value from the set range of data that separate the lower and higher half of values. The median is a type of average value, which describes where the center of the data is located. The minimum can be determine using the syntax

**=MEDIAN(num1,num2,...)**

For example, we have set of value from {1,2,3,4,5}. Using the syntax =MEDIAN {1,2,3,4,5} the middle/average will be 3. 

<img width="343" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/f07ef826-dca9-4746-9701-0a9e59101b53"> <img width="247" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/2a392e3e-eb1c-4a5a-b41a-150dd7f8810e">


**ROUND Function**

The ROUND Function is used to return a number rounded  to a specified number of digits.. This can round from left to right of the decimal points. The syntax for this function is 

**=ROUND(number,num_digits)**

For example, if cell B3 contains 9.1, and you want to round that value to two decimal places, you can use the following formula: =ROUND(B4:B253,0) The result of this function will be 9.

<img width="293" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/015bc8ac-edac-445c-b772-a1850185f858"> <img width="315" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/3ec3ac49-d17e-4f16-8e6b-8f7bef714101">


# Logical Functions

**IF Function**

The IF Function allows you to make logical comparisons between a value and what you expect.So an IF statement can have two results, one value if it is TRUE and will return another value if FALSE. The syntax of IF Function is 

=IF(conditions,value_if_true,value_if_false). 

<img width="876" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/e7fc3f75-1dc3-4bb2-bb7f-84cac819b12f"> 
<img width="320" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/5ca13fc3-a984-4946-9ea6-cd099e694186">

**AND Function**

The AND Function returns TRUE if all its arguments evaluate to TRUE, and returns FALSE if one or more arguments evaluate to FALSE. The AND function is often used together with the IF function. The yntax for this function is

**=AND(condition1,[condition2],...)**

<img width="914" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/2e8a9360-ff75-485e-89b9-f4d58343d877">
<img width="441" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/c62b059f-7ab5-4e1a-8f96-3656b14a7f29">

**OR Functions**

The OR Function in Excel,is a logical formula that tests multiple conditions to determine if any of them are true. If at least one of the conditions is true, the function yields "TRUE." The result is "FALSE" if all the conditions are false. The syntax for OR function is 

**=OR(condition1, [condition2,...condition n])**

<img width="915" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/30367727-8f5f-4909-b597-e7510a4461d3">
<img width="392" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/96722b84-d52a-4978-b2fc-be6b3a7f23b0">

**NOT Function**

The NOT Function helps check if one value is not equal to another. If we give TRUE, it will return FALSE and when given FALSE, it will return TRUE. So, basically, it will always return a reverse logical value. The syntax for this function is

**=NOT(logical)**

<img width="726" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/8c299496-eae9-4dc0-85a1-fa5ab5d59d95">
<img width="280" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/e9b36b4d-1ca0-470a-98de-39394d312989">

**XOR Function**

The XOR Function (exclusive OR) is an logical function that would return TRUE if one of the statements is true and FALSE if both statements are true. If neither of the statements is true, it also returns as false. The syntax for this function is

**=XOR(logical1,[logical2],...)**

<img width="774" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/a25bd239-e9b9-49d4-9cc8-ea708c6a401e">

# Information Functions

**ISERROR Function**

The ISERROR Function is used to determine if a numeric expression represents an error. IsError returns True if the expression argument indicates an error; otherwise, it returns False. For any error type excel generates, including #N/A, #VALUE!, #REF!, #DIV/0!, #NUM!, #NAME?, or #NULL!. The syntax for the ISERROR Function is 

**=ISERROR(value)**

<img width="486" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/65f31f85-b317-4a40-9fe2-cb536b93fbb8"> <img width="341" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/10ea1970-12b0-465c-8a3a-735cc06d4808">

**ISERR Function**

The ISERR Function returns TRUE for any error type except the #N/A.  You can use the ISERR function together with the IF function to test for an error and display a custom message, or perform a different calculation if found. The syntax for ISERR Function is

**=ISERR(value)**

<img width="472" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/7624886b-39f8-49de-9f72-1be55bb4fb84"> <img width="285" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/b7cf4130-cc5b-4931-bcbe-301c8b8b7592">



**ISNA Function**

The ISNA Function returns TRUE when a cell contains the #N/A error and FALSE for any other value, or any other error type. The ISNA function takes one argument, value, which is typically a cell reference. The syntax for this function is 

**=ISNA(value)**

<img width="475" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/4a77aba6-2ce1-463d-b8db-d21f143c0ce4"> <img width="272" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/fbeabe76-8406-4b11-811b-288250b620f6">

**ERROR.TYPE Function**

The ERROR.TYPE function returns the number that corresponds to a specific error value. You can use ERROR.TYPE to test specific kinds of errors. If no error exist, ERROR.TYPE returns #N/A. The Syntax for this one is 

**=ERROR.TYPE(vlue)**

<img width="351" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/84f713d4-095d-41f9-95c4-cd14fd4d832f"> <img width="309" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/55a424c5-daf3-4ba7-a82c-1022deb7f817">

**ISNUMBER Function**

The ISNUMBER Function is use to return TRUE when a cell contains a number, and FALSE if not. Syntax of ISNUMBER Function

**=ISNUMBER(value)**

<img width="608" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/e7184547-03b6-44f6-a27e-82f9c47a340d"> <img width="367" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/668b632f-3fff-4475-b8fb-9d891940c2b4">













# Date and Time Functions		

# Lookup Functions

The Lookup functions 

LOOKUP Function

<img width="910" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/5bdc763b-1b94-47b6-a371-845db6aa5dfe">





VLOOKUP Function

<img width="808" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/69cd6fad-9c28-4ea3-97d9-1155e1b1c858">


MATCH Function

<img width="917" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/f509f2c6-d146-4495-8855-11969d86e1e1">



INDIRECT Function

<img width="861" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/220dd359-8996-47cc-a80b-a48fad1dec5b">

ADDRESSS Function

<img width="891" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/1aac4f5e-0e5e-4dbe-98df-927d08c73c22">






         

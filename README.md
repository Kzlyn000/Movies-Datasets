<img width="452" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/79cfc292-182f-4d16-9dd5-1d67dc766d0e">


# Top 250 Korean Dramas (KDrama) Dataset
The data sets of korean drama from https://www.kaggle.com/datasets/ahbab911/top-250-korean-dramas-kdrama-dataset is used to create different function and to design dashboard using the MS Excel application. 
# Application of Different Function in Excel and Designing Dashboard 



# Text Functions

**LEN Functions**

  The **LEN functions**(length) is a function in excel categorized under text functions which returns the length of the specified string including the letters, numbers, characters, and all spaces. This function can be useful if we wish to get the length of a given text string as the number of characters in a given cell. To apply this function use the formula:
 
 **=LEN(text)**
 
For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =LEN(A2), would return _**14**_. This shows that there are 14 characters in the text **Move to Heaven**.

 <img width="363" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/ffbc7c53-b1c1-4bcc-ada4-e5499b4d9465"> <img width="306" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/369aa898-9e30-43da-9d1f-f4112a67ab3f">


**UPPER Function**

  The UPPER function in Excel allow you to convert all characters in a supplied text string to uppercase/capital letters. Using the formula:

 **=UPPER(text)**

 For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =UPPER(A2), would return _**MOVE TO HEAVEN**_. This shows that all the letter in the text is in uppercase. 


 <img width="477" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/49e5f590-c2d9-4642-9c6c-d1f7c6c6ae9b"> <img width="287" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/4710b0a6-cb9e-4c72-ada4-e3b1cb65531f">


**LOWER Function**

 The LOWER function in Excel is the reciprocal of UPPER Function. This allow you to convert all characters in a supplied text string to lowercase. Using the formula:

 **=LOWER(text)**

 For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =LOWER(A2), would return _**move to heaven**_. This shows that all the letter in the text is in lowercase. 

<img width="491" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/4d29d263-12e5-4f85-aaab-c91757ce6a4f"> <img width="317" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/9af2ac48-fa4a-43a8-ad8f-b76c9beb5f3f">


**LEFT Function**

  The LEFT Function is used to retrieve or extract a chosen amount of substring from a string counting from the left side of excel cell. To apply this function use the formula:

  **=LEFT(text,[number_of_characters])**

  Parameters

  text - The string that you wish to extract

  
  number of characters - Optional. It indicates the amount of of characters you want to extract starting from the left most part of string. If this parameter is omitted, only 1 characteris returned.

  For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =LEFT(A2,3), would return _**Mov**_. 3 count from the left of the text "Move to Heaven" is "Mov".
  

<img width="394" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/1303c461-3c61-43a7-838a-99d6c2d17f43"> <img width="458" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/c4c7cc19-7d42-4c8e-9371-48727a0aa584">


**RIGHT Function**

  The RIGHT Function is used to retrieve or extract a chosen amount of substring from a string counting from the right side of excel cell. To apply this function use the formula:

  **=RIGHT(text,[number_of_characters])**

  Parameters

  text - The string that you wish to extract 
  
  
  number of characters - Optional. It indicates the amount of of characters you want to extract starting from the right most part of string. If this parameter is omitted, only 1 characteris returned.

  For example, if the cell _**A2**_ contains the text _"Move to Heaven"_, the formula =RIGHT(A2,5), would return _**eaven**_. 3 count from the left of the text "Move to Heaven" is "eaven".
  
<img width="347" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/898e5ab9-a627-4300-9bba-eaf0a6115f93"> <img width="475" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/342d1ebb-b27e-457e-be31-730440b2bc9f"> 

	
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

For example, you want to  recommend K-Dramas whose ratings are 8.5 and above, so using IF function if the rating of the drama is above 8.5 it will show YES and if below 8.5 show NO.

<img width="876" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/e7fc3f75-1dc3-4bb2-bb7f-84cac819b12f"> 
<img width="320" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/5ca13fc3-a984-4946-9ea6-cd099e694186">

**AND Function**

The AND Function returns TRUE if all its arguments evaluate to TRUE, and returns FALSE if one or more arguments evaluate to FALSE. The AND function is often used together with the IF function. The yntax for this function is

**=AND(condition1,[condition2],...)**

For example, you want to recommend drama from the recommended ones but the drama should be 15+ - Teens 15 or older so using =AND(cell with age restriction,cell for recommended ones). If drama is within the set age show TRUE but if the drama is aboce show FALSE.

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

<img width="583" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/f0e462bc-b2e5-4037-a294-3b9544c80199"> <img width="300" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/1ce6d8cf-6a49-4ed4-b601-b04b1fc7ed39">



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

DAY,MONTH,YEAR Function

**DAY Function**

The DAY Function returns the day of the month as an integer in the range from 1 to the number of days in the current month or between 1-31. It can use to extract day in a cell.

SYNTAX

**=DAY(serial_number)**

**MONTH Function**

The MONTH Function extract the month from the given date as a number 1-12. 

SYNTAX

**=MONTH(serial_number)**

YEAR Function

The Excel YEAR Function returns the year component of a date as a 4 digit number.

SYNTAX

**=YEAR(serial_number)**

For example in the cell B2 the date stated is 14-May-21. To know the year, month and day component  of the Date, use the syntax =YEAR(B2), =MONTH(B2), =DAY(B2) so the YEAR is 2021, the MONTH is May, and the DAY is 14.

<img width="219" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/c0375fc5-888e-4c73-875a-308be6bfcf31">

<img width="304" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/5a027758-6182-457e-8e4b-8741970f0f25"> <img width="308" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/f430ab03-2033-403a-80ca-4255360ec070"> <img width="310" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/585fbaac-e831-4c21-8ac8-7253f63eef8f">


HOUR,MINUTE,SECOND Function

HOUR Function 

The HOUR Function returns the hour component of a time as a number 0 23. 

SYNTAX

**=HOUR(serial_number)**

MINUTE Function

The MINUTE Function extract the minute component of a time as a number between 0 59.

SYNTAX

=MINUTE(serial_number)

SECOND Function

The SECOND Function extract the minute component of a time as a number between 0 59.

 For example in cell B2 the duration of the drama is 00:52:00. If where going to find the HOUR, MINUTE, and SECOND  we will use the syntax =HOUR(B2), =MINUTE(B2) and =SECOND(B2). Since the duration of the drama is within 52 minutes then the HOUR will be 0, The minutes will be 52 and the second will be 0. 
 
<img width="358" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/c8eff96d-682f-4ba3-8989-ce5f5a0a2f7c">
<img width="285" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/d21411cd-c1e1-4f60-99e0-deecb4e95a35"> <img width="311" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/33812f7e-cffc-48c8-8197-c9ddeadc4530"> <img width="284" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/701bdca0-f8aa-4bc5-b45b-6a1004a7c51f">

**DAYS Function**

The DAYS Function returns the day of the month as an integer in the range from 1 to the number of days in the current month or between 1-31. It can use to extract day in a cell.

SYNTAX

**=DAYS(serial_number)**

For example, we want to find the number of days the drama is aired until it end. In cell B3 the date end on 23-Sep-20 while it aired on 29-Jul-20. Using the syntax =DAYS(B2,C2) the number of days the drama is releae until end is 56 days.

<img width="459" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/19e0572c-1dca-4aa6-92ce-4413e533d0b7"> <img width="303" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/b95a5aef-ccf3-4469-9876-b65bf3887b07">


TIME Function

The TIME Function is a built in function that allows you to create a time with individual hour, minute, and second component.

SYNTAX 

=TIME(hour,minute,second)

<img width="465" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/20702498-39a4-457a-95aa-b363f6e09da2"> <img width="278" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/d1dd842c-feaf-45b8-9761-d02fc5031728">

DATE Function

The DATE Function create a valid date from individual year,month, and day.

SYNTAX

=DATE(year,month,day)

<img width="512" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/2e0d8b3a-aa8f-46d6-ba45-1524c28cb0ff"> <img width="333" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/c4de750e-0035-41f9-988a-9069ef3721e0">




# Lookup Functions

LOOKUP functions 

The LOOKUP function returns a value from a range(one row or one column) or from an array.

SYNTAX

=LOOKUP(value, lookup_range, [result_range]

<img width="910" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/5bdc763b-1b94-47b6-a371-845db6aa5dfe"> <img width="441" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/7f3777e6-84ed-4269-bb70-bc9a60669f52">

**VLOOKUP Function**

The VLOOKUP function in Excel is a powerful function used to lookup data in a table organized vertically. It looks down the left column of a range to find a value.

SYNTAX 

**=VLOOKUP(value, table, index,[result_range])**

Parameters

value - The value to look for in the first column of a table.

table - The table from which to retrieve a value.

index - The column in the table from which to retrieve value. 

result_range - [optional] TRUE = approximate match (default). FALSE = exact match

<img width="808" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/69cd6fad-9c28-4ea3-97d9-1155e1b1c858"> <img width="382" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/11a2a36c-7e47-43f0-a648-33e48b076a22">


**MATCH Function**

The MATCH function searches for a specified item in a range of cells, and then returns the relative position of that item in the range.

SYNTAX

=MATCH(lookup_type, lookup_array, match_type)

<img width="917" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/f509f2c6-d146-4495-8855-11969d86e1e1"> <img width="316" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/3d7129db-f5ac-48ec-aa71-0ec992b421d5">

**INDIRECT Function**

The INDIRECT function in Excel is used to create a reference specified by a text string. It enables us to create references from cell values. This function is one of the lookup and reference functions in Excel. It is most used for building dynamic references for calculations and chart ranges.

Syntax

=INDIRECT( string_reference, [ref_style]

Parameters

string reference - a textual representation of a cell reference.

ref style - Optional. It is the reference style to use: either A1 or R1C1. If this parameter is omitted, it assumes that the ref_style is set to TRUE. 

<img width="861" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/220dd359-8996-47cc-a80b-a48fad1dec5b"> <img width="331" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/d457634d-e07b-4f6a-8f5b-c4ce8a13d73d">

ADDRESSS Function

The ADDRESS function is used to obtain the address of a cell in a worksheet, given specified row and column numbers. 

SYNTAX 

=ADDRESS(row,column,[ref_type],[ref_style],[sheet name])

Parameters

row_num - the row number to use in the cell address

col_num - the column number to use in the cell address

ref_type - Optional. It is the type of reference  to use. If this parameter is omitted, it assumes that the ref_style is set to 1.

ref_style - Optional. It is the reference  tyle to use: either A1 or R1C1. If tHthis parameter is omitted, it assumes that the ref_style is set to TRUE.

sheet_name - Optional. It is the name of the sheet to use in the cell address. If this parameter is omitted, then no sheet name is used in the cell address.

<img width="891" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/1aac4f5e-0e5e-4dbe-98df-927d08c73c22"> <img width="319" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/d6e4c2c1-8f1d-4edb-b50d-2abed9f8e52f">

# DASHBOARD

The detail in the dashboard below are from the data and ranking of korean drama from different year. We choose top 10 korean drama based on their ranking. The dashboard contain the title, synopsis, ranking, cast and their rating.

<img width="754" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/198180be-55ee-437b-88df-aaba63fb1a50">

Rank 1

Move to Heaven

<img width="777" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/6bdd1f44-7378-4b73-aed4-97f8c9f9ca5c">

Rank 2

Flower of Evil

<img width="824" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/760a158f-bffa-4251-96cd-2d9cb978be3b">

Rank 3

Hospital Playlist

<img width="807" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/9d703b4c-ee4a-435a-a47f-570b6f326842">

Rank 4

Hospital Playlist 2

<img width="813" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/5f000232-581a-4db7-9994-ec979e89f34e">

Rank 5

My Mister

<img width="774" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/2dc1cc3c-08b9-46bd-a33d-f3b597c2b9ce">

Rank 6

Reply 1988

<img width="813" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/0c380920-87fd-49e8-8518-6d80e4b4b353">

Rank 7

Weak Hero Class 1

<img width="809" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/9f2aaddb-6ce8-4db5-a0b2-63f0904a1113">

Rank 8

Prison Playbook

<img width="907" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/305b1116-7e05-4802-a2a2-2f8fffaecba8">

Rank 9

Alchemy of Souls

<img width="902" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/7aed9aa8-0087-4e92-b826-a26b7da1b951">

Rank 10

Extraordinary Attorney Woo

<img width="905" alt="image" src="https://github.com/Kzlyn000/Movies-Datasets/assets/144194143/3a103c1f-deb3-47a4-be75-e12a578c73cb">















         

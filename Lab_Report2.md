# CSE15L Week 4 Lab Report
This is the Lab Report for Week 4 of CSE15L, due on the 24th of April, 2022. In this lab we were debugging and improving a program, by making a total of 3 changes to it.

## Original Code:

<img width="849" alt="Screen Shot 2022-04-24 at 1 58 18 PM" src="https://user-images.githubusercontent.com/103228539/164996343-1388cd3e-44bb-446c-beae-2dce7fa0865d.png">


## First Change

<img width="1190" alt="Screen Shot 2022-04-24 at 7 57 33 PM" src="https://user-images.githubusercontent.com/103228539/165013748-4b571dc2-a65e-44b3-a065-22630079257f.png">

The first thing noticed when we did the tests is that if you had an line after the links that was empty, it will cause the code to break. So the first change we made was a simple ```if-statment``` that would indicate that if the open bracket does not exist(```if(openBracket ==-1)```), then the function would ```break```. In which then after that the code ran without error.


## Second Change

<img width="1192" alt="Screen Shot 2022-04-24 at 7 58 37 PM" src="https://user-images.githubusercontent.com/103228539/165013828-f66222dd-7a71-4349-add4-e8ddcc9de2c5.png">

Based on our first test, we were then curious as to what would happen if instead of an empty line, we had a line with just a ```[``` on it. Of which then we discovered that this will also cause the code to break. So our second change was a simply another ```if-statment```, which this time would indicate if the closed bracket does not exist(```if(closeBracket ==-1)```), then the function would ```break```.


## Third Change

<img width="1191" alt="Screen Shot 2022-04-24 at 8 00 24 PM" src="https://user-images.githubusercontent.com/103228539/165013791-81fbd1b7-305f-42d8-88dd-bafbcea79f5b.png">

Recognizing that there was a pattern happening, we decided that our third test to be with missing parentheses; and as we expected, the code would break if there was missing parentheses. Therefore, our final fix would be to add both ```if-statments```: if the closed parentheses does not exist(```if(closeParen ==-1)```), or if the open parentheses does not exist(```if(openParen ==-1)```).

## Conclusion

This then concluded our 3rd CSE15L lab on the process and significance there was on debugging. It really was us a look in to the tediousness and length of time needed into getting a program to work.

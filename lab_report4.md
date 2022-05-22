# CSE15L Week 8 Lab Report
This is the Lab Report for Week 8 of CSE15L, due on the 22th of May, 2022. In this lab we were review another group's Markdown-Parse Repository.

### [Our Group's Markdown-Parse Repository](https://github.com/nxgao/markdown-parser-main)

### [Alternate Group's Markdown-Parse Repository](https://github.com/ehsly/markdown-parser)

## First Test

<img width="227" alt="Screen Shot 2022-05-22 at 1 23 44 AM" src="https://user-images.githubusercontent.com/103228539/169685661-e252d728-6d6b-4b21-bb65-836b1306dcb2.png">

The first thing noticed when we did the tests is that if you had an line after the links that was empty, it will cause the code to break. So the first change we made was a simple ```if-statment``` that would indicate that if the open bracket does not exist(```if(openBracket ==-1)```), then the function would ```break```. In which then after that the code ran without error.


## Second Test

<img width="317" alt="Screen Shot 2022-05-22 at 1 25 39 AM" src="https://user-images.githubusercontent.com/103228539/169685729-7de52f66-18c8-417d-b46f-e92df50cf650.png">

Based on our first test, we were then curious as to what would happen if instead of an empty line, we had a line with just a ```[``` on it. Of which then we discovered that this will also cause the code to break. So our second change was a simply another ```if-statment```, which this time would indicate if the closed bracket does not exist(```if(closeBracket ==-1)```), then the function would ```break```.


## Third Test

<img width="666" alt="Screen Shot 2022-05-22 at 1 27 05 AM" src="https://user-images.githubusercontent.com/103228539/169685789-7bbc2e12-875a-471b-a51f-704f1d973171.png">

Recognizing that there was a pattern happening, we decided that our third test to be with missing parentheses; and as we expected, the code would break if there was missing parentheses. Therefore, our final fix would be to add both ```if-statments```: if the closed parentheses does not exist(```if(closeParen ==-1)```), or if the open parentheses does not exist(```if(openParen ==-1)```).


## Additional Questions



## Conclusion

This then concluded our 3rd CSE15L lab on the process and significance there was on debugging. It really was us a look in to the tediousness and length of time needed into getting a program to work.

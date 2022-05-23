# CSE15L Week 8 Lab Report
This is the Lab Report for Week 8 of CSE15L, due on the 22th of May, 2022. In this lab we were review another group's Markdown-Parse Repository.

### [Our Group's Markdown-Parse Repository](https://github.com/nxgao/markdown-parser-main)

### [Alternate Group's Markdown-Parse Repository](https://github.com/ehsly/markdown-parser)

## First Test

We are inputing this code into Markdown:

<img width="227" alt="Screen Shot 2022-05-22 at 1 23 44 AM" src="https://user-images.githubusercontent.com/103228539/169685661-e252d728-6d6b-4b21-bb65-836b1306dcb2.png">

This code should produce: 
[url.com, `google.com, google.com, ucsd.edu]

Our Markdown-Parser had the same result. However, the other group's Markdown produced something different: 

<img width="899" alt="Screen Shot 2022-05-22 at 1 19 05 PM" src="https://user-images.githubusercontent.com/103228539/169714211-6c6fefd8-46c7-42f3-9e4b-604e28731050.png">

## Second Test

We are inputing this code into Markdown:

<img width="317" alt="Screen Shot 2022-05-22 at 1 25 39 AM" src="https://user-images.githubusercontent.com/103228539/169685729-7de52f66-18c8-417d-b46f-e92df50cf650.png">

This code should produce: [a.com, b.com, a.com((, example.com]

However, this time neither of our codes would produce the right outcome:

<img width="816" alt="Screen Shot 2022-05-22 at 5 43 09 PM" src="https://user-images.githubusercontent.com/103228539/169723907-0d98d8b5-fe9c-41a5-990c-7b09f04c4aa2.png">

<img width="708" alt="Screen Shot 2022-05-22 at 5 41 58 PM" src="https://user-images.githubusercontent.com/103228539/169723883-c980b3ca-ec37-40e3-bd62-15586381ce5d.png">

## Third Test

We are inputing this code into Markdown:

<img width="666" alt="Screen Shot 2022-05-22 at 1 27 05 AM" src="https://user-images.githubusercontent.com/103228539/169685789-7bbc2e12-875a-471b-a51f-704f1d973171.png">

This code should produce this result: [https://www.twitter.com, https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://cse.ucsd.edu/]

The resulting output from both our and the other group's Markdown-Parser were the same, but nonetheless wrong: [This Result](https://github.com/nxgao/cse15l-lab-reports/blob/main/first-code-result)

## Additional Questions

1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.
 - 

2. Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.
 - 

3. Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.
 - 

## Conclusion

This then concluded our 7th CSE15L lab on the reviewing another group's cod ein comparison to ours.

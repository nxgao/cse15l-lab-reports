# CSE15L Week 10 Lab Report
This is the Lab Report for Week 10 of CSE15L, due on the 5th of June, 2022. In this lab we were experimented with the many tests provided for usunder the test-files/ folder, and comparing the results.

## Beginning Process

We were first given access to this [github](https://github.com/nidhidhamnani/markdown-parser), in which we used `git clone` to put it into our `ieng`. We then ran the `make test` command, and although most there were some failures, all of it compiled. 

Now to test the 652 tests in the `test-files` folder we ran the `time bash script.sh`, where , as expected, most of the results were just `[]`. Then, to make it more create as to which test each result came from, in `script.sh` we added the line `echo "Test file name is: ${file}"` where now if we ran it would also print the title of the file along with the result. 

However, printing in the terminal was inefficient due to how long the output was, so we then inputted the command `bash script.sh > results.txt`, which would make the file `results.txt` where it would print the entire output there.

Then use `cp -r cse15lsp22-markdown-parser/test-files my-markdown-parser/` and `cp cse15lsp22-markdown-parser/script.sh my-markdown-parser/` to copy the files from the repository you just copied from that day's lab into your own repository. Then run `bash script.sh > results.txt` again, but in your own respository to get the results of the test files when it runes on your Markdown File.

Finally , use the command `$ vimdiff my-markdown-parser/results.txt cse15lsp22-markdown-parser/results.txt` to use vimdiff to compare the 2 result files to see the differences between the results.

## Vimdiff Results

<img width="997" alt="vimdiff1" src="https://user-images.githubusercontent.com/103228539/171571934-83db8447-2827-46c8-9b78-27f626b96d8c.png">

<img width="993" alt="vimdiff2" src="https://user-images.githubusercontent.com/103228539/171571954-c6f86009-9887-4426-85f5-fa2cb5cb7156.png">

<img width="994" alt="vimdiff3" src="https://user-images.githubusercontent.com/103228539/171571967-d3921793-5645-4dda-8101-24374f3a4060.png">

<img width="975" alt="vimdiff4" src="https://user-images.githubusercontent.com/103228539/171571976-52e3e408-b1ad-4904-9ba3-f077f7f1d10e.png">


## Conclusion

This then concluded our 9th CSE15L lab on using a script to run many files and comparing two implementations


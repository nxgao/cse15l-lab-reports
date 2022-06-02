# CSE15L Week 10 Lab Report
This is the Lab Report for Week 10 of CSE15L, due on the 5th of June, 2022. In this lab we were experimented with the many tests provided for usunder the test-files/ folder, and comparing the results.

## Beginning Process

We were first given access to this [github](https://github.com/nidhidhamnani/markdown-parser), in which we used `git clone` to put it into our `ieng`. We then ran the `make test` command, and although most there were some failures, all of it compiled. 

Now to test the 652 tests in the `test-files` folder we ran the `time bash script.sh`, where , as expected, most of the results were just `[]`. Then, to make it more create as to which test each result came from, in `script.sh` we added the line `echo "Test file name is: ${file}"` where now if we ran it would also print the title of the file along with the result. 

However, printing in the terminal was inefficient due to how long the output was, so we then inputted the command `bash script.sh > results.txt`, which would make the file `results.txt` where it would print the entire output there.

Then use `cp -r cse15lsp22-markdown-parser/test-files my-markdown-parser/` and `cp cse15lsp22-markdown-parser/script.sh my-markdown-parser/` to copy the files from the repository you just copied from that day's lab into your own repository. Then run `bash script.sh > results.txt` again, but in your own respository to get the results of the test files when it runes on your Markdown File.

Finally , use the command `$ vimdiff my-markdown-parser/results.txt cse15lsp22-markdown-parser/results.txt` to use vimdiff to compare the 2 result files to see the differences between the results.

## Vimdiff 

### Here are the [Results](https://github.com/nxgao/cse15l-lab-reports/blob/main/vimdiff_results.md)

A common pattern that can be seen throughout the results is that my Markdown-Parser had extra results when the downloaded Markdown-Parser had just `[]`. 

<img width="960" alt="vimdiff2 0" src="https://user-images.githubusercontent.com/103228539/171693906-e559caa7-90f1-451f-9e17-28ed2c10d516.png">


## Conclusion

This then concluded our 9th CSE15L lab on using a script to run many files and comparing two implementations


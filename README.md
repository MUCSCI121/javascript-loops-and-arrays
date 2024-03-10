# JavaScript Arrays, Loops, and Conditionals Practice
We are going to practice creating, indexing, and modifying JavaScript arrays while loops in order to modify a web page.  All of the work will be completed in the `script.js` and `index.html` files.

## Web page setup
1. Update the `index.html` file so that it references the `script.js` file.

## Arrays
All code will be completed in the `script.js` file.

### Practice 1
1. Create an array variable and initialize it to an empty array.
2. Add the value `"test"` to the array by using the `push()` function on the array.
3. Add the value `"tested"` to the array by using the `push()` function on the array.
4. Add the value `"tester"` to the array by using the `push()` function on the array.
5. Write the length of the array variable to the console output using the `console.log()` function.
6. Write the last value of the array to the console output using the `console.log()` function.  For a challenge, use the array length as part of a calculation to get the index that should be used to get the last value of the array.  Don't forget, what number do indexes start with in arrays?
7. Write the first value of the array to the console output using the `console.log()` function.

### Practice 2
1. Create a new array variable and initialize it to the values `1`, `3`, `5`, `8`.
2. Create a variable called `count` and set the value to `0`.
3. Create a `while` loop that will iterate over each of the array indexes.
4. Set the conditional check inside the `while` loop so that while `count` is less than the length of the array, the `while` look continues to execute.
5. Inside the loop, write the value of the array at that index of `count` to the console using `console.log()`.
6. Inside the loop, after the `console.log()` statement, set the `count` variable value to be increased be `1`.

## References
* [Arrays](https://www.w3schools.com/js/js_arrays.asp)
* [while and do/while loops](https://www.w3schools.com/js/js_loop_while.asp)


## Configuration

### GitDoc

GitDoc is a great extension to automatically commit and push changes into the repository. For developers who are just getting started with web development, configuring this extension to automatically save their changes can make the introduction into git version control a much less intimidating experience. Because the extension cannot be configured by default to automatically push the changes up to the repository, users will need to update the settings the first time they launch project in Codespaces.

1. On the right-hand side of the `Codespaces` editor, click on the `Extensions` icon.

![image](.assets/extensionIcon.jpg) 

2. Once the `Extensions` sidebar expands, click on the gear icon in the `GitDoc` extension card and then select `Extension Settings` from the menu.

![image](.assets/extensionSettingClick.jpg)

3. Update the `Auto Commit Delay` to the number of milliseconds you would like the plugin wait before checking for file changes. The number is in milliseconds, 1 second = 1000 milliseconds. I've found the 5000 is a good number to use.

![image](.assets/autoCommitDelay.jpg) 

4. (Optional) Change the `Commit Validation Level` to `none`. This will allow all changes, even those that might include code which has errors in it, to be saved.

![image](.assets/commitValidation.jpg) 

5. Check the box associated with `Enabled` under the `Commit Validation Level` section.

6. Refresh the page in your browser so that the settings can be applied to the editor.

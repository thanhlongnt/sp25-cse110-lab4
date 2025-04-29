1. line 12 will output `3`. this happens because `i` is the index used for the for loop, but it is declared with a `var`

2. line 13 outputs `150`, which is the last discounted price calculated. this happens beacuse `discountedPrice` is declared as a `var` type

3. line 14 outputs `150`. This is since `finalPrice` is also declared as a `var` type.

4. this function returns `[ 50, 100, 150 ]` since `discountPrices([100, 200, 300], 0.5)` gives the original prices `[100, 200, 300]` a `0.5 * 100 %` discount. 

5. this results in an error, since `i` is declaired as a `let` and its scope is limited to the for loop.

6. this results in an error, since `discountedPrice` is declared as a `let` and its scope is limited to the for loop

7. line 14 outputs `150`. This happens because `finalPrice` is declared as a `let` and is still within the function scope

8. This function will still work and returns `[50, 100, 150]`

9. line 11 will result in an error, as the index of the for loop is limited to the for loop.

10. line 12 will output 3, as `length` is declared as a `const` and `console.log` is within the function scope

11. this will do the same as the first two versions. // investigate why we can append to the const variable

12. for the student object, we can use the following notation:
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]

13. After running the script, we get the following output:
    a. 32
    b. 1
    c. 3
    d. 3null
    e. 4
    f. 0
    g. 3undefined
    h. NaN

14. After running the script, we get the following output:
a. true
b. false
c. true
d. false
e. false
f. true

15. == is loose typing
    === is strict typing

16. Code for this question is [here](part2-question16.js)

17. this code doubles the input array. 

18. code for this questions is [here](part2-question18.js)

19. output for this code is :
1
4
3
2
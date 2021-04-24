1. values added: 20
2. final result: 20
3. values added: 20
4. Runtime error. The print statement on line thirteen is not in the block containing 'result'. Since 'result' is declared with let, it has block-level scope.
5. runtime error; const variable 'result' cannot be re-initialized.
6. runtime error. The print statement on line thirteen is not in the block containing 'result'. Since 'result' is declared with const, it has block-level scope.


1. '3' will be printed. 'i' has function-level scope, and this statement is included in the same function.
2. '150' will be printed. 'discountedPrice' has function-level scope, and this statement is included in the same function.
3. '150' will be printed. 'finalPrice' has function-level scope, and this statement is included in the same function.
4. [50, 100, 150] will be returned. 'discounted' is a list with function-level scope (declared with var). Returning 'discounted' will give this list
5. runtime error. variable 'i' has block-level scope. This statement is outside of the block 'i' was initialized.
6. runtime error. variable 'discountedPrice' has block-level scope. This statement is outside of the block 'discountedPrice' was initialized.
7. '150' will be printed, since 'finalPrice' has block-level scope, and this statement is located in the same block.
8. [50, 100, 150] will be returned. 'discounted' is a list with block-level scope (declared with let). Returning 'discounted' will give this list
9. Runtime error. Variable 'i' has block-level scope. This statement is outside of the block 'i' was initialized.
10. '3' is printed. 'length' is declared with const, and has block-level scope. This statement is included in the same block.
11. [50, 100, 150] will be returned. 'discounted' is a list with block-level scope (declared with const). Since 'discounted' is never reassigned, 'discountPrice' will give this list without an exception.
12. A. student['name']
    B. student['Grad Year']
    C. student['greeting']()
    D. student['Favorite Teacher']['name']
    E. student['courseLoad'][0]
13. A. '32'
    B. 1
    C. 3
    D. '3null'
    E. 4
    F. 0
    G. '3undefined'
    H. NaN
14. A. true
    B. false
    C. true
    D. false
    E. false
    F. true
15. == is a non-strict equality comparison. In other words, type-conversion is applied to our operands prior to comparison. === is a strict quality comparison; type conversion is not applied to our operands before comparing. Non-strict equality comparison should be used to check for equality regardless of type, whereas strict equality comparison should be used to check for value and type equivalence.
17. [2, 4, 6] will be returned. The function 'doSomething' is passed as a callback to 'modifyArray', which is used to multiply each element in the list [1, 2, 3] by a factor of 2. As a result, 'modifyArray' can execute 'doSomething' on these elements while our program continues asynchronously
18. 
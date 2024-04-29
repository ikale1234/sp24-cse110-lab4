# Part 2

### 1.
Line 12 will print '2' because the input length of prices is 3, and i is the for loop counter
that iterates ober prices length. Since using var, scope of i is whole function.

### 2.
Line 13 will print '150' because after the loop, discountedPrice represents last version created
in the loop, which would be 300 * (0.5), and it is valid since var is used.

### 3.
Line 14 will print '150' again since finalPrice is declared at beginning of function, and used right after discountedPrice
to round the value.

### 4. 
function will return [50, 100, 150] because each of the items in original prices parameter is cut in half,
and added to the "discounted" list. discounted is declared at beginning of function.

### 5.
This will cause an error as 'i' is declared in a for loop block, therefore making it only accessible within
that block. line 12 is not in that block.

### 6.
Error for same reason as #5.

### 7.
Line 14 prints '150' since let variable is declared at beginning of function (same reaasoning as #3).

### 8.
function returns [50, 100, 150] (same as #4). Since all variables have different names and no errors happen
functionality will be same as #4

### 9.
Error due to the const violations occuring in the for loop (lines 6 - 9). Line 11 is never reached.

### 10.
Error due to the const violations occuring in the for loop (lines 6 - 9). Line 12 is never reached.

### 11.
Error due to the const violations occuring in the for loop (lines 6 - 9). Line 14 is never reached.

### 12.
A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]

### 13. 
A. '32', because + concatenates since string is detected
B. 1, since - is only a math operation, and '3' can be converted to make sense
C. 3, null converted to 0 since mathematical operation is implied (3 + ...)
D. '3null', null converted to 'null' because string concatenation is implied.
E. 4, true is converted to 1 (bools can be 0, 1) since mathematical operation is implied (... + 3)
F. 0, false and null can both be converted to numeric (0 and 0), so because of this the + operator is used as
a plus, since that is the only thing that makes sense in this context.
G. '3undefined', same reason as D
H. NaN, using - must mean doing math, and undefined will be NaN in every situation, and
any operation on NaN is NaN.

### 14.
A. true, since diff types, strings become nums and 2 > 1
B. false, since both strings, alphabet comparison happens, and '1' > '2'
C. true, same reason as A, 1 == 1
D. false, === means no type conversion
E. false, true = 1 and 1 != 2
F. true, Boolean(2) = true, and true = true

### 15.
== is the loose equality operator, which allows for types to change in order to fit the comparison context naturally. === however, is strict, and does not allow for type coersion, and will return false for any two differing types.

### 16.
Code in part2-question16.js




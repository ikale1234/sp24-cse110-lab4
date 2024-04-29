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



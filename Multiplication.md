# Multiplication

Scenario:Result overflow
Given: The calculator is on
When:I type "first number" and "multiply" and "second number" and "equal "
Then:I see "out of range message "as result

Scenario:signs of number
Given: The calculator is on
When:I type "first number" and "multiply" and "second number" and "equal "
Then: I see "mutiplied number"+ve if both number of same signs -ve if both number of different signs

Scenario: multiplication by 0
Given: The calculator is on
When:I type "number" and "multiply" and "0" and "equal "
Then:I see the "0" as result

Scenario:multiplication by 1
Given: The calculator is on
When:I type "number" and "multiply" and "0" and "equal "
Then:I see "same number" as result

Scenario:Decimal value multiplication
Given: The calculator is on
When:I type "first decimal number" and "multiply" and "second decimal number" and "equal "
Then:I see "decimal multiplied number" as result

Scenario:irrational value multiplication
Given: The calculator is on
When: I type "first irrational number" and "multiply" and "second irrational number" and "equal "
Then: I see "multiplied number" as result

Scenario:rational value multiplication
Given: The calculator is on
When: I type "first rational number" and "multiply" and "second rational number" and "equal 
Then:I see "multiplied number" as result

Scenario:simple multiplication
Given: The calculator is on
When: I type "first  number" and "multiply" and "second number" and "equal 
Then:I see "multiplied number" as result

Scenario:decimal and integer multiplication
Given: The calculator is on
When: I type "first integer number" and "multiply" and "second decimal number" and "equal 
Then: I see "decimal multiplied number" as result

Scenario:more then two numbers multiplication
Given:The calculator is on
When: I type all the operand and put "multiply" in between each operand
Then:I see " multiple of all number" as result

Scenario:complex number multiplication
Given:The calculator is on
When: I type "first complex number" and "multiply" and "second complex number" and "equal 
Then: 

Scenario:range of operand exceed allowed limit
Given:The calculator is on
When:
Then:

Scenario:pressing multiply button multiple times
Given: The calculator is on
When:I type "first number" and "multiply" and "multiply" and  "second number" and "equal"
Then:I see "multiplied numbered" as result as it will considered all override multiply as single multiply operator or it will display error message

Scenario:interleaving operators
Given: The calculator is on
When:I type "first number" and "multiply" and "plus" and "minus"  and  "second number"
Then:it will show error message or take final operator as operator and do the function

Scenario:Decimal value capping
Given: The calculator is on
When::I type "first decimal number" and "multiply" and  "second number" and "equal"
Then:I see "multiplied number" as result but only two/three digit after decimal

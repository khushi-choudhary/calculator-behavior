# Addition
Scenario: Addition of two positive numbers
Given: The Calulator is turned on
When: I type"first positive number" and "plus"and "second Positive number" and "equals"
Then: I see the "added number" as the result

Scenario: Addition of two negative numbers
Given: The Calulator is turned on
When:  I type "negative number"and "plus" and "negative number" and "equals"
Then: I see the "added number" as the result sign can we negative or positive

Scenario: Addition of fractions
Given: The Calulator is turned on
When:  I type "fraction number" and "plus" and "fraction number" and "equals"
Then: I see the "added number in decimal or fraction" as result

Scenario: Addition of positive and negative number
Given: The Calulator is turned on
When:  I type "positive number" and "plus" and "negative number" and "equals"
Then: "added number and its sign depened on sign of biggest number" as result

Scenario: Addition of decimals
Given: The Calulator is turned on
When: I type "one decmical number" and  "plus" "another decimal number " and "equal"
Then: I see the "added number " as the result and the result will be in decimal

Scenario: Typing operator more then once
Given: The Calulator is turned on
When: I type "number1" and "plus" and other operator and "number2" and "equal"
Then: display error message or take final operator as operator and do the operation

Scenario: Addition of more than 2 numbers
Given: The Calulator is turned on
When: type all the operand and put "plus" sign between operand
Then: I see addition of all  the provided number

Scenario: Adding numbers where the result goes out of range
Given: The Calulator is turned on
When: I type "Large number" and "plus" and "large number" and "equal "
Then: it will display "Number is too large" and out of range as message

Scenario:6+* is provided as input
Given: The Calulator is turned on
When:  i type "first no." and "plus" and  "mul" and "equal
Then: syntax error or we take second operand same as first and do the operation

Scenario: Identify operation
Given: The Calulator is turned on
When: operand will entered
Then: it will able to identify the operand
Scenario: Converse operation
Given: The Calulator is turned on
When: I type "first number" and "plus" and "second number" and "equal"
Then: i see result as "second num" and "plus" and then "first number"

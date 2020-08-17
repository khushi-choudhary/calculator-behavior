# Addition

Scenario: Addition of two positive numbers
Given: The Calculator is turned on
When: I type"first positive number" and "plus"and "second Positive number" and "equals"
Then: I see the "added number" as the result

Scenario: Addition of two negative numbers
Given: The Calculator is turned on
When:  I type "negative number"and "plus" and "negative number" and "equals"
Then: I see the "added number" as the result sign can we negative or positive

Scenario: Addition of fractions
Given: The Calculator is turned on
When:  I type "fraction number" and "plus" and "fraction number" and "equals"
Then: I see the "added number in decimal or fraction form" as result

Scenario: Addition of positive and negative number
Given: The Calculator is turned on
When:  I type "positive number" and "plus" and "negative number" and "equals"
Then: I see "added number" as result 

Scenario: Addition of decimals
Given: The Calculator is turned on
When: I type "one decimal number" and  "plus" and "another decimal number " and "equal"
Then: I see the "added number " as the result and the result will be in decimal

Scenario: Typing operator more then once
Given: The Calculator is turned on
When: I type "number1" and "plus" and other operator and "number2" and "equal"
Then: display error message or take final operator as operator and do the operation

Scenario: Addition of more than 2 numbers
Given: The Calculator is turned on
When: type all the operand and put "plus" sign between operand
Then: I see addition of all  the provided number

Scenario: Adding numbers where the result goes out of range
Given: The Calculator is turned on
When: I type "Large number" and "plus" and "large number" and "equal "
Then: it will display "Number is too large" and out of range as message

Scenario:6+* is provided as input
Given: The Calculator is turned on
When: I type "first number" and "plus" and  "multiply" and "equal"
Then: syntax error or we take second operand same as first and do the operation

Scenario: Identify operation
Given: The Calculator is turned on
When: operand will entered
Then: it will able to identify the operand

Scenario: Converse operation
Given: The Calculator is turned on
When: I type "first number" and "plus" and "second number" and "equal"
Then: I see result as "second number" and "plus" and then "first number"

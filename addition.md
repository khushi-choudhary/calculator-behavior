
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
 Then: I see the "added number in decimal or fraction" as result.
  
  Scenario: Addition of positive and negative number
  Given: The Calulator is turned on
  When:  I type "positive number" and "plus" and "negative number" and "equals"
  Then: I see the "added number and it's sign depened on sign of biggest number" as the result 

  Scenario: Addition of decimals 
  Given: The Calulator is turned on
  When: I type "one decmical number" and  "plus" "another decimal number " and "equal"
  Then: I see the "added number " as the result and the result will be in decimal.
  
  Scenario: Typing operator more then once
  Given: The Calulator is turned on
  When: I type "first number" and "plus" and other operator and "second number" and "equal"
  Then: it will display error message or it will take final opertor as opertor and do the operation 
  
  Scenario: Addition of more than 2 numbers
  Given: The Calulator is turned on
  When: I type "first  number" and "plus" and "second number" and "plus" and "third number" and so on and type "equal"
  Then: I see addition of all  the provided number.
  
  Scenario: Adding numbers where the result goes out of range
  Given: The Calulator is turned on
  When: I type "first number" and "plus" and "second number" and "equal " but the result is too big
  Then: it will display "Number is too large" and out of range as msg 
  
  Scenario:6+* is provided as input
  Given: The Calulator is turned on
  When:  i type "first no." and "plus" and  "mul" and "equal
  Then: syntax error or we can take second operand same as first and do the operation and give result.

  Scenario: Identify operation
  Given: The Calulator is turned on
  When: operand will entered 
  Then: it will able to identify the operand
  
  Scenario: Converse operation
  Given: The Calulator is turned on
  When: I type "first number" and "plus" and "second number" and "equal"
  Then: i see result as "second num" and "plus" and then "first number"

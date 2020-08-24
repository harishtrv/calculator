# Addition

## Scenario: Addition of two positive numbers

Given The calculator is on.  
When I type in "positive number" And I press "plus"
And I type in "positive number" And I press "equals".  
Then I see the "added number" as the result.

## Scenario: Addition of two negative numbers

Given The calculator is on.  
When I type in "negative number" And I press "plus"
And I type in "negative number" And I press "equals".  
Then I see the "added number" as the result with negative sign.

## Scenario: Addition of positive number and negative number

Given The calculator is on.  
When I type in "negative number" And I press "plus"
And I type in "positive number" And I press "equals".  
Then I see the "subtracted number" as the result with sign of bigger number.

## Scenario: Entering signs without brackets

Given The calculator is on.  
When I type in "signs without brackets" like +- or -+ etc
Then I see the "Invalid sign message" as the result.

## Scenario: Addition of two numbers with result going out of range

Given The calculator is on.  
When I type in "positive number" And I press "plus"
And I type in "positive number" And I press "equals" and result going out of range.  
Then I see the "out of range message" as the result.

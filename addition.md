# Addition

Scenario: Addition of two positive numbers
   Given The calculator is turned on
   When I type in "positive number
      And I press "plus"
      And I type in "positive number"
      And I press "equals"
   Then I see the "added number" as the result

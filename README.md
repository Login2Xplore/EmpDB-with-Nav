# EmpDB-with-Nav

Provides easy navigation to the employee form: Has following buttons on the employee form page. The first row is of ‘Control’ buttons and the second row is of ‘Navigation’ buttons: 
     [New]        [Save]         [Edit]         [Change]    [Reset]
         [First]         [Prev]         [Next]         [Last]  

Whenever the navigation buttons are enabled (except for when [Save] and [Change] are enabled) the behavior of navigation will be as follows:
 - Clicking on [First] will display first record and will enable [Next] and [Last] and disable [Prev] and [First]
 - Clicking on [Last] should be opposite to the above step. 
 - Clicking on [Prev] will display the previous record and should enable all four navigation buttons. If it's the first record should disable [First] and [Prev].
 - Clicking on [Next] will behave just the reverse of the above step.

If [Save] and [Change] are enabled the navigation buttons must all be disabled. 

1.On page load, displays last record and on [Reset] click current record is displayed(all form fields disabled) 

2.Clicking on [New] will enable all form fields and move the cursor to the first field i.e. empID. It will also enable [Save] and [Reset] buttons.

3.Clicking on [Reset] will go back to step-1.

4.Clicking on [Save] will save the new record after all validations and go back to step-1.

5.Click on [Edit] will enable all form fields except empID and move the cursor to empName for editing. 

6.Clicking on [Reset] will go back to step-1.

7.Clicking on [Change] will update the current record after all validations and go back to step-1.

![](/public_html/images/Nav-Load.png)
![](/public_html/images/Nav-New.png)
![](/public_html/images/Nav-Reset.png)
![](/public_html/images/Nav-Edit.png)

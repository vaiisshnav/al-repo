<table><tr><td> <em>Assignment: </em> IS601 - Mini Project 2 - Burgers</td></tr>
<tr><td> <em>Student: </em> Akshitha Rao Annamaneni (aa3382)</td></tr>
<tr><td> <em>Generated: </em> 4/1/2023 5:38:37 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-mini-project-2-burgers/grade/aa3382" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch per the desired branch name below</li><li>Add the baseline files from the following link:&nbsp;<a href="https://gist.github.com/MattToegel/028db0e3fd2b20c1fb8e284b341292bb">https://gist.github.com/MattToegel/028db0e3fd2b20c1fb8e284b341292bb</a>&nbsp;</li><li>Put them into a subfolder in your repository folder (I called my folder BurgerMachine)</li><li>git add .</li><li>git commit -m "baseline files"</li><li>git push origin (name of desired branch below)</li><li>You can go to github and open the pull request for evidence capturing later (don't close/merge the pull request until you're done with the assignment)</li><li>Do the below tasks and fill in the below entries</li><ol><li>git add/commit after any significant changes to build up history</li></ol><li>Save the input and generate the submission markdown file (copy to clipboard or download the file)</li><li>Name it something relevant to the assignment if it's not named already</li><li>git add the submission file</li><li>git commit the submission file</li><li>git push the submission file</li><li>Complete the pull request to dev</li><li>Create a pull request from dev to prod</li><li>Go to the prod branch on github, navigate to the submission file</li><li>Paste that link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Code Changes - Add the calculate_cost() implementation </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of the updated method calculate_cost()</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225477893-eb91e1d0-b267-4690-92c7-b3f206508bcd.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Python code for caluclating the cost of burger<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225478450-66011196-0196-46d0-88eb-b0947bd8628c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>terminal output with calculated cost of burger in currency format<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225478999-0e625009-2b09-4688-b74d-569888ebaa7e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>handling currency format<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the approach to implementing the calculation</td></tr>
<tr><td> <em>Response:</em> <div style="line-height: 24px;"><div style="line-height: 24px;">in&nbsp;calculate_cost&nbsp;function we are checking if inprogress_burger is false we<br>are returning 0. If not false we loop through the items of inprogress_burger<br>and add the cost of each item to the total and return the<br>total value.</div>in while displaying the cost of burger which is stored in expected<br>varibale , it is formated to display the currency format where I am<br>adding "$" to the cost and converting it to float with 2 decimals<br>using ".2f"<br></div><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Exception Handling </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of adjusted code to handle exceptions</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225483781-674f6553-ba7c-42c5-82d0-c5cbce5bd1eb.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>code for all exceptions<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225480516-6ed440ef-d9d5-4b35-893c-5a77e8845175.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>OutofstockException for stage patty and normal flow of ordering burger.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225482113-de418c52-3c0b-4f51-a169-c2cda3efff2f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>NeedsCleaningException with where it prompts the user to type the word &#39;clean&#39; to<br>clean the machine; other words are ignored.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225482509-a61c1b02-8a18-4b0c-ad18-a76668adba6c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>InvalidChoiceExceptions for different stages <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225482996-1012503e-2a1b-486d-af40-26f4d97b7816.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>ExceededRemainingChoicesExceptions for different stages <br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225483199-abfde154-cf80-46e2-8da9-8908db355bec.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>InvalidPaymentException <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each exception handling process</td></tr>
<tr><td> <em>Response:</em> <p><span style="font-size: 13px;">OutOfStockException : while handling this exception it checks the quantity of<br>the item if the item is 0 it raises the&nbsp;</span><span style="font-size: 13px;">OutOfStockException and<br>stage where the item was out of stock.</span><div><span style="font-size: 13px;">NeedsCleaningException: if the all<br>utensils are used . It raises the&nbsp;</span><span style="font-size: 13px;">NeedsCleaningException when the user enters<br>input clean user can continue to order with regular flow.</span><span style="font-size: 13px;"><br></span></div><div><span style="font-size:<br>13px;">InvalidChoiceException: If user enter the option for each stage which are not displayed<br>in the terminal it raises the&nbsp;</span><span style="font-size: 13px;">InvalidChoiceException.</span><span style="font-size: 13px;"><br></span></div><div><span style="font-size: 13px;">ExceededRemainingChoicesException: if<br>user selects more than 3 options for patty or toppings. it raises&nbsp;</span><span style="font-size:<br>13px;">ExceededRemainingChoicesException.</span><span style="font-size: 13px;"><br></span></div><div><span style="font-size: 13px;">InvalidPaymentException: If user enter wrong currency format it raises<br>the&nbsp;</span><span style="font-size: 13px;">InvalidPaymentException.&nbsp;</span><span style="font-size: 13px;"><br></span></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Test Cases </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of test cases per the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484107-5bda9045-f957-4bfa-9c34-ad9f7d60a159.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 1<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484186-3dfd93f8-b8e6-408c-b43d-095fab641399.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484290-95b25020-feb0-4a5f-a483-d2da6265e702.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 3<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484422-9c1f8180-c89d-4d01-839f-779adbc39923.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 4<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484472-d999fe48-8d18-429b-93f2-81a3c9286a68.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 5<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484559-b5218519-ce46-4c71-a659-0744d5476871.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 6<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484655-f602d717-87f8-4135-8016-dd8a03209525.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test 7<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225484808-2e9d372f-d684-4daf-b593-e294bed1c71b.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test  8<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225485130-695d42f4-a86a-4932-864a-c16f00da643e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>pytest -rA<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each test case logic</td></tr>
<tr><td> <em>Response:</em> <p>Test 1 : -&nbsp; checking whether InvalidStageException is raised when we user selecting<br>the patty without selecting the bun.<div><br></div><div>Test 2 :-&nbsp; &nbsp;checking whether&nbsp;OutOfStockException&nbsp;is raised when patty<br>item quantity is 0. To test this we are editing the quantity&nbsp;of turkey<br>to 0.</div><div><br></div><div>Test 3:-&nbsp; checking whether&nbsp;OutOfStockException&nbsp;is raised when topping item quantity is 0. To<br>test this we are editing the quantity of&nbsp;&nbsp;Lettuce&nbsp;to 0.</div><div><br></div><div>Test 4:- checking whether&nbsp;ExceededRemainingChoicesException&nbsp;is raised<br>when user selects the more than three patties of different combination.</div><div><br></div><div>Test 5 :-<br>checking whether&nbsp;ExceededRemainingChoicesException&nbsp;is raised when user selects the more than three toppings of different<br>combination.</div><div><br></div><div>Test6 :-&nbsp; checking the cost of the burger in this testcase with where<br>we are performing assert of calculate_cost of burger with actual value. As currency<br>check format we are giving input with &quot;$&quot; and float value with 2<br>decimals.</div><div><br></div><div>Test 7:-&nbsp; performing assert with the total sales with sum of three different<br>burger costs.</div><div><br></div><div>Test 8: performing assert with total burgers with the number of orders.</div><div><br></div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add pull request for the assignment</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/Akshithara/IS601-004/pull/14">https://github.com/Akshithara/IS601-004/pull/14</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain any issues/difficulties or something you learned while doing this assignment</td></tr>
<tr><td> <em>Response:</em> <p>Faced difficulties in testing the currency format Where I am trying to pass<br>the regular integer without the float value.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of successful output</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/67438038/225487131-a597fdcb-8e90-416f-9b81-10b85cf672df.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>of successful program execution of 2 orders <br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-mini-project-2-burgers/grade/aa3382" target="_blank">Grading</a></td></tr></table>
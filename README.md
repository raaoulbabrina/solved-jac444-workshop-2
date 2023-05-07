Download Link: https://assignmentchef.com/product/solved-jac444-workshop-2
<br>
<strong>Description:</strong>

The following workshop lets you practice basic java coding techniques, creating classes, methods, using arrays.

<strong> </strong>

<strong>Task 1: </strong>

<strong> </strong>

The Canadian federal personal income tax is calculated based on filing status and taxable income. There are four filing statuses:

<ul>

 <li>single filers</li>

 <li>married filing jointly or qualified widow(er) married filing separately</li>

 <li>head of household.</li>

</ul>

The tax rates vary every year.

If you are, for example say, <em>single</em> with a taxable income of $10,000, the first $8,350 is taxed at 10% and the other $1,650 is taxed at 15%, so, your total tax is $1,082.50.




<strong><u>Design a class</u></strong> named <em>IncomeTax</em> to contain the following instance data fields (Chose the data fields types on your own):




<ol>

 <li>filingStatus: One of the four tax-filing statuses:

  <ul>

   <li>0—single filer</li>

   <li>1— married filing jointly or qualifying widow(er) 2—married filing separately</li>

   <li>3—head of household.</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Use the constants

  <ul>

   <li>SINGLE_FILER(0)</li>

   <li>MARRIED_JOINTLY_OR_QUALIFYING_WIDOW(ER) (1)</li>

   <li>MARRIED_SEPARATELY (2) HEAD_OF_HOUSEHOLD (3) to represent the statuses.</li>

  </ul></li>

</ol>




<ol start="3">

 <li>A double-dimension array (You decide the type of it) named <em>intervals</em>: Stores the tax intervals/ brackets for each filing status.</li>

 <li>A single-dimension array (You decide the type) named <em>rates</em>: Stores the tax rates for each interval.</li>

 <li>A variable <em>taxableIncome</em>: Stores the taxable income.</li>

</ol>




<ol start="6">

 <li>Provide the getter and setter methods for each data field and the <em>getIncomeTax()</em> method that returns the tax.</li>

 <li>Provide a no-arg constructor.</li>

 <li>Provide the overloaded constructor <em>IncomeTax(filingStatus, intervals, rates, taxableIncome)</em>.</li>

</ol>




Write a program that prompt the user with a simple menu system of three choices:

<ul>

 <li>Compute personal income Tax</li>

 <li>Print the tax tables for taxable incomes (with range)</li>

 <li>Exit</li>

</ul>




<ul>

 <li>With choice one your program should prompt the user to enter the filing status and taxable income and compute the tax.</li>

 <li>With choice two your program should use the IncomeTax class to print the 2001 and 2009 tax tables for taxable income from (ask the user to input the amount) to (ask the user to input the amount) with intervals of $1,000 for all four statuses.</li>

</ul>




The tax rates for the year 2001 and 2009 are given in Tables below.




<table width="697">

 <tbody>

  <tr>

   <td width="73"> </td>

   <td colspan="3" width="467">Table 1: 2001 Canadian Federal Personal Tax Rates</td>

   <td width="157"> </td>

  </tr>

  <tr>

   <td width="73">Tax Rate</td>

   <td width="143">Single</td>

   <td width="174">Married Filing Jointly or Qualifying Widow(er)</td>

   <td width="150">Married Filing Separately</td>

   <td width="157">Head of House Hold</td>

  </tr>

  <tr>

   <td width="73">15%</td>

   <td width="143">Up to – $27,050</td>

   <td width="174">Up to – $45,200</td>

   <td width="150">Up to $22,600</td>

   <td width="157">Up to – $36,250</td>

  </tr>

  <tr>

   <td width="73">27.5%</td>

   <td width="143">$27,051 – $65,550</td>

   <td width="174">$45,201 – $109,250</td>

   <td width="150">$22,601 – $54,625</td>

   <td width="157">$36,251 – $93,650</td>

  </tr>

  <tr>

   <td width="73">30.5%</td>

   <td width="143">$65,551-$136,750</td>

   <td width="174">$109,251 – $166,500</td>

   <td width="150">$54,626 – $83,250</td>

   <td width="157">$93,651 – $151,650</td>

  </tr>

  <tr>

   <td width="73">35.5%</td>

   <td width="143">$136,751-$297,350</td>

   <td width="174">$166,501 – $297,350</td>

   <td width="150">$83,251 – $148,675</td>

   <td width="157">$151,651 – $297,350</td>

  </tr>

  <tr>

   <td width="73">39.1%</td>

   <td width="143">$297,351 +</td>

   <td width="174">$297,351 +</td>

   <td width="150">$148,676+</td>

   <td width="157">$297,351+</td>

  </tr>

 </tbody>

</table>




<table width="697">

 <tbody>

  <tr>

   <td width="73"> </td>

   <td colspan="3" width="467">Table 2: 2009 Canadian Federal Personal Tax Rates</td>

   <td width="157"> </td>

  </tr>

  <tr>

   <td width="73">Marginal Tax Rate</td>

   <td width="143">Single</td>

   <td width="174">Married Filing Jointly or Qualifying Widow(er)</td>

   <td width="150">Married Filing Separately</td>

   <td width="157">Head of House Hold</td>

  </tr>

  <tr>

   <td width="73">10%</td>

   <td width="143">$0 – $8,350</td>

   <td width="174">$0 – $16,700</td>

   <td width="150">$0 – $8,350</td>

   <td width="157">$0 – $11,950</td>

  </tr>

  <tr>

   <td width="73">15%</td>

   <td width="143">$8,351 – $33,950</td>

   <td width="174">$16,701 – $67,900</td>

   <td width="150">$8,351 – $33,950</td>

   <td width="157">$11,951 – $45,500</td>

  </tr>

  <tr>

   <td width="73">25%</td>

   <td width="143">$33,951-$82,250</td>

   <td width="174">$67,901 – $137,050</td>

   <td width="150">$33,951 – $68,525</td>

   <td width="157">$45,501 – $117,450</td>

  </tr>

  <tr>

   <td width="73">28%</td>

   <td width="143">$82,251-$171,550</td>

   <td width="174">$137,051 – $208,850</td>

   <td width="150">$68,526 – $104,425</td>

   <td width="157">$117,451 – $190,200</td>

  </tr>

  <tr>

   <td width="73">33%</td>

   <td width="143">$171,551-$372,950</td>

   <td width="174">$208,851 – $372,950</td>

   <td width="150">$104,426 – $186,475</td>

   <td width="157">$190,201 – $372,950</td>

  </tr>

  <tr>

   <td width="73">35%</td>

   <td width="143">$372,951 +</td>

   <td width="174">$372,951 +</td>

   <td width="150">$186,476 +</td>

   <td width="157">$372,951 +</td>

  </tr>

 </tbody>

</table>




For each filing status there are six tax rates. Each rate is applied to a certain amount of taxable income. For example, of a taxable income of $400,000 for single filers, $8,350 is taxed at 10%, (33,950 – 8,350) at 15%, (82,250 – 33,950) at 25%, (171,550 – 82,250) at 28%, (372,950 – 171,550) at 33%, and (400,000 – 372,950) at 35%.
















<strong><em>Continue to the next page…. </em></strong>



















Possible output screen shots:

With choice 1:




<ul>

 <li>– single filer</li>

 <li>– married jointly or qualifying widow(er)</li>

 <li>– married separately</li>

 <li>– head of household)</li>

</ul>

Enter the filing status: 0

<sub>                                               </sub>Enter the Taxable Income: $20000

<sub>                                               </sub>Tax is: $2582.50




With choice 2:




<strong><em>Continue to the next page… </em></strong>




<table width="584">

 <tbody>

  <tr>

   <td width="584"> Enter the amount From: $50000Enter the amount To: $600002001 tax tables for taxable income from $50,000 to $60,000———————————————————————————-Taxable       Single      Married Joint       Married        Head ofIncome                          or Qualifying       Separate       a HouseWidow(er)———————————————————————————-50000        10368.75        8100.00          10925.00        9218.7551000        10643.75        8375.00          11200.00        9493.7552000        10918.75        8650.00          11475.00        9768.7553000        11193.75        8925.00          11750.00       10043.7554000        11468.75        9200.00          12025.00       10318.7555000        11743.75        9475.00          12311.25       10593.7556000        12018.75        9750.00          12616.25       10868.7557000        12293.75       10025.00          12921.25       11143.7558000        12568.75       10300.00          13226.25       11418.7559000        12843.75       10575.00          13531.25       11693.75 60000        13118.75       10850.00          13836.25       11968.75 2009 tax tables for taxable income from $50,000 to $60,000———————————————————————————Taxable       Single      Married Joint       Married        Head ofIncome                         or Qualifying       Separate       a HouseWidow(er)———————————————————————————50000         8687.50       11905.70           8687.50        7352.5051000         8937.50       12235.70           8937.50        7602.5052000         9187.50       12565.70           9187.50        7852.5053000         9437.50       12895.70           9437.50        8102.5054000         9687.50       13225.70           9687.50        8352.5055000         9937.50       13555.70           9937.50        8602.5056000        10187.50       13885.70          10187.50        8852.5057000        10437.50       14215.70          10437.50        9102.5058000        10687.50       14545.70          10687.50        9352.50</td>

  </tr>

 </tbody>

</table>

Possible UML diagram for the class IncomeTax <strong>(You can add more functionalities or properties/ attributes)</strong>




<table width="531">

 <tbody>

  <tr>

   <td width="531">IncomeTax</td>

  </tr>

  <tr>

   <td width="531">-filingStatus: int+SINGLE_FILER: int————————–+MARRIED_JOINTLY_OR_QUALIFYING_WIDOW(ER): int————————————————————————–+MARRIED_SEPARATELY: int————————————————————————–+HEAD_OF_HOUSEHOLD: int—————————————--intervals: int[][]-rates: double[]-taxableIncome: double+IncomeTax()+IncomeTax(filingStatus: int, Intervals: int[][], rates: double[], taxableIncome: double)+getFilingStatus(): int+setFilingStatus(status: int)+getIntervals(): int[][]+setIntervals(Intervals: int[][])+getRates(): int[]+setRates(rates: int[])+getTaxableIncome(): double+setTaxableIncome(taxableIncome: double)+getIncomeTax(): double</td>

  </tr>

 </tbody>

</table>
















<strong><em>Continue to the next page… </em></strong>

Workshop Header




/**********************************************

<strong>Workshop #  </strong>

<strong>Course:</strong><em>&lt;subject type&gt; – Semester </em>

<strong>Last Name:</strong><em>&lt;student last name&gt; </em>

<strong>First Name:</strong><em>&lt;student first name&gt; </em>

<strong>ID:</strong><em>&lt;student ID&gt; </em>

<strong>Section:</strong><em>&lt;section name&gt; </em>

<em>This assignment represents my own work in accordance with Seneca Academic Policy. </em>

<em>Signature </em>

<strong>Date:</strong><em>&lt;submission date&gt; </em>

**********************************************/




<strong> </strong>

Code Submission Criteria:

Please note that you should have:

<ul>

 <li>Appropriate indentation.</li>

 <li>Proper file structure</li>

 <li>Follow java naming convention</li>

 <li>Document all the classes properly</li>

 <li>Do Not have any debug/ useless code and/ or files in the assignment</li>

 <li>Do not have everything in the <em>main method</em>.</li>

 <li>Have a separate TestClass with the main method in it.</li>

 <li>Try and check your inputs if the user is not entering garbage inputs.</li>

</ul>




Deliverables and Important Notes:




<strong>All these deliverables are suppose to be uploaded on the blackboard once done. </strong>

<strong> </strong>

<ul>

 <li>You are supposed to create video/ record voice/ detailed document of your running solution.</li>

</ul>

<strong>(50%)</strong>

<ul>

 <li>Screen Video captured file should state your last name and id, like Ali_123456.mp4 (or whatever the extension of the file is)</li>

 <li>Record voice clip should also include a separate word file with the screen shots of your program’s output, state your last name and id, like Ali_123456.mp3 (or whatever the extension of the file is)</li>

 <li>Detailed document should include screen shots of your output, have your name and id on the top of the file and save the file with your last name and id, like Ali_123456.docx (or whatever the extension of the file is)</li>

 <li>A word/ text file which will reflect on learning of your concepts in this workshop. Also include the instructions on how to run your code.                                              <strong>(30%)</strong>

  <ul>

   <li>Should state your Full name and Id on the top of the file and save the file with your last name and id, like Ali_123456.txt</li>

  </ul></li>

 <li>Submission of working code.                                                                         <strong>(20%)</strong>

  <ul>

   <li>Make sure your follow the “<strong>Code Submission Criteria”</strong> mentioned above.</li>

   <li>You should zip your whole working project to a file named after your Last Name followed by the first 3 digits of your student ID. For example, zip.</li>

  </ul></li>

 <li>Your marks will be deducted according to what is missing from the above-mentioned submission details.</li>

 <li>Late submissions would result in additional 10% penalties for each day or part of it.</li>

 <li>Remember that you are encouraged to talk to each other, to the instructor, or to anyone else about any of the assignments, but the final solution may not be copied from any source.</li>

</ul>
























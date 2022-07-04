# C++ STL | Set 2 (pair)
## Easy 
<div class="problem-statement">
                <p></p><p><span style="font-size:20px">Implement different operations on&nbsp;pairs.<br>
<br>
<strong>Input:</strong><br>
The first line of input contains an integer <strong>T</strong> denoting the no of test cases . Then T test cases follow. The first line of input contains an integer <strong>Q</strong> denoting the no of queries . Then in the next line are <strong>Q</strong>&nbsp;space separated queries .<br>
A query can be of&nbsp;five&nbsp;types&nbsp;<br>
1. a s&nbsp;x y (Adds a pair with string s&nbsp;and values&nbsp;x,y to the vector A&nbsp;at the end )<br>
2. b (returns the size of the vector A)<br>
3. c (prints space separated values of each element of the vector of pairs A)<br>
4. d (sorts the pair's array with respect to the values x,y in ascending order)<br>
<br>
<br>
<strong>Output:</strong><br>
The output for each test case will&nbsp;&nbsp;be space separated integers denoting the results of each query .&nbsp;<br>
<br>
<strong>Constraints:</strong><br>
1&lt;=T&lt;=100<br>
1&lt;=Q&lt;=100<br>
<br>
<strong>Example:</strong></span></p>

<p><span style="font-size:20px"><strong>Input</strong><br>
2<br>
5<br>
a ga&nbsp;4 5 a ra&nbsp;1 2 a sh&nbsp;1 1 d c<br>
4<br>
a geeks 10 12 &nbsp;a code 11 11 b c<br>
<br>
<strong>Output</strong><br>
sh 1 1 ra 1 2 ga 4 5&nbsp;<br>
2 geeks 10 12 code 11 11</span></p>

<p><br>
<span style="font-size:20px"><strong>Explanation :<br>
For the first test case</strong><br>
There are five&nbsp;queries.&nbsp;Queries&nbsp;are&nbsp;performed in this order<br>
1. a ga 4 5 &nbsp; --&gt;&nbsp;vector contents {ga,4,5}&nbsp;<br>
2. a ra 1 2 &nbsp; &nbsp;--&gt;&nbsp;vector contents {ga,4,5}, {ra,1,2}<br>
3. a sh 1 1 &nbsp; &nbsp;--&gt;&nbsp;vector contents are {ga,4,5}, {ra,1,2}, {sh,1,1}<br>
4.&nbsp;d &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; --&gt; vector get sorted as {sh,1,1}, {ra,1,2}, {ga,4,5}<br>
5. c &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; --&gt;&nbsp;vector values printed as 'sh 1 1 ra 1 2 ga 4 5 '&nbsp;without quotes&nbsp;<br>
<br>
<strong>For the sec test case&nbsp;</strong><br>
There are four&nbsp;queries.&nbsp;Queries&nbsp;are&nbsp;performed in this order<br>
1. a geeks 10 12 --&gt;&nbsp;vector A has {geeks,10,12} &nbsp;<br>
2. a code&nbsp;11 11 &nbsp; --&gt;&nbsp;vector A has {geeks,10,12}, {code,11,11}<br>
3. b&nbsp; &nbsp; &nbsp; &nbsp;--&gt; prints the size of the vector A ie&nbsp;2<br>
4. c &nbsp; &nbsp; &nbsp; --&gt; prints the elements of the pair of vectors as 'geeks 10 12 code 11 11' without quotes.</span><br>
<br>
<br>
<span style="font-size:16px"><strong>Note:</strong>The <strong>Input/Output</strong> format and <strong>Example</strong> given are used for system's internal purpose, and should be used by a user for <strong>Expected Output</strong> only. As it is a function problem, hence a user should not read any input from stdin/console. The task is to complete the function specified, and not to write the full code.</span></p>
 <p></p>
            </div>
# C++ STL | Set 3 (map)
## Easy
<div class="problem-statement">
                <p></p><p><span style="font-size:20px">Implement different operations on maps.<br>
<br>
<strong>Input:</strong><br>
The first line of input contains an integer <strong>T</strong> denoting the no of test cases . Then T test cases follow. The first line of input contains an integer <strong>Q</strong> denoting the no of queries . Then in the next line are <strong>Q</strong>&nbsp;space separated queries .<br>
A query can be of three&nbsp;types&nbsp;<br>
1. a x y&nbsp;(adds a value with key x and value&nbsp;y to the map)<br>
2. b x (print value of &nbsp;x is present in the map else print -1.&nbsp;)<br>
3. c (prints values x and y separated by space i.e., contents of map)<br>
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
4<br>
a 1 2 a 66 3 b 66 c<br>
3<br>
a 1 66 b 5 c<br>
<br>
<strong>Output</strong></span><br>
<span style="font-size:20px">3 1 2 66 3<br>
-1 1 66</span></p>

<p><br>
<span style="font-size:20px"><strong>Explanation :<br>
For the first test case</strong><br>
There are four&nbsp;queries.&nbsp;Queries&nbsp;are&nbsp;performed in this order<br>
1. a 1 2&nbsp; --&gt; &nbsp;map has a key 1 with value 2&nbsp;<br>
2. a 66 3&nbsp;--&gt;&nbsp;map has a key 66 with value 3<br>
3. b 66 &nbsp; &nbsp;--&gt; prints the value of key 66 if its present in the map ie 3.<br>
4. c &nbsp; &nbsp;--&gt; &nbsp;print the contents of map separated by space ie&nbsp;( 1 2 66 3 )<br>
<strong>For the sec test case&nbsp;</strong><br>
There are three&nbsp;queries.&nbsp;Queries&nbsp;are&nbsp;performed in this order<br>
1. a 1 66&nbsp;--&gt; adds a key 1 with a value of 66 in the map<br>
2. b 5 &nbsp; &nbsp; &nbsp;--&gt; &nbsp;since the key 5 is not present in the map hence -1 is printed.<br>
3. c &nbsp; --&gt; prints contents of map separated by space&nbsp;ie(1 66)</span><br>
<br>
<span style="font-size:16px"><strong>Note:</strong>The <strong>Input/Output</strong> format and <strong>Example</strong> given are used for system's internal purpose, and should be used by a user for <strong>Expected Output</strong> only. As it is a function problem, hence a user should not read any input from stdin/console. The task is to complete the function specified, and not to write the full code.</span></p>
 <p></p>
            </div>
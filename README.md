# Test Your Calculator!
Checklist to test how awesome is your calculator!

<p>If you want to copy a simple calculator like Windows', then you should try this sequences.</p>

<p> Left column is your input  : : Right column is an expected output on the screen. </p>

# Zero
  <ol>
    <li>```0 0 ``` : : ```0```</li>
    <li>```0 1 ``` : : ```1```</li>
    <li>```0 1 0``` : : ```10```</li>
  </ol>

# Dot
   <ol>
    <li>```. ``` : : ```0.```</li>
    <li>```.. ``` : : ```0.```</li>
    <li>```. = ``` : : ```0```</li>
    <li>```. 0 ``` : : ```0.0```</li>
    <li>```. 0 . ``` : : ```0.0```</li>
    <li>```. 0 . 1 .. 20 ``` : : ```0.0120```</li>
    <li>```. 0 . 1 .. 20 + ``` : : ```0.012```</li>
    <li>```. 0 . 1 .. 20 = ``` : : ```0.012```</li>
  </ol>

#Equal sign
  <ol>
    <li>```+ 1 = ``` : : ```1```</li>
    <li>```1 + = ``` : : ```2```</li>
    <li>```1 + 2 = 4 ``` : : ```4```</li>
    <li>```1 + 2 = = ``` : : ```5```</li>
  </ol>

#Math operators
  <ol>
    <li>```1 + 2 + + ``` : : ```3```</li>
    <li>```1 + 2 + + = ``` : : ```6``` or ```5``` (optional) - Windows' calculator shows ```6``` </li>
    <li>```1 + - * / 2 = ``` : : ```0.5```</li>
    <li>```* / + - 1 = = ``` : : ```-2```</li>
  </ol>

#Errors
  <ol>
    <li>```1 / 0 = ``` : : ```Cannot divide by zero```</li>
    <li>```1 / 0 = 2 ``` : : ```2``` (optional) - Windows' calculator require ```C```  or ```CE```  after ```1/0=``` </li>
  </ol>  

#Round-up
  <ol>
    <li>```1 . 1 * 7  = ``` : : ```7.7```</li>
    <li>```2 / 7 = ``` : : ```0.2857142857142857```</li>
    <li>```1 . 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1  * 7 ``` : : ```7.000000000000007``` (its 14 times ```0``` in each number)</li>
  </ol>

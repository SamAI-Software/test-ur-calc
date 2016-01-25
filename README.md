# Test Your Calculator!
<p>Checklist to test how awesome is your calculator!</p>
<br>
<p>If you want to copy a simple calculator like Windows Standard, then you should try this sequences.</p>
<p>Note: this calculator does not follow operator precedence.</p>
<br>
<p> Left column is your input  : : Right column is an expected output on the screen. </p>

# Zero [```0```]
  <ol>
    <li>```0 0 ``` : : ```0```</li>
    <li>```0 1 ``` : : ```1```</li>
    <li>```0 1 0``` : : ```10```</li>
  </ol>

# Dot [```.```]
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

#Equal sign [```=```]
  <ol>
    <li>```+ 1 = ``` : : ```1```</li>
    <li>```- 1 = ``` : : ```-1```</li>
    <li>```1 + = ``` : : ```2```</li>
    <li>```1 + 2 = 4 ``` : : ```4```</li>
    <li>```1 + 2 = = ``` : : ```5```</li>
  </ol>

#Math operators [```+ - * / ```]
  <ol>
    <li>```1 + 2 + + ``` : : ```3```</li>
    <li>```1 + 2 + + = ``` : : ```6``` or ```5``` (optional) - Windows' calculator shows ```6``` </li>
    <li>```1 + - * / 2 = ``` : : ```0.5```</li>
    <li>```* / + - 1 = = ``` : : ```-2```</li>
  </ol>

#Double Sign [```±```]
  <ol>
    <li>```± 1 ``` : : ```1```</li>
    <li>```1 ± ``` : : ```-1```</li>
    <li>```1 + ± 3 = ``` : : ```4``` or ```2``` or ```-13``` (optional) - Windows' calculator shows ```4``` </li>
    <li>```1 ± - 3 ± = ``` : : ```2```</li>
    <li>```2 * 2 = ± = ``` : : ```-8``` or ```16``` (optional) - Windows' calculator shows ```-8``` </li>
  </ol>

#Round-up
  <ol>
    <li>```1 . 1 * 7  = ``` : : ```7.7```</li>
    <li>```2 . 1 + 2 . 2 = ``` : : ```4.3```</li>
    <li>```2 / 7 = ``` : : ```0.2857142857142857```</li>
    <li>```1 . 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1  * 7 ``` : : ```7.000000000000007``` (its 14 times ```0``` in each number)</li>
  </ol>

#Clear Entry [```CE```]
  <ol>
    <li>```2 + 1 CE - * 5 = ``` : : ```10```</li>
  </ol>
  
#Errors
  <ol>
    <li>```1 / 0 = ``` : : ```Cannot divide by zero```</li>
    <li>```1 / 0 = 3 4 ``` : : ```34``` or ```Cannot divide by zero``` (optional) - Windows' calculator requires ```C```  or ```CE```  after ```1/0=``` </li>
    <li>```1 / 0 = 1 + 1 = ``` : : ```2``` or ```Cannot divide by zero``` (optional)</li>
  </ol>  

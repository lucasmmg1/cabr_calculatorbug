<h1>Bug Report Training</h1> 

<p>A simple Python calculator created for GitHub bug-report training.</p> 

<h2>Features</h2> 
<ul> 
  <li>Addition</li> 
  <li>Subtraction</li> 
  <li>Multiplication</li> 
  <li>Division</li> 
</ul> 

<h2>Known Issue</h2> 
<p>The <code>divide()</code> function returns an incorrect result because it adds <code>1</code> to the divisor.</p> 
<p>For example:</p> <pre><code>divide(10, 5)</code></pre> <p>Expected result:</p> <pre><code>2.0</code></pre> <p>Actual result:</p> 
<pre><code>1.6666666666666667</code></pre> 

<h2>How to Run</h2> 
<p>Make sure Python is installed, then run:</p> 
<pre><code>python calculator.py</code></pre> 
<p>Or:</p> 
<pre><code>python3 calculator.py</code></pre> 

<h2>Purpose</h2>
<p>This repository is a training example for creating and documenting a bug report, including reproduction steps, log evidence, and issue assignment.</p>

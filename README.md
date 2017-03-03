# About
A single layer perceptron maps its input x to the output f(x).<br>
f(x) is a simple binary function also called activation function and can have two possible results either 0 or 1.<br><br>
f(x) = 1 if (w.x+b) > 0, else 0.
<br>where w is a vector of real-valued weights, w.x is the dot product and b is the bias.

# Perceptron-Logic_Gate
Implementation of AND and OR logic gates using a single-layer perceptron.
<br><br>
AND Logic Gate:<br>
<table>
  <tr>
  <th>X1</th>
  <th>X2</th>
  <th>Output</th>
  </tr>
  <tr>
  <td>0</td>
  <td>0</td>
  <td>0</td>
  </tr>
  <tr>
  <td>0</td>
  <td>1</td>
  <td>0</td>
  </tr>
  <tr>
  <td>1</td>
  <td>0</td>
  <td>0</td>
  </tr>
  <tr>
  <td>1</td>
  <td>1</td>
  <td>1</td>
  </tr>
</table>
<br><br>
OR Logic Gate:<br>
<table>
  <tr>
  <th>X1</th>
  <th>X2</th>
  <th>Output</th>
  </tr>
  <tr>
  <td>0</td>
  <td>0</td>
  <td>0</td>
  </tr>
  <tr>
  <td>0</td>
  <td>1</td>
  <td>1</td>
  </tr>
  <tr>
  <td>1</td>
  <td>0</td>
  <td>1</td>
  </tr>
  <tr>
  <td>1</td>
  <td>1</td>
  <td>1</td>
  </tr>
</table>

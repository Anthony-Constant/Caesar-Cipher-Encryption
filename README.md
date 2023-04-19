<div>
<h2>Introduction</h2>
<p>This is a simple implementation of the Caesar cipher encryption technique in Python. The Caesar cipher is one of the simplest and most widely known encryption techniques. It works by replacing each letter in the plaintext message by a letter a fixed number of positions down the alphabet. This fixed number is called the key. The method is named after Julius Caesar, who used it in his private correspondence.</p>
<h3>Encryption Formula</h3>
<p>The encryption formula for the Caesar cipher is as follows:</p>
<p>En(x) = (x + n) mod 26</p>
<p>where x is the plaintext message and n is the key. The value 26 is used because there are 26 letters in the alphabet. The mod operation ensures that the result is always within the range of the alphabet.</p>
<h3>Decryption Formula</h3>
<p>The decryption formula for the Caesar cipher is as follows:</p>
<p>Dn(x) = (x - n) mod 26</p>
<h2>How it Works</h2>
<p>The Caesar cipher is a substitution cipher in which each letter in the alphabet is replaced by a letter some fixed number of positions down the alphabet. For example, with a right shift of 2, C would replace A, D would become B and so on. The following table shows the encryption and decryption alphabets for a right shift of 2:</p>
<table>
  <tr>
    <th>Plain</th>
    <td>A</td>
    <td>B</td>
    <td>C</td>
    <td>D</td>
    <td>E</td>
    <td>F</td>
    <td>G</td>
    <td>H</td>
    <td>I</td>
    <td>J</td>
    <td>K</td>
    <td>L</td>
    <td>M</td>
    <td>N</td>
    <td>O</td>
    <td>P</td>
    <td>Q</td>
    <td>R</td>
    <td>S</td>
    <td>T</td>
    <td>U</td>
    <td>V</td>
    <td>W</td>
    <td>X</td>
    <td>Y</td>
    <td>Z</td>
  </tr>
  <tr>
    <th>Cipher</th>
    <td>C</td>
    <td>D</td>
    <td>E</td>
    <td>F</td>
    <td>G</td>
    <td>H</td>
    <td>I</td>
    <td>J</td>
    <td>K</td>
    <td>L</td>
    <td>M</td>
    <td>N</td>
    <td>O</td>
    <td>P</td>
    <td>Q</td>
    <td>R</td>
    <td>S</td>
    <td>T</td>
    <td>U</td>
    <td>V</td>
    <td>W</td>
    <td>X</td>
    <td>Y</td>
    <td>Z</td>
    <td>A</td>
    <td>B</td>
  </tr>
</table>

<h2>Usage</h2>
<p>To use the Caesar cipher encryption in Python, simply run the Caesar_Cipher.py file and follow the prompts. Enter the plaintext message and the key (an integer between 1 and 25) when prompted. The script will then encrypt the message and display the ciphertext.</p>
<h2>References</h2>
<ul>
  <li><a href="https://en.wikipedia.org/wiki/Caesar_cipher">https://en.wikipedia.org/wiki/Caesar_cipher</a></li>
</ul>
<h2>Credits</h2>
<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at <a href="https://anthonyconstant.co.uk/">anthonyconstant.co.uk</a>.</p>
<h2>License</h2>
<p>This script is released under the MIT License. See the LICENSE file for more details.</p>

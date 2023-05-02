Download Link: https://assignmentchef.com/product/solved-comp322-assignment-1-exploring-functions-and-arrays
<br>
In the following questions you will be asked to write multiple functions doing each a specific task. The signature of each function will be provided as well as a main() function that calls all the functions one by one and print their results to the screen.

Question 1

Write a function that asks the user to input a sentence, then it will ask the user to enter one letter. The function will then count the number of occurrences of this letter in the provided sentence. Don’t forget that both uppercase and lowercase letters should be counted. Signature of the function: <strong>void countLetter(); </strong>

When running the CountLetter() function, the output should be similar to the following example:

Please enter a sentence: HELLO there, how are you?

Please enter a letter: o

The letter o is repeated 3 times in your sentence

Question 2

According to wikipedia: The 26 code words in the NATO phonetic alphabet are assigned to the 26 letters of the English alphabet in alphabetical order as follows: ​<strong>A​</strong>lfa, ​<strong>B​</strong>ravo, ​<strong>C​</strong>harlie,

<strong>D​</strong>elta, ​<strong>E​</strong>cho, ​<strong>F​</strong>oxtrot, ​<strong>G​</strong>olf, ​<strong>H​</strong>otel, ​<strong>I​</strong>ndia, ​<strong>J​</strong>uliett, ​<strong>K​</strong>ilo, ​<strong>L​</strong>ima, ​<strong>M​</strong>ike, ​<strong>N​</strong>ovember, ​<strong>O​</strong>scar, ​<strong>P​</strong>apa, <strong>Q​</strong>uebec, ​<strong>R​</strong>omeo, ​<strong>S​</strong>ierra, ​<strong>T​</strong>ango, ​<strong>U​</strong>niform, ​<strong>V​</strong>ictor, ​<strong>W​</strong>hiskey, ​<strong>X​</strong>-ray, ​<strong>Y​</strong>ankee, ​<strong>Z​</strong>ulu.

<u><a href="https://en.wikipedia.org/wiki/NATO_phonetic_alphabet">https://en.wikipedia.org/wiki/NATO_phonetic_alphabet</a></u>

Write a function that takes a word and translate each letter into its corresponding phonetic alphabet.

Signature of the function: <strong>void convertPhonetic(); </strong>

When running the ConvertPhonetic() function, the output should be similar to the following example:

Please enter a word: Hello

Hotel Echo Lima Lima Oscar

Question 3

<ul>

 <li>Research tail recursivity and explain in your own words why it is better to design your recursive function this way.</li>

 <li>Can any recursive function be designed to be tail recursive? Please develop your answer by providing clear explanation</li>

</ul>

Write your answer inside a C++ comment block within your cpp file.

Question 4

Write a tail recursive factorial function. Signature of the function: <strong>void factorial(); </strong>

When running the factorial() function, the output should be similar to the following example:

Please enter a number: 4

The factorial of 4 is 24

Please note that you may need to write a helper function to be called by factorial to make your code easier.

Question 5

Write an enhanced version of your recursive factorial function using an array that stores the calculated factorial of the first 6 factorials. This means that the values for the first 6 factorials (1, 2, 6, 24, 120, 720) are already known and stored in an array so you don’t need to recalculate them each time the function runs. Signature of the function: <strong>void enhancedFactorial(); </strong>

When running the factorial() function, the output should be similar to the following example:

Please enter a number: 4

The factorial of 4 is 24

Please note that you may need to write a helper function to be called by factorial to make your code easier.




<strong>Please use the following main() function for testing: int main() { countLetter(); convertPhonetic(); factorial(); enhancedFactorial(); return 0; </strong>

<strong>} </strong>

<strong> </strong>

<strong> </strong>
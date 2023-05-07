Download Link: https://assignmentchef.com/product/solved-kit103-assignment1-literal-values
<br>
Enter your answers to these questions in the accompanying Python script le kit103_assign1.py. Each question has an entry in a dictionary of answers that is initially set to None. Replace this with the requested Python expression (that is, code that generates a value). For instance, to answer Question 1 part a you could put:

ans[‘Q1 a’] = { ‘this’, ‘is’, ‘just’, ‘an’, ‘example’ }

Wherever a question indicates that certain values are given and must be used in your answer you will nd that these variables are also de ned in the script le.

Submit your completed script le to the Programming Assignment 1 (Sets) assignment folder on MyLO by 1500 (3pm) Wednesday 16 August 2017.

Each question part is worth 0.25 marks. KMA155 students will be assessed primarily on questions marked with an asterisk (*), but may attempt all questions if they wish.

<h1>Question 1: Literal Values</h1>

Write these sets as literal values (i.e., program text that literally represents the value described).

<ol>

 <li>(*) the rst 6 positive even numbers greater than zero</li>

 <li>(*) the names Bob, Alice, Donna and Charlie (with that capitalisation)</li>

 <li>the set of English vowels (a, e, i, o and u; remember to put them inside quote marks)</li>

</ol>

<h1>Question 2: Set Comprehensions</h1>

Write set comprehensions to generate the following sets:

<ol>

 <li>(*) the set { 8, 16, 24, 32, 40 }</li>

 <li>(*) cubes of the rst 6 positive integers (i.e., { 1<sup>3</sup>, 2<sup>3</sup>, 3<sup>3</sup>, 4<sup>3</sup>, 5<sup>3</sup>, 6<sup>3</sup> })</li>

</ol>

(tip: Python has an exponentiation operator **)

<ol>

 <li>the set of letters in the word ‘abracadabra’ (hint: strings in Python can be treated exactly like lists of characters). Your solution should still work if we were to change the word, so do not remove repeated letters yourself.</li>

</ol>

<h1>Question 3: Relationships</h1>

Assume that the following sets have been de ned:

mammals = { ‘cow’, ‘gorilla’, ‘human’, ‘kangaroo’ }

aves = { ‘cormorant’, ‘eagle’, ’emu’ } quadrupeds = { ‘cow’, ‘lizard’ }

bipeds = { ‘cormorant’, ‘eagle’, ’emu’, ‘gorilla’, ‘human’, ‘kangaroo’ }

can_swim = { ‘cormorant’, ‘cow’, ‘human’, ‘kangaroo’ } can_fly = { ‘aeroplane’, ‘cormorant’, ‘eagle’ }

Write boolean expressions using Python set comparison operators (i.e., issubset(), &lt;=, ==, etc.) and the above sets to answer the questions below. Do not simply say yes or no (imagine that the sets above were actually complete and so too large for you to answer these questions unaided). Ensure you answer the question as asked.

<ol>

 <li>Are bipeds a proper subset of mammals?</li>

 <li>(*) Can all bipeds swim?</li>

 <li>Are all aves (birds) also bipeds?</li>

</ol>

<h1>Question 4: Set membership</h1>

Given the sets de ned in Question 3, identify the following subgroups (as above, write the Python code that will nd the answer):

<ol>

 <li>Mammals that cannot swim</li>

 <li>Things that can y and swim</li>

 <li>(*) Bipeds that can swim but are not mammals</li>

</ol>

<h1>Question 5: Combinations</h1>

Jodie would like to identify her dream vehicle by enumerating various possibilities based on speed, colour and vehicle type. Given the following sets of options, write set comprehensions that will generate the possible combinations described below. Note that the order of items in each combination should match the order in the question.

colours = { ‘red’, ‘green’, ‘blue’, ‘yellow’ } vehicles = { ‘car’, ‘boat’, ‘rocket’ } speeds = { ‘slow’, ‘fast’ }

<ol>

 <li>Generate all pairs of speeds and vehicles.</li>

 <li>Generate novel vehicle types by combining vehicles with other vehicles as pairs. These may include the same vehicle twice.</li>

 <li>(*) Generate all triples (3-tuples) of speed, colour and vehicle.</li>

</ol>

<h1>Question 6: Bags &amp; Bitsets</h1>

<ol>

 <li>Write a dictionary literal that represents the bag/multiset { ‘cat’, ‘hat’, ‘sat’, ‘cat’, ‘sat’, ‘sat’ }</li>

</ol>

Parts b through e assume the following are de ned: a universe of discourse  = { ‘alfa’, ‘bravo’, ‘charlie’,

‘delta’, ‘echo’ }, and sets set1 = { ‘delta’, ‘echo’ } and set2 = { ‘alfa’, ‘bravo’, ‘delta’ }.

<ol>

 <li>(*) Write the binary literal value that encodes set1 as a 5-bit long bitset. (Remember that a binary literal begins with 0b.)</li>

 <li>(*) Write the binary literal value that encodes set2 as a 5-bit long bitset.</li>

 <li>(*) Write the binary literal that corresponds to the result of the set operation set1 set2.</li>

 <li>Referring to the bitset representations of set1 and set2 stored in your previous answers ans[‘Q6 b’] and ans[‘Q6 c’], respectively, write the bit-wise expression that would calculate the result of the set operation set1</li>

</ol>
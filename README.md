# spoken english to written english

This is a Python module to convert a paragraph of spoken english to written english.

For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.

#Note- as of now the code can handle punctuation marks like . and ,.

To add new rule(new punctuation marks)- please read "Q2 design document.pdf"

Also:
This code currently support three rules: Numbers(e.g. one, two), Tuples(e.g. double, triple) and general (like "C M","P M","D M","A M").

## Usage 1

Paragraph of spoken english:

triple a

Output:

Spoken english: triple a

Written English:  aaa

## Usage 2

Paragraph of spoken english:

C M

Output:

Spoken english: C M

Written English:  CM

## Usage 3

Paragraph of spoken english:

two dollars

Output:

Spoken english: two dollars

Written English:  $2

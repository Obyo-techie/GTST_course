# Regular Expressions!/regex/

- Most filter validation on any platform done by Regular expression /regex/.
- They are patterns that helps to filter so texts, space, tabs & symbol.
- Like telegram or other platform filtering links inside group, filtering some bad words..... Aregex
- Regex is PATTERN!
- Regex are used on linux tools called grep.awk and sed

**((GOOGLE DORKING))????  
((GITHUB DORKING))????**

## regex....

- to demonstrate this we can use Vscode search tools
- And don't forget to turn the regex button on
- the pattern is same but the implementation may differ on programming language.
- on Python.

## Meta characters

- Those are regex pattern symbol. - >>>. | ^ | $ | * | ? |
    - DOT
        - Used to get ALL line except new lines
            - syntax '.'
    - Caret (^) .Assertion.
        - Used to get lines that starts with pattens
            - syntax '^text'
    - Dollar sign ($)
        - Used to get line that ends with some pattern.
            - syntax 'text$'
    - Plus (+) - Quantity
        - used to get that have pattern that occurs 1 and more times.
            - Syntax ' Text+'
    - Asterix ( *) - Quantity
        - Used to get line that have pattern that occurs 0 and more times.
            - Syntax 'text*'
    - Question mark (?) -Quantity
        - used to get line that have pattern that occurs 0 and 1 times.
            - Syntax 'text?'
    - Curly Bracket ({ min, max}) - Quantity
        - Used to get line that have pattern that occurs min and max times. it is custom
            - Syntax 'text{1,2}' for plus 'text{0,1}' for asterix
    - \w (small letter 'w')
        - used to get alphanumeric
    - \W (capital letter 'W')
        - used to get all except alphanumeric
            - syntax '\W'
    - \s  (small letter 's')
        - Used to get white space.
          - syntax '\s'
    - \S  (capital letter 'S')
        -  Used to get except whitespace 
            -  syntax 'S'
    - \d (small letter 'd')
        - used to get digits
           -  syntax '\d'
    - \D (capital letter 'D')
        - used to get except Digits/nums/
           - syntax '\D'
    - Pipe (  |  ) OR
        - used to search 2 different things
            - syntax 'a|b'
      - Escape ( \ )
         - used to search symbols that are metacharacters.
             - syntax '\sign'
     - Square bracket ( [ ] ) - custom pattern
        - Used to create your own patterns
           - Syntax [pattern]

## Bash regex

- You  can use it on awk, sed and grep 
#### on grep

 somebody@parrotmachine ~> cat testingREGEX.md | gerp *"^. * @. * [a-z\$]"*   
## Bash for REGEX
- we use =~ operator for regex check with if condition statements
- Here we use double brackets for our conditional statments 
   -  syntax pattern="pattern="YourRegex"
                     if [[$input =~ ${pattern} ]]


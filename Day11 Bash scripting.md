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
        - used to get
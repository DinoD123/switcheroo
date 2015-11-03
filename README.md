# switcheroo
An esoteric programming language that attempts to contain all other useful programming languages

The code is broken up into sections with labels, each representing a program in another esoteric programming language.
For example:

    `b0
    ++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.
    `>0
    !v"hello, world"r!
     >l?!;o

Each label is formatted as such:

    `(first character of language name)(index digit) [input] [options]

The index digit is in base 62, which is counted 0-9,a-z,A-Z.

If the input is empty, but you need to use the options, then too bad. I'll figure out how to make the input and options parts better.

The options modify the program in certain ways, and many languages won't have any. For example, in ><>, there's and option to give input into the starting stack.

Once I start actually working on the interpreter, I'll make a table of language codes.

# assembler

gcc -o assembler main.c lexer.c parser.c -Wall
./assembler test_code.txt output.mem

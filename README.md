## Interpreter for Monty ByteCode files
> This is an interpreter for
> these special opcodes: `push`, `pall`, `pint`, `pop`, `swap`, `swap`, `add`, `nop`

### How to Compile
Usage: ./monty [filename]
```
$ git clone https://github.com/MelissaN/monty
$ cd monty
$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty
$ ./monty bytecodes/000.m
```

### Built using
- C
- OS: Ubuntu 14.04 LTS
- compiler: gcc 4.8.4
- Style guidelines: Betty

### Author
- Amanuel Sisay     [![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/30px-Twitter_Bird.svg.png)](https://twitter.com/amanabiy_as)
- Amanuel Awol

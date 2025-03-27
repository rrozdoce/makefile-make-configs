# Why Makefile is used for?

## Small projects

Makefile is a file configuration which defines the rules of compilation, often, is used for total controll of process to small projects

# What is make?

Make is a tool which read Makefile and execute the rules, always use when a Makefile is present

```sh
make        # Executa a primeira regra (normalmente 'all')
make clean  # Executa a regra 'clean'
make -j4    # Compila com 4 threads (paralelismo)
```

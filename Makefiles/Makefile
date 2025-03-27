# Nome do executável
TARGET = meu_programa

# Compilador
CC = gcc

# Flags de compilação
CFLAGS = -Wall -Wextra

# Arquivos fonte
SRCS = main.c utils.c

# Arquivos objeto (gerados a partir dos .c)
OBJS = $(SRCS:.c=.o)

# Regra padrão
all: $(TARGET)

# Regra para gerar o executável
$(TARGET): $(OBJS)
	$(CC) $(CFLAGS) -o $@ $^

# Regra para compilar cada arquivo .c em .o
%.o: %.c
	$(CC) $(CFLAGS) -c $< -o $@

# Limpar arquivos gerados
clean:
	rm -f $(OBJS) $(TARGET)


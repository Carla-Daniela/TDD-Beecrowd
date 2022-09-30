# Makefile

CC = gcc
TEST = test_bee_1132.exe
UNITY = ./Unity/src/unity.c

all:	$(TEST)

test_%.exe:	test_%.c
		$(CC) $< $(UNITY) -o $@ -lm
		./$@
		rm $@	
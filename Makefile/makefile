OBJ=main.o tool1.o tool2.o 
CFLAGS+=-c -Wall -g
CC=gcc

mytool:$(OBJ)
	$(CC) $(OBJ) -o $@

%.o:%.c
	$(CC) $(CFLAGS) $^ -o $@

clean:
	$(RM) -r *.o mytool
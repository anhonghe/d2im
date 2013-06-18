CC		=	gcc -Wall -g
CFLAGS  =   
LIBS    =   -lm -lpthread -lX11 -lXcursor -lXcursor -ldl -lGL
OBJS    =   main.o
all:$(OBJS)
	$(CC) $(OBJS)  $(CFLAGS) $(LIBS) -o ../bin/mapedit
test:
	make test -C ../bin
debug:
	make debug -C ../bin
clean:
	rm  *.o ./mpq/*.o ../bin/mapedit -f
$(OBJS):%.o:%.c
	$(CC) -c $(CFLAGS) $< -o $@

PROGRAMA := scanner2
CC := gcc

all: $(PROGRAMA)

$(PROGRAMA): scanner2.l
	flex scanner2.l
	$(CC) lex.yy.c -o $(PROGRAMA)

clean:
	rm -f $(PROGRAMA) $(PROGRAMA).exe lex.yy.c

.PHONY: all clean
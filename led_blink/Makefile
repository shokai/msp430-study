CC=msp430-gcc
CFLAGS=-Os -Wall -g -mmcu=msp430g2553

OBJS=main.o


all: $(OBJS)
	$(CC) $(CFLAGS) -o main.elf $(OBJS)

%.o: %.c
	$(CC) $(CFLAGS) -c $<

clean:
	rm -f main.elf $(OBJS)

AS=asm -v -n -C 68HC11

%.S19:	%.ASM
	$(AS) -l $*.LST -o $*.S19 $^

.PHONY: clean distclean

all: BUFFALO.S19

clean:
	-rm -f *.LST
distclean: clean
	-rm -f *.S19

AS=asm -C 68HC11 -n -u

%.S19:	%.ASM
	$(AS) -l $*.LST -o $@ $^

.PHONY: clean distclean

all: BUFFALO.S19

clean:
	-rm -f *.LST
distclean: clean
	-rm -f *.S19


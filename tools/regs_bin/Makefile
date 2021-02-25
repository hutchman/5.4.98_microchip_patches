

RAMDISK_DIR = ../ramdisk/usr/sbin

CFLAGS = -Wall

EXE=regs_bin

all: $(EXE)

regs_bin: regs_bin.c
	$(CC) -o regs_bin $(CFLAGS) regs_bin.c

clean:
	$(RM) $(EXE)

install: $(EXE)
	@install -m 755 $(EXE) $(RAMDISK_DIR)





CFLAGS += -Wall -Wno-array-bounds -pthread 

EXE=ptp_cli mrp_cli

all: $(EXE)

ptp_cli: ptp_cli.c ksz_ptp.c ksz_ptp.h
	$(CC) -o ptp_cli $(CFLAGS) ptp_cli.c

mrp_cli: mrp_cli.c ksz_mrp_api.c ksz_mrp_api.h
	$(CC) -o mrp_cli $(CFLAGS) mrp_cli.c

clean:
	$(RM) $(EXE)

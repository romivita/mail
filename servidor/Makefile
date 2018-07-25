CC =gcc
CFLAGS=-g -pthread -Wall
//LDLIBS=-pthread
TARGETS=servidor

all: $(TARGETS)

servidor: servidor.c worker.c response.c request.c archivo.c contar.c workerG.c extencion.c 
	$(CC) $(CFLAGS) -o $@ $^

clean: servidor
	rm $(TARGETS) *.o

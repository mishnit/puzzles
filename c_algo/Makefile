CFLAGS=-Wall -g

all:
	make quicksort
	make mergesort
	make binary_search
	make linkedlist
	make radix
	make trees

clean:
	rm -f quicksort
	rm -f mergesort
	rm -f binary_search
	rm -f linkedlist
	rm -f radix
	rm -f trees
	rm -f *.o
	rm -rf *.dSYM

quicksort: common.o
mergesort: common.o
binary_search: common.o
radix: common.o
trees: queue.o

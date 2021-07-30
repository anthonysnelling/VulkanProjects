blah: blah.o
    cc blah.o -o blah # Runs Third

blah.o: blah.c
    cc -c blah.c -o blah.o # Runs Second

blah.c:
	echo "int main() { return 0; }" > blah.c #Runs First
    

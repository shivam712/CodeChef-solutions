CFLAGS=-Wall -g

c: 
	gcc -std=c99 {{ project_name }}.c -o {{ project_name }}.out

java:
	javac Main.java

clean:
	rm -f {{ project_name }}.out
	rm -f Main.class

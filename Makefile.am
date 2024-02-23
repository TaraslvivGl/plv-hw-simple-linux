AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = helloworld
helloworld_SOURCES = main.c hello_func.c
dist_doc_DATA = README.md
include_HEADERS = hello_make.h

clean-all:
	ls | grep -Ev '*\.c\b|*\.am\b|*\.ac\b|*\.md\b|*\.h\b|*\.gz\b' | xargs rm -fr
	rm -fr /usr/local/include/hello_make.h
	rm -fr /usr/local/share/doc/helloworld/README.md
	rm -fr /usr/local/bin/helloworld
	

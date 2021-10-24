Current script generates initial directories structure, including a simple Makefile;/
Optionally with '-i' flag you can generate the gitignore file;/
We assume that default new project is written on C programming language;/

Example:/
	command:/
		./new_project foo_prj_name -i/
	result:/
		foo_prj_name/ /
		|-Makefile/
		|-.gitignore/
		|/
		|-build/ /
		|-include/ /
		|-src/ /

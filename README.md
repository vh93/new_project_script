Current script generates initial directories structure, including a simple Makefile;<br />
Optionally with '-i' flag you can generate the gitignore file;<br />
We assume that default new project is written on C programming language;<br />

Example:<br />
	command:<br />
		./new_project foo_prj_name -i<br />
	result:<br />
		foo_prj_name/ <br />
		|-Makefile<br />
		|-.gitignore<br />
		|<br />
		|-build/ <br />
		|-include/ <br />
		|-src/ <br />

Current script generates initial directories structure, including a Makefile; <br>
Optionally with '-i' flag you can generate the gitignore file; <br>
We assume that default new project is written on C language; <br>
<br>
	command:
<br>
<code>
	./new_project foo_prj_name -i
</code>
<br>result:
<br>
<code>foo_prj_name/</code>
<br>
<code>
	|- Makefile
</code>
<br>
<code>
	|- .gitignore
</code>
<br>
<code>
	|- build/
</code>
<br>
<code>
	|- include/
</code>
<br>
<code>
	|- src/
</code>

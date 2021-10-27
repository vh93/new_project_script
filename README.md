Current script generates initial directories structure, including a Makefile; <br>
Optionally with '-i' flag you can generate the gitignore file; <br>
We assume that default new project is written on C language; <br>
<br>
	Example:
<br>

&emsp;
	command:
<br>
&emsp;&emsp;
<code>
	./new_project foo_prj_name -i
</code>
<br>

&emsp;
	result:
<br>
&emsp;&emsp;
<code>
	foo_prj_name/
</code>
<br>
&emsp;&emsp;
<code>
	|__Makefile
</code>
<br>
&emsp;&emsp;
<code>
	|__.gitignore
</code>
<br>
&emsp;&emsp;
<code>
	|__build/
</code>
<br>
&emsp;&emsp;
<code>
	|__include/
</code>
<br>
&emsp;&emsp;
<code>
	|__src/
</code>

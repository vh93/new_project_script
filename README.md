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
	|-Makefile
</code>
<br>

&emsp;&emsp;
<code>
	|-.gitignore
</code>
<br>

&emsp;&emsp;
<code>
	|
</code>
<br>

&emsp;&emsp;
<code>
	|-build/
</code>
<br>

&emsp;&emsp;
<code>
	|-include/
</code>
<br>

&emsp;&emsp;
<code>
	|-src/
</code>

Current script generates initial directories structure, <br>
including a simple Makefile; <br>
Optionally with '-i' flag you can generate the gitignore file; <br>
We assume that default new project is written on <br>
C programming language;
<br>
Example:										<br>
&emsp;			command: 						<br>
&emsp;&emsp;	./new_project foo_prj_name -i	<br>
&emsp;			result:							<br>
&emsp;&emsp;	foo_prj_name/					<br>
&emsp;&emsp;	|-Makefile						<br>
&emsp;&emsp;	|-.gitignore					<br>
&emsp;&emsp;	|								<br>
&emsp;&emsp;	|-build/						<br>
&emsp;&emsp;	|-include/						<br>
&emsp;&emsp;	|-src/

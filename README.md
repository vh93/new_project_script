Current script generates initial directories structure, including a Makefile; <br>
Optionally with '-i' flag you can generate the gitignore file; <br>
We assume that default new project is written on C language; <br>
<br>command:
<br>
<code>./new_project foo_prj_name -i</code>
<br>result:
<br>
<code>foo_prj_name/</code>
<br>
<code>|__Makefile</code>
<br>
<code>|_.gitignore</code>
<br>
<code>|__build/</code>
<br>
<code>|__include/</code>
<br>
<code>|__src/</code> <br>
Note, that if you would like to have a singe-file project, <br>
in the Makefile you should comment the <code>$(OBJECT_FILES)</code><br> 
part on the line 22:<br>
<code>21 #targets</code>
<code>22 foo_prj_name: $(SRC_DIR)/foo_prj_name.c #$(OBJECT_FILES)</code>
<br>

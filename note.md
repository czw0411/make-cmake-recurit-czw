# task 02

在nanno中尝试修改题目中的todo后，一直提示：Makefile:4: *** missing separator.  Stop.在询问codex后，得知每行前面不是按空格，而是应该按tab，对此，codex给出的解释是：这个报错的原因：Makefile 里"命令"行必须以 Tab（制表符）开头，但你编辑时 Tab 可能被换成了空格。第 4 行的规则下面那行命令开头是空格，make 就不认了。

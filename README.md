#RISC CPU
注意$readmemb读取文件路径的格式；
注意根据IEEE2005年标准rom或ram中若出现reg[8:0] mem[0,8]等声明，则表示位宽的那一项即[0,8]应用小端格式；

#波形查看
在test文件夹中使用gtkwave查看wave.fst
在终端中执行如下指令：
```shell
cd test
gtkwave wave.fst
```
# RISC_CPU_XIAYUWEN_TEXTBOOK

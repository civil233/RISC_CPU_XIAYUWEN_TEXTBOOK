# RISC CPU <br>
注意$readmemb读取文件路径的格式；<br>

注意根据IEEE2005年标准rom或ram中若出现reg[8:0] mem[0,8]等声明，则表示位宽的那一项即[0,8]应用小端格式；<br>

此risc cpu实现了8条指令；<br>

此cpu通过改变ram、rom中的指令实现了多种功能，对应test文件夹中的test1、2、3；<br>

# 波形查看
使用gtkwave查看wave.fst
在终端中执行如下指令：
```shell
cds
cd test
gtkwave wave.fst
```
# 命令行输出查看
在top.v文件中通过iverilog中自带的编译指令-o，联合其他模块共同仿真

# RISC_CPU_XIAYUWEN_TEXTBOOK

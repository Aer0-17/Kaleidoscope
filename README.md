# Kaleidoscope

## LLVM
- **LLVMContext** TheContext 是一个不透明的对象，拥有许多核心 LLVM 数据结构，例如类型和常量值表。
- **Module** TheModule是LLVM中用于存放代码段中所有函数和全局变量的结构。从某种意义上讲，可以把它当作LLVM IR代码的顶层容器。
- **IRBuilder** Builder是用于简化LLVM指令生成的辅助对象。IRBuilder类模板的实例可用于跟踪当前插入指令的位置，同时还带有用于生成新指令的方法。
- **Value** 是用于表示 LLVM 中的“静态单赋值（SSA）寄存器”或“SSA 值”的类 https://en.wikipedia.org/wiki/Static_single-assignment_form
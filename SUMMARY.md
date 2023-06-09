# Summary

* [rust](docs/readme.md)
  * [1.Installing Rust](docs/1.setup.md)
    * [install rust](./docs/1.setup.md#1installing-rust) 
      * [rustup(rust toolchain installer)典型使用](docs/1.setup.md#rustuprust-toolchain-installer典型使用)
    * [rustup cargo](docs/1.setup.md#rustup-cargo)
  * [2. envirment prepare](docs/2.envprepare.md)
    * [introduction](docs/2.envprepare.md#introduce)
    * [cargo典型使用](docs/2.envprepare.md#cargo典型使用)
    * [维护Cargo.toml manifest](docs/2.envprepare.md#维护cargotoml-manifest)
    * [持续集成](docs/2.envprepare.md#持续集成)
      * [cargo*binutils 典型使用](docs/2.envprepare.md#cargo-binutils-典型使用)
    * [编译诊断约束属性](docs/2.envprepare.md#编译诊断约束属性)
      * [诊断属性Diagnostic attributes](docs/2.envprepare.md#诊断属性diagnostic-attributes)
      * [限制属性limits attributes](docs/2.envprepare.md#限制属性limits-attributes)
  * [3.初次rust编程](docs/3.firsttime.md)
    * [C经验的冲突](docs/3.firsttime.md#c经验的冲突)
    * [第一个程序](docs/3.firsttime.md#第一个程序)
  * [4.rust语法](docs/4.syntax.md)
    - [语法速查](docs/4.syntax.md#语法速查)
      - [类型](docs/4.syntax.md#类型)
      - [格式化输出](docs/4.syntax.md#格式化输出)
      - [流程](docs/4.syntax.md#流程)
      - [关键字type](docs/4.syntax.md#关键字type)
    - [语句与表达式概念](docs/4.syntax.md#语句与表达式概念)
    - [变量](docs/4.syntax.md#变量)
      - [隐藏（Shadowing） 概念](docs/4.syntax.md#隐藏shadowing-概念)
    - [数据类型](docs/4.syntax.md#数据类型)
      - [复合类型：tuple](docs/4.syntax.md#复合类型tuple)
      - [符合类型：array](docs/4.syntax.md#符合类型array)
      - [符合类型 切片Slice](docs/4.syntax.md#符合类型-切片slice)
      - [复合类型：范围Range](docs/4.syntax.md#复合类型范围range)
    - [自定义数据类型](docs/4.syntax.md#自定义数据类型)
      - [复合类型：struct](docs/4.syntax.md#复合类型struct)
      - [枚举enumerations](docs/4.syntax.md#枚举enumerations)
    - [函数与方法与闭包](docs/4.syntax.md#函数与方法与闭包)
      - [函数与方法](docs/4.syntax.md#函数与方法)
      - [所有权与函数](docs/4.syntax.md#所有权与函数)
      - [闭包Closure](docs/4.syntax.md#闭包closure)
      - [高阶函数（Higher Order Function, HOF）](docs/4.syntax.md#高阶函数higher-order-function-hof)
    - [流程控制](docs/4.syntax.md#流程控制)
      - [if、else语句](docs/4.syntax.md#ifelse语句)
      - [if let](docs/4.syntax.md#if-let)
      - [while let](docs/4.syntax.md#while-let)
      - [loop、while、for](docs/4.syntax.md#loopwhilefor)
      - [match](docs/4.syntax.md#match)
    - [collections](docs/4.syntax.md#collections)
      - [Iterator trait](docs/4.syntax.md#iterator-trait)
    - [特征trait](docs/4.syntax.md#特征trait)
      - [通用trait](docs/4.syntax.md#通用trait)
    - [错误处理error handling](docs/4.syntax.md#错误处理error-handling)
  * [5.rust 高级功能](docs/5.advanced_feature.md)
    - [macro](docs/5.advanced_feature.md#macro)
      - [描述宏Declarative Macros](docs/5.advanced_feature.md#描述宏declarative-macros)
      - [过程宏（Procedure Macro）](docs/5.advanced_feature.md#过程宏procedure-macro)
    - [命令行解析](docs/5.advanced_feature.md#命令行解析)
    - [序列化与反序列化](docs/5.advanced_feature.md#序列化与反序列化)
  * [6.rust模块化组织](docs/6.module_organization.md)
    - [packages and crates](docs/6.module_organization.md#packages-and-crates)
    - [Modules](docs/6.module_organization.md#modules)
      - [文件分层](docs/6.module_organization.md#文件分层)
    - [Cargo.toml文件说明](docs/6.module_organization.md#cargotoml文件说明)
      - [发布配置profile](docs/6.module_organization.md#发布配置profile)
    - [6.6.条件编译](docs/6.module_organization.md#66条件编译)
  * [7.与其他语言交换](docs/7.interactwithother.md)
    - [rust 选择不同的编译器](docs/7.interactwithother.md#rust-选择不同的编译器)
    - [STM32 (Cortex M3) 和 GD32 (RISC-V)](docs/7.interactwithother.md#stm32-cortex-m3-和-gd32-risc-v)
  * [8.自动测试](docs/8.test.md)
    - [单元测试](docs/8.test.md#单元测试)
    - [性能测试](docs/8.test.md#性能测试)
    - [集成测试](docs/8.test.md#集成测试)
    - [问题处理](docs/8.test.md#问题处理)
      - [error: Unable to update registry `crates-io`](docs/8.test.md#error-unable-to-update-registry-crates-io)
      - [error: failed to parse manifest at ... edition key](docs/8.test.md#error-failed-to-parse-manifest-at--edition-key)
      - [升级问题](docs/8.test.md#升级问题)
    - [notes:](docs/8.test.md#notes)
  * [9.内存安全](docs/9.memory_security.md)
    - [所有权 Ownership](docs/9.memory_security.md#所有权-ownership)
    - [借用 Borrowing](docs/9.memory_security.md#借用-borrowing)
  * [10. bindgen & cbindgen](docs/10.bindgen.md)
  * [18. references](docs/18.references.md)
* [embedded](docs/embedded/0.prepare.md)
  - [0.预准备](docs/embedded/0.prepare.md#0预准备)
    - [which target?](docs/embedded/0.prepare.md#which-target)
    - [建议](docs/embedded/0.prepare.md#建议)
  - [1.常用工具](docs/embedded/1.tools.md)
    - [probe-run](docs/embedded/1.tools.md#probe-run)
    - [cargo-generate](docs/embedded/1.tools.md#cargo-generate)
    - [inspecting tools](docs/embedded/1.tools.md#inspecting-tools)
      - [LLVM Object Reader](docs/embedded/1.tools.md#llvm-object-reader)
      - [LLVM object size dumper](docs/embedded/1.tools.md#llvm-object-size-dumper)
      - [llvm object file dumper](docs/embedded/1.tools.md#llvm-object-file-dumper)
      - [testing on qemu](docs/embedded/1.tools.md#testing-on-qemu)
  - [2.Debug on omicon3.Debug on omicon](docs/embedded/2.debug.md)
    - [openocd debug](docs/embedded/2.debug.md#openocd-debug)
      - [1.connect to board](docs/embedded/2.debug.md#1connect-to-board)
      - [2. use pure openocd cmd to debug](docs/embedded/2.debug.md#2-use-pure-openocd-cmd-to-debug)
      - [3. use gdb to debug](docs/embedded/2.debug.md#3-use-gdb-to-debug)
  - [3.avd2rust](docs/embedded/3.svd2rust.md)
    - [Peripheral API](docs/embedded/3.svd2rust.md#peripheral-api)
      - [绕过单实例约束封装例子](docs/embedded/3.svd2rust.md#绕过单实例约束封装例子)
    - [read / modify / write API](docs/embedded/3.svd2rust.md#read--modify--write-api)
    - [Interrupt API](docs/embedded/3.svd2rust.md#interrupt-api)
  - [4.memory layout](docs/embedded/4.memory_layout.md)
  - [5.code snips](docs/embedded/5.code_snips.md)
    - [stm32f4xx\_hal crate](docs/embedded/5.code_snips.md#stm32f4xx_hal-crate)
      - [时钟配置](docs/embedded/5.code_snips.md#时钟配置)
        - [STM32 DWT cycle counter (CYCCNT) surprising behavior (rust)](docs/embedded/5.code_snips.md#stm32-dwt-cycle-counter-cyccnt-surprising-behavior-rust)
        - [PWM的代码片段](docs/embedded/5.code_snips.md#pwm的代码片段)
      - [gpio代码片段](docs/embedded/5.code_snips.md#gpio代码片段)
    - [from scratch building](docs/embedded/5.code_snips.md#from-scratch-building)
      - [The smallest #!\[no\_std\] program(binary)](docs/embedded/5.code_snips.md#the-smallest-no_std-programbinary)
  - [6.problems](docs/embedded/6.problems.md)
    - [avr问题处理](docs/embedded/6.problems.md#avr问题处理)
      - [avr-gcc](docs/embedded/6.problems.md#avr-gcc)
      - [error: cannot find macro `llvm_asm` in this scope](docs/embedded/6.problems.md#error-cannot-find-macro-llvm_asm-in-this-scope)
      - [libm  failed to compile targeting avr](docs/embedded/6.problems.md#libm--failed-to-compile-targeting-avr)
      - [avr-hal serial problem](docs/embedded/6.problems.md#avr-hal-serial-problem)
    - [arm问题处理](docs/embedded/6.problems.md#arm问题处理)
  - [7.rcit framework](docs/embedded/7.rctiframework.md)
  - [8.others](docs/embedded/8.others.md)
    - [rust-esp](docs/embedded/8.others.md#rust-esp)

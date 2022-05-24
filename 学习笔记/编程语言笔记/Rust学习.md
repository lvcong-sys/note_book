# Rust笔记

## 2022年5月10日

> 入门所遇的问题：
>
> 1. rust的安装
>
> > 因为以前安装的是gun版本的rust，所以导致cargo和rust的版本过低。解决：在软件中将rust卸载，然后安装rustup来进行安装。
>
> 2. rust的编码
>
> > 因为使用vcCode的时候默认是以gbk保存，所以导致编译项目时出现错误。解决：使用UTF-8另存文件，或者直接修改vccode的默认保存的编码格式为UTF-8一劳永逸。
>
> 3. cargo与rustup
>
>    > * cargo是rust的的包管理器和项目构建器,提供了一系列的工具，从项目的建立、构建到测试、运行直至部署，为 Rust 项目的管理提供尽可能完整的手段。同时，与 Rust 语言及其编译器== rustc== 紧密结合，可以说用了后就忘不掉，如同初恋般的感觉。如同npm。
>    >
>    >   * 包管理器和项目构建器的深层了解
>    >
>    >     > 
>    >
>    > * rustup是rust的安装和管理工具。它会自动安装rust和其编译器cargo。

## 2022年5月22日

> 1. rust中的内存泄露（圣经中有解释道）
>
>    > 在对rust中的数值类型进行赋值的时候要注意每个类型的取值范围：例如i8(有符号8位整型)的的取值范围便是-128~127。若超出这个范围则在编译时会报错。
>    >
>    > ```rust
>    > fn main(){
>    >   let a:i8  = 128;//在这段代码中IDE会有两个提示：1、a这个变量为被引用应当改为'_a'。2、i8的范围是-128..=127（rust中的序列方式）。所以128超出这个数据类型的范围。
>    > }
>    > ```
>    >
>    > 上方代码运行结果如下
>    >
>    > ![image-20220523200130136](https://raw.githubusercontent.com/lvcong-sys/note_book/master/image-20220523200130136.png)
>
> 2. rust的模块和文件
>
>    > 1. crate
>    > 2. 模板
>
> 3. 编译项目时遇到的问题
>
>    > 今天在直接使用vc code的插件code-runner运行运行以下代码时
>    >
>    > ```rust
>    > use num::complex::Complex;
>    > 
>    >  fn main() {
>    >    let a = Complex { re: 2.1, im: -1.2 };
>    >    let b = Complex::new(11.1, 22.2);
>    >    let result = a + b;
>    > 
>    >    println!("{} + {}i", result.re, result.im)
>    >  }
>    > ```
>    >
>    > 报错如下
>    >
>    > ![](https://cdn.jsdelivr.net/gh/lvcong-sys/note_book@master/16533105199331653310519077.png)
>    >
>    > 但是在终端里面使用'cargo run'运行代码的时候却没有问题
>    >
>    > 运行结果如下![](https://cdn.jsdelivr.net/gh/lvcong-sys/note_book@master/16533106459311653310645480.png)

## 2022年5月24日

> 


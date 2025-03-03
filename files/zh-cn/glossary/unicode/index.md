---
title: Unicode
slug: Glossary/Unicode
---

{{GlossarySidebar}}

Unicode 是一种{{Glossary("Character set","字符集")}}标准，用于对来自世界上不同语言、文字系统和符号进行编号和{{Glossary("Character","字符")}}定义。通过给每个字符分配一个编号，程序员可以创建{{Glossary("Character encoding","字符编码")}}，让计算机在同一个文件或程序中存储、处理和传输任何语言组合。

在 Unicode 定义之前，在同一数据中混合使用不同的语言是很困难的，而且容易出错。例如，一个字符集存储的是日文字符，而另一个字符集存储的是阿拉伯字母。如果没有明确标明数据的哪些部分属于哪个字符集，其他程序和计算机就会错误地显示文本，或者在处理过程中损坏文本。如果你曾经见过像 (`“”`) 被替换为胡言乱语 `Ã‚Â£`，那么你就已经看到过这个被称为 [Mojibake](https://zh.wikipedia.org/wiki/Mojibake) 的问题。

网络上最常见的 Unicode 字符编码是{{Glossary("UTF-8")}}。还存在一些其他编码，如 UTF-16 或过时的 UCS-2，但推荐使用 UTF-8。

## 了解更多

- [Unicode](https://zh.wikipedia.org/wiki/Unicode) on Wikipedia
- [The Unicode Standard: A Technical Introduction](https://www.unicode.org/standard/principles.html)

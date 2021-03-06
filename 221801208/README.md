# WordCount使用说明
## 如何运行
在命令行输入：
```
java WordCount input.txt output.txt
```
## 功能简介
统计input.txt中的以下几个指标
1. 统计文件的字符数（对应输出第一行）：
    - 统计Ascii码，汉字不考虑
    - 空格，水平制表符，换行符，均算字符

2. 统计文件的单词总数（对应输出第二行），单词：至少以4个英文字母开头，跟上字母数字符号，单词以分隔符分割，不区分大小写。
    - 英文字母： A-Z，a-z
    - 字母数字符号：A-Z， a-z，0-9
    - 分割符：空格，非字母数字符号
    - 例：file123是一个单词， 123file不是一个单词。file，File和FILE是同一个单词

3. 统计文件的有效行数（对应输出第三行）。
    - 任何包含非空白字符的行

4. 统计文件中各单词的出现次数（对应输出接下来10行），最终只输出频率最高的10个。
    - 频率相同的单词，优先输出字典序靠前的单词。
    - 输出的单词统一为小写格式

统计结果输出到output.txt，输出的格式如下；其中word1和word2 对应具体的单词，number为统计出的个数。

```
characters: number
words: number
lines: number
word1: number
word2: number
...
```

## 作业链接
[PersonalProject-Java](https://github.com/Trump800/PersonalProject-Java)

## 博客链接
[My Blog](https://www.cnblogs.com/SakuChyan/p/14477385.html)

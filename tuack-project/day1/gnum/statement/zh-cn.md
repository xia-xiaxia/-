{{ self.title() }}

{{ s('description') }}

对于任意整数， 我们定义如下两个性质。

- 性质 1：是偶数；
- 性质 2：大于 $4$ 且不大于 $12$。

duoluoluo 喜欢这两个性质同时成立的整数；yazhi 喜欢这至少符合其中一种性质的整数；600years 喜欢刚好有符合其中一个性质的整数；盖亚喜欢不符合这两个性质的整数。现在给出一个整数 $x$，请问他们是否喜欢这个整数？

{{ s('input format') }}

输入一个整数 $x(0\le x \le 10000)$。

{{ s('output format') }}

输出这 $4$ 个人是否喜欢这个数字，如果喜欢则输出 `1`，否则输出 `0`，用空格分隔。

输出顺序为：duoluoluo、yazhi、600years、盖亚。

{{ s('sample', 1) }}

{{ self.sample_text() }}


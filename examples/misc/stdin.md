# Standard Input

- tags: input io reader conv
- author: Brendan Hansen

This example reads a single line of input from <a href="https://en.wikipedia.org/wiki/Standard_streams">standard input</a>, splits it in half on the first space using <a href="https://docs.onyxlang.io/packages/core.string.html#bisect">string.bisect</a>, converts both parts to integers using <a href="https://docs.onyxlang.io/packages/core.conv.html#parse">conv.parse</a>, then prints the results using <a href="https://docs.onyxlang.io/packages/core.html#printf">printf</a> for formatted printing.

```onyx
{{#include stdin.onyx }}
```

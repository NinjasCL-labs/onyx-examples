# File Operations

- tags: io reader os file
- author: Brendan Hansen

This example shows various ways of reading and writing to a file. The core idea behind files in Onyx is that they extend the <code>io.Stream</code> structure, so you can use the <code>core.io</code> package to interact with them.

```onyx
{{#include files.onyx }}
```
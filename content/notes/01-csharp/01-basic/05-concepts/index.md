---
title: Concepts
weight: 5
menu:
  notes:
    name: Concepts
    identifier: notes-csharp-basics-concepts
    parent: notes-csharp-basics
    weight: 5
---

<!-- Code blocks and variable scopes -->

{{< note title="Scope" >}}

**if-else operator**

```csharp
bool flag = true;
if (flag)
{
  int value = 10;
  Console.WriteLine($"Inside the code block: {value}"); // Prints value.
}
Console.WriteLine($"Outside the code block: {value}"); // Gives error because value is declared inside the if code block.
```
{{< /note >}}

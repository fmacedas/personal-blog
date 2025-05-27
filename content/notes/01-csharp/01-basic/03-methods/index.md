---
title: Methods
weight: 3
menu:
  notes:
    name: Methods
    identifier: notes-csharp-basics-methods
    parent: notes-csharp-basics
    weight: 3
---

<!-- Stateless Method -->

{{< note title="Stateless" >}}

The following code is stateless because it doesn't require to store any state to work, you just call the static method WriteLine from Console class.

```csharp
Console.WriteLine("Hello World!");
```
{{< /note >}}

<!-- Stateful Method -->

{{< note title="Stateful" >}}

The following code is stateful because it is required to store previous information of the state to calculate next random value.

```csharp
Random dice = new Random();
int roll = dice.Next(1, 7);
```
{{< /note >}}

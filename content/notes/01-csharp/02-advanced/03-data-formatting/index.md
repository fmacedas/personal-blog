---
title: Data Formatting
weight: 3
menu:
  notes:
    name: Data Formatting
    identifier: notes-csharp-advanced-data-formatting
    parent: notes-csharp-advanced
    weight: 3
---

<!-- Composite Formatting -->

{{< note title="Composite Formatting" >}}
```csharp
string first = "Hello";
string second = "World";
string result = string.Format("{0} {1}!", first, second);
Console.WriteLine(result); // Hello World!
```
{{< /note >}}

<!-- Formatting Currency -->

{{< note title="Formatting Currency" >}}
```csharp
decimal price = 123.45m;
int discount = 50;
Console.WriteLine($"Price: {price:C} (Save {discount:C})"); // Price: $123.45 (Save $50.00)
```
{{< /note >}}

<!-- Formatting Numbers -->

{{< note title="Formatting Numbers" >}}
```csharp
decimal measurement = 123456.78912m;
Console.WriteLine($"Measurement: {measurement:N} units"); // Measurement: 123,456.79 units
Console.WriteLine($"Measurement: {measurement:N4} units"); // Measurement: 123,456.7891 units
```
{{< /note >}}

<!-- Formatting Percentage -->

{{< note title="Formatting Numbers" >}}
```csharp
decimal tax = .36785m;
Console.WriteLine($"Tax rate: {tax:P2}"); // Tax rate: 36.79%
```
{{< /note >}}




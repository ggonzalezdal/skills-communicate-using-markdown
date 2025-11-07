# Practising Markdown
## Sections
### Image
![banksy_bart](https://github.com/user-attachments/assets/79f92832-37e2-47c2-8a09-7251c77b87e5)
### Code Example
#### C# Fibonacci Sequence 
``` C#
long a = 0;
long b = 1;

Console.WriteLine($"\nFibonacci sequence for {count} numbers:");

for (int i = 0; i < count; i++)
{
    Console.Write(a + " ");
    long next = a + b;
    a = b;
    b = next;
}
Console.WriteLine();
```
Add header and subheder



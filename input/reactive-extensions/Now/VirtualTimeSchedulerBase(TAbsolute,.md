title: VirtualTimeSchedulerBase<TAbsolute, TRelative>.Now Property
---
# VirtualTimeSchedulerBase\<TAbsolute, TRelative\>.Now Property

Gets the scheduler's notion of current time.

**Namespace:**  [System.Reactive.Concurrency](System.Reactive.Concurrency\System.Reactive.Concurrency.md)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
Public ReadOnly Property Now As DateTimeOffset
    Get
```

```vb
'Usage
Dim instance As VirtualTimeSchedulerBase
Dim value As DateTimeOffset

value = instance.Now
```

```csharp
public DateTimeOffset Now { get; }
```

```c++
public:
virtual property DateTimeOffset Now {
    DateTimeOffset get () sealed;
}
```

```fsharp
abstract Now : DateTimeOffset
override Now : DateTimeOffset
```

```jscript
final function get Now () : DateTimeOffset
```

#### Property Value

Type: [System.DateTimeOffset](https://msdn.microsoft.com/en-us/library/Bb341783)  
The current time.

#### Implements

[IScheduler.Now](Now\IScheduler.Now.md)

## See Also

#### Reference

[VirtualTimeSchedulerBase\<TAbsolute, TRelative\> Class](VirtualTimeSchedulerBase\VirtualTimeSchedulerBase(TAbsolute,.md)

[System.Reactive.Concurrency Namespace](System.Reactive.Concurrency\System.Reactive.Concurrency.md)






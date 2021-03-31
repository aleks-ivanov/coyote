# SchedulingPoint class

Provides a set of static methods for declaring points in the execution where interleavings between operations should be explored during testing.

```csharp
public static class SchedulingPoint
```

## Public Members

| name | description |
| --- | --- |
| static [Deprioritize](SchedulingPoint/Deprioritize.md)() | Lowers the scheduling priority of the currently executing operation during testing. |
| static [Interleave](SchedulingPoint/Interleave.md)() | Explores a possible interleaving with another operation during testing. |

## Remarks

These methods are no-op in production.

## See Also

* namespace [Microsoft.Coyote.Runtime](../Microsoft.Coyote.RuntimeNamespace.md)
* assembly [Microsoft.Coyote](../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
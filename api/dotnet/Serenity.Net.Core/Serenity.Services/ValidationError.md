# ValidationError class
**namespace:** *[Serenity.Services](../README.md#serenity.services-namespace)*   **assembly**: *[Serenity.Net.Core](../README.md)*

Generic validation error mostly used by services.

```csharp
public class ValidationError : Exception, IIsSensitiveMessage
```

## Public Members

| name | description |
| --- | --- |
| [ValidationError](ValidationError/ValidationError.md)() | Initializes a new instance of the [`ValidationError`](ValidationError.md) class. |
| [ValidationError](ValidationError/ValidationError.md)(…) | Initializes a new instance of the [`ValidationError`](ValidationError.md) class. (5 constructors) |
| [Arguments](ValidationError/Arguments.md) { get; set; } | Gets or sets the arguments. |
| [ErrorCode](ValidationError/ErrorCode.md) { get; set; } | Gets or sets the error code. |
| [IsSensitiveMessage](ValidationError/IsSensitiveMessage.md) { get; set; } | By default all ValidationErrors are end user exceptions (e.g. message can be shown safely to the end user) |

## See Also

* interface [IIsSensitiveMessage](IIsSensitiveMessage.md)
* **Source:** *[ValidationError.cs](https://github.com/serenity-is/Serenity/blob/master/src/Serenity.Net.Core/Interface/ValidationError.cs)*
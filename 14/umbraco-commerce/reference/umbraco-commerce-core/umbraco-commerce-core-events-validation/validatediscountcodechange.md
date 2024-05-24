---
title: ValidateDiscountCodeChange
description: API reference for ValidateDiscountCodeChange in Umbraco Commerce
---
## ValidateDiscountCodeChange

```csharp
public class ValidateDiscountCodeChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateDiscountCodeChange

```csharp
public ValidateDiscountCodeChange(DiscountReadOnly discount, 
    ChangingValue<DiscountCode> discountCode)
```


### Properties

#### Discount

```csharp
public DiscountReadOnly Discount { get; }
```


---

#### DiscountCode

```csharp
public ChangingValue<DiscountCode> DiscountCode { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
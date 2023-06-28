---
title: CalculateSubOrderLinePricesTask
description: API reference for CalculateSubOrderLinePricesTask in Umbraco Commerce
---
## CalculateSubOrderLinePricesTask

```csharp
public class CalculateSubOrderLinePricesTask : 
    SubOrderLinesCalculationPipelineBase<CalculateSubOrderLinePricesTask, CalculateOrderLinePricesPipeline>
```

**Inheritance**

* class [SubOrderLinesCalculationPipelineBase&lt;TSelf,TSubOrderLinePipeline&gt;](suborderlinescalculationpipelinebase-2.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.OrderLine.Tasks](README.md)

### Constructors

#### CalculateSubOrderLinePricesTask

```csharp
public CalculateSubOrderLinePricesTask(ILogger<CalculateSubOrderLinePricesTask> logger)
```


### Methods

#### AdditionalProcessing

```csharp
public override void AdditionalProcessing(OrderLineCalculationPipelineArgs parentPipelineArgs, 
    OrderLineCalculation orderLineCalculation)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
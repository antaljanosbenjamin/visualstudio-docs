---
title: "Workflow Designer - CorrelatesOn Definition Dialog Box"
ms.date: 11/04/2016
ms.topic: reference
ms.prod: visual-studio-dev15
ms.technology: vs-workflow-designer
f1_keywords:
  - "CorrelatesOnDefinition.UI"
ms.assetid: 8b2b627a-f236-4479-aa09-525df65e3413
author: gewarren
ms.author: gewarren
manager: douge
ms.workload:
  - "multiple"
---
# CorrelatesOn Definition Dialog Box

The **CorrelatesOn** dialog box is used in Windows Workflow Designer to edit the <xref:System.ServiceModel.Activities.Receive.CorrelatesOn%2A> property of a <xref:System.ServiceModel.Activities.Receive> activity. For more information, see the [Receive](../workflow-designer/receive-activity-designer.md) topic.

The correlation between <xref:System.ServiceModel.Activities.Receive> activities specifies how different service operations connect with each other in a workflow.

The following table describes the user interface (UI) elements of the **CorrelatesOn** dialog box.

|UI Element|Description|
|----------------|-----------------|
|**CorrelatesWith**|The <xref:System.ServiceModel.Activities.CorrelationHandle> that is used to route the message to the appropriate workflow instance.|
|**XPath Queries**|A key/value pair that contains the queries used to extract correlation data from the incoming messages. This corresponds to the <xref:System.ServiceModel.Activities.Receive.CorrelatesOn%2A> property. The XPath queries are contained in a <xref:System.ServiceModel.MessageQuerySet> object.|

## To launch the CorrelatesOn dialog box

The **Receive** activity designer can be dragged from the **Toolbox** and dropped on to the Workflow Designer surface wherever activities are usually placed. This creates a <xref:System.ServiceModel.Activities.Receive> activity with a default <xref:System.Activities.Activity.DisplayName%2A> of Receive. Select the **Receive** activity designer and click the ellipsis button next to the (Collection) text for the **CorrelatesOn** property in the property grid for the **CorrelatesOn Definition** dialog box to appear.

## See also

- <xref:System.ServiceModel.Activities.Receive>
- [Add CorrelationInitializers Dialog Box](../workflow-designer/add-correlationinitializers-dialog-box.md)
- [Add Correlation Dialog Box](http://msdn.microsoft.com/en-us/9e41a149-e8ab-41b1-8886-ea06a63041b6)
- [Initialize Correlation Dialog Box](../workflow-designer/initialize-correlation-dialog-box.md)
---
UID: NF:portcls.IDrmPort.ForwardContentToInterface
title: IDrmPort::ForwardContentToInterface
description: The ForwardContentToInterface method accepts a pointer to the COM interface of an object to which the caller intends to forward protected content.
tech.root: audio
ms.assetid: 8ccec5e2-2239-4d3d-a789-f7d1800966d7
ms.author: windowsdriverdev
ms.date: 10/31/2018
ms.topic: method
ms.keywords: IDrmPort::ForwardContentToInterface, ForwardContentToInterface, IDrmPort.ForwardContentToInterface, IDrmPort::ForwardContentToInterface, IDrmPort.ForwardContentToInterface
req.header: portcls.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
 - apiref
api_type: 
 - COM
api_location: 
 - portcls.h
api_name: 
 - IDrmPort.ForwardContentToInterface
product: 
 - Windows
targetos: Windows

---

# IDrmPort::ForwardContentToInterface


## -description

The ForwardContentToInterface method accepts a pointer to the COM interface of an object to which the caller intends to forward protected content. Note that this method is identical in operation to the [DrmForwardContentToInterface](https://docs.microsoft.com/windows-hardware/drivers/ddi/content/drmk/nf-drmk-drmforwardcontenttointerface) function, and its parameter definitions and return value are also identical.



## -parameters

### -param ContentId



### -param pUnknown



### -param NumMethods




## -returns
This method returns NTSTATUS.

## -remarks
See comments in [DrmForwardContentToInterface](https://docs.microsoft.com/windows-hardware/drivers/ddi/content/drmk/nf-drmk-drmforwardcontenttointerface).


## -see-also

[IDrmPort](nn-portcls-idrmport.md)

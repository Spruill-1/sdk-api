---
UID: NF:rtworkq.RtwqSetDeadline2
title: RtwqSetDeadline2 function (rtworkq.h)
description: Sets a deadline by which the work in a work queue must be completed.
helpviewer_keywords: ["RtwqSetDeadline2","RtwqSetDeadline2 function","base.rtwqsetdeadline2","rtworkq/RtwqSetDeadline2"]
old-location: base\rtwqsetdeadline2.htm
tech.root: backup
ms.assetid: A259C9D2-9700-4FE8-81D6-7AD14476AA9C
ms.date: 12/05/2018
ms.keywords: RtwqSetDeadline2, RtwqSetDeadline2 function, base.rtwqsetdeadline2, rtworkq/RtwqSetDeadline2
req.header: rtworkq.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10 [desktop apps only]
req.target-min-winversvr: Windows Server 2016 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Rtworkq.lib
req.dll: RTWorkQ.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - RtwqSetDeadline2
 - rtworkq/RtwqSetDeadline2
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - RTWorkQ.dll
api_name:
 - RtwqSetDeadline2
---

# RtwqSetDeadline2 function


## -description



Sets a deadline by which the work in a work queue must be completed.

## -parameters

### -param workQueueId [in]

The identifier for the work queue. The identifier is returned by the <a href="/windows/desktop/api/rtworkq/nf-rtworkq-rtwqallocateworkqueue">RtwqAllocateWorkQueue</a> function.

### -param deadlineInHNS [in]

 The deadline for the work in the queue to be completed, in milliseconds.

### -param preDeadlineInHNS [in]

 The pre-deadline for the work in the queue to be completed, in milliseconds.

### -param pRequest [in, out]

Receives a handle to the request that can be used to cancel the request by calling <a href="/windows/desktop/api/rtworkq/nf-rtworkq-rtwqcanceldeadline">RtwqCancelDeadline</a>.

## -returns

If this function succeeds, it returns <b>S_OK</b>. Otherwise, it returns an <b>HRESULT</b> error code.

## -remarks

Update a deadline by creating a new deadline and releasing the old one.

Cancel a deadline by calling <a href="/windows/desktop/api/rtworkq/nf-rtworkq-rtwqcanceldeadline">RtwqCancelDeadline</a>.

## -see-also

<a href="/windows/desktop/api/rtworkq/nf-rtworkq-rtwqcanceldeadline">RtwqCancelDeadline</a>
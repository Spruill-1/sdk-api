---
UID: NS:winnt._LARGE_INTEGER~r1
title: LARGE_INTEGER
ms.date: 01/30/2019
ms.keywords: _LARGE_INTEGER, LARGE_INTEGER
targetos: Windows
req.construct-type: structure
req.ddi-compliance: 
req.dll: 
req.header: winnt.h
req.include-header: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.typenames: LARGE_INTEGER
req.umdf-ver: 
req.unicode-ansi: 
f1_keywords:
 - _LARGE_INTEGER
 - winnt/_LARGE_INTEGER
 - LARGE_INTEGER
 - winnt/LARGE_INTEGER
dev_langs:
 - c++
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - winnt.h
api_name:
 - _LARGE_INTEGER
 - LARGE_INTEGER
---

# LARGE_INTEGER structure


## -description

Represents a 64-bit signed integer value.
<div class="alert"><b>Note</b>  Your C compiler may support 64-bit integers natively. For example, Microsoft Visual C++ supports the <a href="/windows/desktop/Midl/--int64">__int64</a> sized integer type. For more information, see the documentation included with your C compiler.</div><div> </div>

## -struct-fields

### -field DUMMYSTRUCTNAME

### -field LowPart

The low-order 32 bits.

### -field HighPart

The high-order 32 bits.

### -field u

### -field QuadPart

A signed 64-bit integer.

## -remarks

The <b>LARGE_INTEGER</b> structure is actually a union. If your compiler has built-in support for 64-bit integers, use the <b>QuadPart</b> member to store the 64-bit integer. Otherwise, use the <b>LowPart</b> and <b>HighPart</b> members to store the 64-bit integer.

## -see-also

<a href="/windows/win32/api/winnt/ns-winnt-ularge_integer~r1">ULARGE_INTEGER</a>
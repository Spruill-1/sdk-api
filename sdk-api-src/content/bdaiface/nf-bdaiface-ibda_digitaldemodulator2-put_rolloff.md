---
UID: NF:bdaiface.IBDA_DigitalDemodulator2.put_RollOff
title: IBDA_DigitalDemodulator2::put_RollOff (bdaiface.h)
description: Sets the demodulator's roll-off factor.
helpviewer_keywords: ["IBDA_DigitalDemodulator2 interface [Microsoft TV Technologies]","put_RollOff method","IBDA_DigitalDemodulator2.put_RollOff","IBDA_DigitalDemodulator2::put_RollOff","bdaiface/IBDA_DigitalDemodulator2::put_RollOff","mstv.ibda_digitaldemodulator2_put_rolloff","put_RollOff","put_RollOff method [Microsoft TV Technologies]","put_RollOff method [Microsoft TV Technologies]","IBDA_DigitalDemodulator2 interface"]
old-location: mstv\ibda_digitaldemodulator2_put_rolloff.htm
tech.root: mstv
ms.assetid: ade8c334-b7b3-464e-a3ab-f8816a44a9dd
ms.date: 12/05/2018
ms.keywords: IBDA_DigitalDemodulator2 interface [Microsoft TV Technologies],put_RollOff method, IBDA_DigitalDemodulator2.put_RollOff, IBDA_DigitalDemodulator2::put_RollOff, bdaiface/IBDA_DigitalDemodulator2::put_RollOff, mstv.ibda_digitaldemodulator2_put_rolloff, put_RollOff, put_RollOff method [Microsoft TV Technologies], put_RollOff method [Microsoft TV Technologies],IBDA_DigitalDemodulator2 interface
req.header: bdaiface.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Bdaiface.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IBDA_DigitalDemodulator2::put_RollOff
 - bdaiface/IBDA_DigitalDemodulator2::put_RollOff
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - bdaiface.h
api_name:
 - IBDA_DigitalDemodulator2.put_RollOff
---

# IBDA_DigitalDemodulator2::put_RollOff


## -description

Sets the demodulator's roll-off factor.

## -parameters

### -param pRollOff [in]

Pointer to a variable that contains the roll-off factor, specified as a member of the <a href="/previous-versions/windows/desktop/mstv/rolloff">RollOff</a> enumeration.

## -returns

If this method succeeds, it returns <b>S_OK</b>. Otherwise, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/api/bdaiface/nn-bdaiface-ibda_digitaldemodulator2">IBDA_DigitalDemodulator2</a>
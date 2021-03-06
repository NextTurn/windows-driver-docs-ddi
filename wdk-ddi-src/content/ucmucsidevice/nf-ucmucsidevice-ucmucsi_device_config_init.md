---
UID: NF:ucmucsidevice.UCMUCSI_DEVICE_CONFIG_INIT
title: UCMUCSI_DEVICE_CONFIG_INIT function (ucmucsidevice.h)
tech.root: usbref
description: Initializes a **UCMUCSI_DEVICE_CONFIG** structure.
ms.date: 09/30/2018
keywords: ["UCMUCSI_DEVICE_CONFIG_INIT function"]
ms.keywords: UCMUCSI_DEVICE_CONFIG_INIT
req.header: ucmucsidevice.h
req.include-header: UcmUcsiCx.h
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 1.27
req.umdf-ver: N/A
req.lib: UcmUcsiCxStub.lib
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
ms.custom: RS5
f1_keywords:
 - UCMUCSI_DEVICE_CONFIG_INIT
 - ucmucsidevice/UCMUCSI_DEVICE_CONFIG_INIT
topic_type:
 - apiref
api_type:
 - LibDef
api_location:
 - UcmUcsiCxStub.lib
api_name:
 - UCMUCSI_DEVICE_CONFIG_INIT
---

# UCMUCSI_DEVICE_CONFIG_INIT function


## -description

Initializes a [**UCMUCSI_DEVICE_CONFIG**](ns-ucmucsidevice-_ucmucsi_device_config.md) structure.

## -parameters

### -param Config

A pointer to the **UCMUCSI_DEVICE_CONFIG** structure to initialize.

## -remarks

The client driver must call this initialization function before calling [**UcmUcsiDeviceInitialize**](nf-ucmucsidevice-ucmucsideviceinitialize.md).

## -see-also

[**EVT_WDF_DRIVER_DEVICE_ADD**](../wdfdriver/nc-wdfdriver-evt_wdf_driver_device_add.md)

[**UCMUCSI_DEVICE_CONFIG**](ns-ucmucsidevice-_ucmucsi_device_config.md)

[**WdfDeviceCreate**](../wdfdevice/nf-wdfdevice-wdfdevicecreate.md)


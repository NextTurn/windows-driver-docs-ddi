---
UID: NE:portabledevice.tagWPD_BITRATE_TYPES
title: WPD_BITRATE_TYPES (portabledevice.h)
description: The WPD_BITRATE_TYPES enumeration type describes an audio file's compression type.
old-location: wpddk\wpd_bitrate_types.htm
tech.root: wpd_dk
ms.date: 02/15/2018
keywords: ["tagWPD_BITRATE_TYPES enumeration"]
ms.keywords: WPD_BITRATE_TYPES, WPD_BITRATE_TYPES enumeration, WPD_BITRATE_TYPE_DISCRETE, WPD_BITRATE_TYPE_FREE, WPD_BITRATE_TYPE_UNUSED, WPD_BITRATE_TYPE_VARIABLE, enumeration, portabledevice/WPD_BITRATE_TYPES, portabledevice/WPD_BITRATE_TYPE_DISCRETE, portabledevice/WPD_BITRATE_TYPE_FREE, portabledevice/WPD_BITRATE_TYPE_UNUSED, portabledevice/WPD_BITRATE_TYPE_VARIABLE, tagWPD_BITRATE_TYPES, wpddk.wpd_bitrate_types
req.header: portabledevice.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: WPD_BITRATE_TYPES
ms.custom: RS5
f1_keywords:
 - tagWPD_BITRATE_TYPES
 - portabledevice/tagWPD_BITRATE_TYPES
 - WPD_BITRATE_TYPES
 - portabledevice/WPD_BITRATE_TYPES
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - PortableDevice.h
api_name:
 - tagWPD_BITRATE_TYPES
 - WPD_BITRATE_TYPES
---

# tagWPD_BITRATE_TYPES enumeration


## -description

The <b>WPD_BITRATE_TYPES</b> enumeration type describes an audio file's compression type.

## -enum-fields

### -field WPD_BITRATE_TYPE_UNUSED

This value has not been specified.

### -field WPD_BITRATE_TYPE_DISCRETE

Constant bit rate compression.

### -field WPD_BITRATE_TYPE_VARIABLE

Variable bit rate compression.

### -field WPD_BITRATE_TYPE_FREE

Free format bit rate. (This is a constant bit rate that is lower than the maximum allowed bit rate.)

## -see-also

<a href="/previous-versions/windows/hardware/drivers/ff597672(v=vs.85)">Structures and Enumeration Types</a>


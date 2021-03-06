---
UID: NS:ntddmmc._FEATURE_DATA_SECTOR_ERASABLE
title: _FEATURE_DATA_SECTOR_ERASABLE (ntddmmc.h)
description: The FEATURE_DATA_SECTOR_ERASABLE structure contains information for the Sector Erasable feature.
old-location: storage\feature_data_sector_erasable.htm
tech.root: storage
ms.date: 03/29/2018
keywords: ["FEATURE_DATA_SECTOR_ERASABLE structure"]
ms.keywords: "*PFEATURE_DATA_SECTOR_ERASABLE, FEATURE_DATA_SECTOR_ERASABLE, FEATURE_DATA_SECTOR_ERASABLE structure [Storage Devices], PFEATURE_DATA_SECTOR_ERASABLE, PFEATURE_DATA_SECTOR_ERASABLE structure pointer [Storage Devices], _FEATURE_DATA_SECTOR_ERASABLE, ntddmmc/FEATURE_DATA_SECTOR_ERASABLE, ntddmmc/PFEATURE_DATA_SECTOR_ERASABLE, storage.feature_data_sector_erasable, structs-CD-ROM_e48f2e10-1b6d-4d5a-9e8d-b1fc45fd8509.xml"
req.header: ntddmmc.h
req.include-header: Ntddcdrm.h
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
req.typenames: FEATURE_DATA_SECTOR_ERASABLE, *PFEATURE_DATA_SECTOR_ERASABLE
f1_keywords:
 - _FEATURE_DATA_SECTOR_ERASABLE
 - ntddmmc/_FEATURE_DATA_SECTOR_ERASABLE
 - PFEATURE_DATA_SECTOR_ERASABLE
 - ntddmmc/PFEATURE_DATA_SECTOR_ERASABLE
 - FEATURE_DATA_SECTOR_ERASABLE
 - ntddmmc/FEATURE_DATA_SECTOR_ERASABLE
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - ntddmmc.h
api_name:
 - _FEATURE_DATA_SECTOR_ERASABLE
 - PFEATURE_DATA_SECTOR_ERASABLE
 - FEATURE_DATA_SECTOR_ERASABLE
---

# _FEATURE_DATA_SECTOR_ERASABLE structure


## -description

The FEATURE_DATA_SECTOR_ERASABLE structure contains information for the Sector Erasable feature.

## -struct-fields

### -field Header

Contains a <a href="/windows-hardware/drivers/ddi/ntddmmc/ns-ntddmmc-_feature_header">FEATURE_HEADER</a> structure with header information for this feature descriptor.

## -remarks

This structure holds data for the feature named "Sector Erasable" by the <i>SCSI Multimedia - 4 (MMC-4)</i> specification. Devices that support this feature can erase media. These devices also require an erase pass before overwriting existing data.

When queried, devices supporting this feature must return the information indicated in <a href="/windows-hardware/drivers/ddi/ntddmmc/ns-ntddmmc-_feature_header">FEATURE_HEADER</a>. No other feature-specific information is required.

## -see-also

<a href="/windows-hardware/drivers/ddi/ntddmmc/ns-ntddmmc-_feature_header">FEATURE_HEADER</a>



<a href="/windows-hardware/drivers/ddi/ntddmmc/ne-ntddmmc-_feature_number">FEATURE_NUMBER</a>


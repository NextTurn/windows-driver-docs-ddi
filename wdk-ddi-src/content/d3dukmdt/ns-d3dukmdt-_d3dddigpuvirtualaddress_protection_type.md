---
UID: NS:d3dukmdt._D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
title: _D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE (d3dukmdt.h)
description: D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE specifies the protection on the graphics processing unit (GPU) virtual address that is mapped.
old-location: display\d3dddigpuvirtualaddress_protection_type.htm
tech.root: display
ms.date: 05/10/2018
keywords: ["D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE structure"]
ms.keywords: D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE, D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE structure [Display Devices], _D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE, d3dukmdt/D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE, display.d3dddigpuvirtualaddress_protection_type
req.header: d3dukmdt.h
req.include-header: D3dumddi.h, D3dkmddi.h
req.target-type: Windows
req.target-min-winverclnt: Windows 10
req.target-min-winversvr: Windows Server 2016
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
req.typenames: D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
f1_keywords:
 - _D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
 - d3dukmdt/_D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
 - D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
 - d3dukmdt/D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3dukmdt.h
api_name:
 - _D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
 - D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE
---

# _D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE structure


## -description

<b>D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE</b> specifies the protection on the graphics processing unit (GPU) virtual address that is mapped.

## -struct-fields

### -field Write

The pages will be allowed read-write access.

### -field Execute

The pages will be allowed execute access.

### -field Zero

The pages will be put to the <i>zero</i> state.

### -field NoAccess

The pages will be put to the <i>invalid</i> state.

### -field SystemUseOnly

This member is for system use only and should not be set by the user mode driver.

### -field Reserved

This member is reserved and should be set to zero.

### -field Value

The consolidated value of the structure's members.


---
title: KSPROPERTY\_BDA\_CA\_SET\_PROGRAM\_PIDS
description: Clients use KSPROPERTY\_BDA\_CA\_SET\_PROGRAM\_PIDS to set the list of packet identifiers in a particular program.
ms.assetid: 5cc049f7-df97-4739-8ec4-22ab646781a6
keywords: ["KSPROPERTY_BDA_CA_SET_PROGRAM_PIDS Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_BDA_CA_SET_PROGRAM_PIDS
api_location:
- Bdamedia.h
api_type:
- HeaderDef
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# KSPROPERTY\_BDA\_CA\_SET\_PROGRAM\_PIDS


Clients use KSPROPERTY\_BDA\_CA\_SET\_PROGRAM\_PIDS to set the list of packet identifiers in a particular program.

## <span id="ddk_ksproperty_bda_ca_set_program_pids_ks"></span><span id="DDK_KSPROPERTY_BDA_CA_SET_PROGRAM_PIDS_KS"></span>


### <span id="Usage_Summary_Table"></span><span id="usage_summary_table"></span><span id="USAGE_SUMMARY_TABLE"></span>Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Filter</p></td>
<td><p>KSP_NODE</p></td>
<td><p>BDA_PROGRAM_PID_LIST</p></td>
</tr>
</tbody>
</table>

 

Remarks
-------

The BDA\_PROGRAM\_PID\_LIST structure contains the list of packet identifiers for a specified program.

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Bdamedia.h (include Bdamedia.h)</td>
</tr>
</tbody>
</table>

## <span id="see_also"></span>See also


[**BDA\_PROGRAM\_PID\_LIST**](https://msdn.microsoft.com/library/windows/hardware/ff556549)

[**KSEVENT\_BDA\_PROGRAM\_FLOW\_STATUS\_CHANGED**](ksevent-bda-program-flow-status-changed.md)

[**KSP\_NODE**](https://msdn.microsoft.com/library/windows/hardware/ff566720)

 

 






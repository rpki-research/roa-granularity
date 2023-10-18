# ROA granularity

This repository stores part of (due to GitHub's repository size limit) the data used for analyzing ROA granularity.

**rrc00_po_pairs** contains the extracted and de-duplicated (prefix,origin AS) pairs from the RIB table of collector rrc00 for July 2023, in the format of *'Prefix|Origin AS'*.

**po_pairs_230721** contains the extracted and de-duplicated (prefix,origin AS) pairs from the RIB tables of 57 collectors provided by projects RouteViews and RIPE RIS for July 21 2023, in the format of *'Prefix|Origin AS'*.

**VRP_sets** contains the VRP set for July 2023, and the VRP set for each day is a JSON file, which contains VRP entries valid for that day, with three fields: *ASN, Prefix and maxLength*.

**unique_VRPs** contains all unique VRPs and their lifecycles since the deployment of RPKI, in the format of *'ASN,Prefix,maxLength,start_time,end_time'*.

Some files are ***empty*** because the corresponding collectors had no data for that day.
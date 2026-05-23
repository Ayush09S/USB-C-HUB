# USB-C-HUB

# Zine!
<img width="539" height="827" alt="Zine" src="https://github.com/user-attachments/assets/cdfe5cda-1033-445f-84db-ef13a4d7ea3b" />


# Context
Hi! This is a project I've decided to build that aims to be my first project for the Fallout Program run by Hack Club. I've learnt to create a pcb for the first time, used new software (I used EasyEda) and learnt the way in which pcb's are properly designed, and not properly designed. For example, when using data connectors, DO NOT use the auto-routing tool. It took away from both the fun and the actual working function of the circuit board. Also, AI sucks to check pcbs. Either I'm not understanding something properly, or it sucks. I decide to choose that it sucks. I'll ask for a sanity-check in fallout through slack.

# How to make
1. Order the PCB (from somewhere like JLCPCB)
   OR
   Cut it out with a CNC
   Both with the Gerber folder provided
2. 3D Print the casing from the CAD file provided
3. Ensure you have the right Screws and Nuts as listed in the BOM (easy and cheap to order from Aliexpress)
4. Put it together! Screw in the screws and fasten the nuts to keep it together! You should now be able to plug it in.

# CAD Design
Note-to-self, use tinkercad for simplicity. Still need to complete. Use multiple images.
<img width="1011" height="621" alt="Screenshot 2026-04-28 at 10 54 51 pm" src="https://github.com/user-attachments/assets/dc3df69b-cb61-4c2e-afd9-ce8307952ecc" />
<img width="1019" height="731" alt="Screenshot 2026-04-28 at 10 54 32 pm" src="https://github.com/user-attachments/assets/77f7b112-7345-46ca-8f23-8b4584331d4c" />
<img width="1202" height="743" alt="Screenshot 2026-04-28 at 10 56 06 pm" src="https://github.com/user-attachments/assets/a05ba10f-ec37-4df1-b3fb-fe20ff38f8df" />
<img width="988" height="709" alt="Screenshot 2026-04-28 at 10 55 16 pm" src="https://github.com/user-attachments/assets/2add7911-f07c-41a6-8499-2c8dfe5fc5d6" />
<img width="1268" height="648" alt="Screenshot 2026-04-28 at 10 56 24 pm" src="https://github.com/user-attachments/assets/dc9ddc63-3fbc-476d-a2c4-490b3dbb62a3" />

# Wiring Diagram
Note-to-self, use multiple views and color coding to convey information. Still need to complete

<img width="1406" height="990" alt="Screenshot 2026-04-28 at 11 07 24 pm" src="https://github.com/user-attachments/assets/44a73554-0ded-4b66-b3e7-61b9e3eaa50f" />
<img width="1013" height="974" alt="Screenshot 2026-04-28 at 11 08 53 pm" src="https://github.com/user-attachments/assets/1922add0-4523-48ff-b9ad-f23f873c4aa9" />
<img width="970" height="964" alt="Screenshot 2026-04-28 at 11 09 34 pm" src="https://github.com/user-attachments/assets/f73ec0dc-aa16-4d2d-afbf-97081f8f9f19" />
<img width="1081" height="1065" alt="Screenshot 2026-04-28 at 11 29 54 pm" src="https://github.com/user-attachments/assets/91d88718-7bd8-4466-ae02-511035528a46" />
<img width="1281" height="1112" alt="Screenshot 2026-04-28 at 11 15 20 pm" src="https://github.com/user-attachments/assets/e419b179-a7fd-492e-a177-c3884ecca9e4" />
(I'd suggest black for the pcb build color)

# Specs
4 Outputs, 1 Input

Output:
- 2x Usb2.0 A
- 2x Usb-C

Input:
- 1x Usb-C

# BOM (All in AUD)

No.|Item|  Description  | Requested Qty |Min Order Qty|Unit Price|Total Price|Running Total| Link
---|----|---------------|---------------|-------------|----------|-----------|-------------|------
 1 | 3D Printer| Bambu X1C AVAILABLE AT SCHOOL | 1 | 1 | $1099.00 | $1099.00 | $21.30 | https://www.mobileciti.com.au/bambu-lab-x1-carbon-3d-printer-with-ams-refur-excellent?gclid=Cj0KCQjwoMXQBhDcARIsAH-eEtv6DcY8bJ5KFvRXVKA8ApDhx15VS-7CEkVGBmmQL9fcapztwOnEn9AaAqIYEALw_wcB&utm_medium=ppc&utm_campaign=00_Smart+Shopping+campaign&utm_term=&utm_source=adwords&hsa_src=x&hsa_acc=4638778441&hsa_mt=&hsa_grp=&hsa_ad=&hsa_tgt=&hsa_net=adwords&hsa_ver=3&hsa_cam=1578143160&hsa_kw=&gad_source=1&gad_campaignid=17417661961&gbraid=0AAAAAD-y5hW1onLIU-sxGjRVv_D7dO2qU
 2 | Screws | M2x18mm | 4 | 25 | $0.06 | $3.70 | $25.00 |https://www.aliexpress.com/item/1005005841287178.html?src=google&src=google&albch=shopping&acnt=179-224-6891&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=_oFgTQeV&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005005841287178&ds_e_product_merchant_id=107907811&ds_e_product_country=AU&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=23109426145&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=23109428320&gbraid=0AAAABBR8xId8V1CaMwpJNadhfpnStSTf4&gclid=Cj0KCQjwoMXQBhDcARIsAH-eEtt8P-ByHrxdFp6WYVdqjZv07RoKa5KXCZU_p0B7Su_xA6ctL3eb8h8aApRpEALw_wcB 
 3 | Nuts | M2 | 4 | 25 | $0.06 | $3.71 | $28.71 | https://www.aliexpress.com/item/32988995881.html?spm=a2g0o.productlist.main.1.68a733d4BXz6UR&algo_pvid=2115fbf9-60f4-46f9-a87d-f6827d534282&algo_exp_id=2115fbf9-60f4-46f9-a87d-f6827d534282-0&pdp_ext_f=%7B%22order%22%3A%225324%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21AUD%212.52%211.41%21%21%211.77%210.99%21%40210311a017795282089784201e4b31%2166897480663%21sea%21AU%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A8bcdc914%3Bm03_new_user%3A-29895%3BpisId%3A5000000204867275&curPageLogUid=6GkJlTjxoej9&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A32988995881%7C_p_origin_prod%3A#nav-description
 4 | PCB| Circuit Board (Below is specifics |       1       |      5      |   $4.3  |   $21.30  |    $21.30 | Order from https://jlcpcb.com/

# Additional Notes
Guided project through Hack Club's Fallout Docs. Was incredible fun and would definitely recommend to others for starter project!

For Github page inspo:
https://github.com/daaminashai/mhmhub
https://github.com/geg-tech/biblicallyaccuratekeyboard

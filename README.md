# game32

Hey, this is the game32 that i made to be able to practice programming in c++ and to have a versitile device to test my code on. This is the first iteration, eventually it will be battery powered and have a better layout. 

This board is powered with a esp32 s3, and has a tft display driven with a st7789. 

It is a 2 layer board: 

Top layer:

<img width="502" height="430" alt="image" src="https://github.com/user-attachments/assets/720fd8af-a352-4c1e-a805-8f6e827bd028" />

Bottom Layer:

<img width="509" height="433" alt="image" src="https://github.com/user-attachments/assets/72ee7c99-cbb9-46dc-b0b5-1a59a9bbba1d" />

Bill of materials, its pretty messy, so open the file is you want to see it cleaner:

No.	Quantity	Comment	Designator	Footprint	Value	Manufacturer Part	Manufacturer	Supplier Part	Supplier

1	8	TS-1088-AR02016	1,2,3,4,5,6,7,8	SW-SMD_L3.9-W3.0-P4.45			XUNPU(讯普)	C720477	LCSC	

2	1	HDR-M_2.54_1x2P	3v3	HDR-TH_2P-P2.54-V-M-1				C32713268	LCSC	

3	1	boot	boot	SW-SMD_L3.9-W3.0-P4.45		boot	XUNPU(讯普)	C720477	LCSC	

4	1	100nF	C1	C0603	100nF	CC0603KRX7R9BB104	YAGEO(国巨)	C14663	LCSC	

5	1	22uF	C2	C0805	22uF	CL21A226MAQNNNE	SAMSUNG(三星)	C45783	LCSC	

6	1	10uF	C3	C0805	10uF	GRM21BR61H106KE43L	muRata(村田)	C440198	LCSC	

7	4	100nF	C4,C6,C7,C8	C0603	100nF			C1590	LCSC	

8	1	10uf	C5	C0603	10uf			C1691	LCSC	
9	1	TF-01A	CARD1	TF-SMD_TF-01A		TF-01A	韩国韩荣	C91145	LCSC	

10	1	en	en	SW-SMD_L3.9-W3.0-P4.45		en	XUNPU(讯普)	C720477	LCSC	

11	1	FPC-05FB-50PH20	FPC1	FPC-SMD_50P-P0.50_FPC-05FB-50PH20		FPC-05FB-50PH20	XUNPU(讯普)	C2856838	LCSC	

12	1	HDR-M_2.54_1x8P	H1	HDR-TH_8P-P2.54-V-M				C32713274	LCSC	

13	1	LED_0603-B	LED1	LED0603-R-RD				C965807	LCSC	

14	1	K3-1280S-F1	on	SW-SMD_K3-1280S-K1		K3-1280S-F1	韩国韩荣	C92658	LCSC	

15	1	LBSS138LT1G	Q1	SOT-23_L2.9-W1.3-P1.90-LS2.4-BR		LBSS138LT1G	LRC(乐山无线电)	C8490	LCSC	

16	1	100	R2	R0603	100			C22775	LCSC	

17	2	10K	R3,R8	R0603	10K			C25804	LCSC	

18	4	10	R4,R5,R6,R7	R0402	10			C25077	LCSC	

19	2	5.1k	R9,R10	R0603	5.1k			C23186	LCSC	

20	1	ESP32-S3-WROOM-1-N16R8	U1	WIRELM-SMD_ESP32-S3-WROOM-1		ESP32-S3-WROOM-1-N16R8	ESPRESSIF(乐鑫)	C2913202	LCSC	

21	1	MCP23017-E/SS	U2	SSOP-28_L10.2-W5.3-P0.65-LS7.8-BL		MCP23017-E/SS	MICROCHIP(美国微芯)	C506653	LCSC	

22	1	AP2112K-3.3TRG1	U3	SOT-25-5_L2.9-W1.6-P0.95-LS2.8-BL		AP2112K-3.3TRG1	DIODES(美台)	C51118	LCSC	

23	1	918-418K2023C40002	USBC1	USB-C-SMD_C67380		918-418K2023C40002	精拓金	C67380	LCSC	
										

The fastest NFC emulator

Which MCU can emulate a mifare 1 card?
Try to run the example trace in the file "fixed-nonce-data.txt" on it, 
and if the last FDT is less than 5, it's performance is very good.
If the last FDT is less than 1, it is the perfect MCU for emulate mifare 1 card.

[Ps] [Mifare]Read Block Command: 30 08 4A 24 
-->[Ps] [Mifare]Read Block Command enc: 1D 62 37 0B 
	[Ps] [RF14443A]FDT Delay: 1    --------------- the last FDT
<--[Ps] [Mifare]Read Block Recv: 7E B3 CA 4C C2 F8 11 A2 7D B9 61 84 41 48 E9 F2 C4 89 


<img width="277" height="182" alt="image" src="https://github.com/user-attachments/assets/ad0da36e-3f9e-46f2-9f9d-886d396e2082" />


# CC101 - 433Mhz RF Receiver

CC101 Connection to Arduino Uno

<img width="577" height="271" alt="image" src="https://github.com/user-attachments/assets/7336fdfe-f49f-4bc2-863d-53540441d6c4" />


	•	CC1101 VCC → 3.3V (not 5V!)
	•	CC1101 GND → GND
	•	CSn → D10
	•	MOSI → D11
	•	MISO → D12
	•	SCLK → D13
	•	GDO0 → D2 (INT0)

The UNO is 5 V logic but CC1101 is 3.3 V-only. Use level shifting if you can (at least on MOSI/SCK/CSn and GDO0 back into the UNO).

# Stenugnsbageriet Olof
Vi bakar surdegsbröd, bullar och kakor med smör, kärlek och öländskt lantvetemjöl.

## Kylutrymmen

Målet är att hålla koll på temperatur i kylutrymmen. Få reda på om dörren till kylutrymmet är öppet. Syftet är att veta om kylen är trasig eller har lämnats öppen och förhindra att matvaror blir dåliga.

### Välja nätverksteknologi

För det här projektet utforskas LORA Zigbee och WiFi som alternativ till att sckicka datan. Aspekter som är viktiga för bageriet är att det ska vara relativt billigt att köp in det som behövs. Det ska vara lätt att underhålla. Det ska hälst inte bövas att man sätter upp sig på några nya abonemang. För att lösningen ska funka krävs det också att signalen tar sig igenom de tjocka väggarna på kyl och frysutrymmet.

|Teknologi|Inledande kostnad|Kräver abonemang|Batteritid|Räckvidd innomhus|
|-|-|-|-|-|
|LORA|Hög|Inte nödvändigtvis|Väldigt lång |10-15 km|
|Zigbee|Låg|Inte nödvändigtvis|Lång|10-20 m|
|WiFi|Låg|Inte Utöver befintligt WiFi|Eventuellt kortare|upp till 50 m|

### Disskusion med Anna
Zigbee verkar kul för att man kan bygga vidare på det och inkludera saker som smarta lampor. Ikea känns som ett bra företag att köpa hubb ifrån. Wifi är värt att fortsätta undersöka som alternativ till Zigbee.

### Sensorförslag

Här följer 2 förslag på upsättningar av sensorer som kan köpas tillsammans.

|Gateway| Sensor | antal | totalt pris |
|-|-|-|-|-|
||


|Gateway| Sensor | antal | totalt pris |
|-|-|-|-|-|
||

### Förslag på dörrsensor som bara är larm
Denna typ av sensorer faller inte in under IOT, men det kanske är vad som bäst skulle fylla de behov som finns i bageriet. 
|Länk|pris|Batteritid|Användbar funktion|
|----|----|----------|------------------|
|[Fridggi](https://www.amazon.com/FRIDGGI-Freezer-Fridge-Delays-120sec/dp/B08B4H3LM8/ref=sr_1_1_sspa?keywords=Refrigerator%2BDoor%2BAlarm&qid=1698155334&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)|22.64$|1 år|Olika typer av larm kan ställas in. Exempel 1: Mjukt larm efter en minut, påminnelse efter 2 minuter. Exempel 2: Ihållande larm efter 3 minuter.|
|[WSDCAM](https://www.amazon.com/Freezer-Seconds-Adjustable-Wireless-Refrigerator/dp/B08LMTF8GM/ref=sr_1_4?keywords=Refrigerator+Door+Alarm&qid=1698155334&sr=8-4)|22.99$|Ingen information|Larmar om dörren varit öppen i 3/15/30 eller 60 sekunder.|
|[Freezer Door Alarm](https://www.amazon.com/Freezer-Window-Reminder-Office-School/dp/B0BX9FZ6CB/ref=sr_1_6?keywords=Refrigerator%2BDoor%2BAlarm&qid=1698155334&sr=8-6&th=1)|16.99 $|ingen information|Kan ställas in att larma efter 30 sekunder. Påminelse var 20e sekund. Slutar efter en timme, eller när dörren stängs|

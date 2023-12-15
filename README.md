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

#### Förslag 1
|Gateway| Sensor | antal | totalt pris |
|-|-|-|-|
||

#### Förslag 2
|Gateway| Sensor | antal | totalt pris |
|-|-|-|-|
||

### Förslag på dörrsensor som bara är larm
Denna typ av sensorer faller inte in under IOT, men det kanske är vad som bäst skulle fylla de behov som finns i bageriet. 
|Länk|pris|Batteritid|Användbar funktion|
|----|----|----------|------------------|
|[Fridggi](https://www.amazon.com/FRIDGGI-Freezer-Fridge-Delays-120sec/dp/B08B4H3LM8/ref=sr_1_1_sspa?keywords=Refrigerator%2BDoor%2BAlarm&qid=1698155334&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)|22.64$|1 år|Olika typer av larm kan ställas in. Exempel 1: Mjukt larm efter en minut, påminnelse efter 2 minuter. Exempel 2: Ihållande larm efter 3 minuter.|
|[WSDCAM](https://www.amazon.com/Freezer-Seconds-Adjustable-Wireless-Refrigerator/dp/B08LMTF8GM/ref=sr_1_4?keywords=Refrigerator+Door+Alarm&qid=1698155334&sr=8-4)|22.99$|Ingen information|Larmar om dörren varit öppen i 3/15/30 eller 60 sekunder.|
|[Freezer Door Alarm](https://www.amazon.com/Freezer-Window-Reminder-Office-School/dp/B0BX9FZ6CB/ref=sr_1_6?keywords=Refrigerator%2BDoor%2BAlarm&qid=1698155334&sr=8-6&th=1)|16.99 $|ingen information|Kan ställas in att larma efter 30 sekunder. Påminelse var 20e sekund. Slutar efter en timme, eller när dörren stängs|

## Instruktioner

### Installation av appen Smart Life - Smart Living

Ladda ner appen

![Alt text](1_1.jpg)

_______________________________
Skappa nytt konto

![Alt text](1_2-2.jpg)

_______________________________
Skriv din e-post, godkänn villkoren och sedan välj Get Verification Code

![Alt text](1_3.jpg)

________________________________
Skriv in verifikationskod som du fått i din e-post.

![Alt text](1_5-2.jpg)

________________________________
Skriv ett lösenord och välj sedan Klart.

![Alt text](1_4-1.jpg)

_________________________________
Välj Go to App.

![Alt text](1_5-3.jpg)

__________________________________
Appen är nu installerad.

![Alt text](1_6.jpg)

________________________________

### Installation av Gateway Cleverio SG100

Gateway Cleverio SG100

![Alt text](1_1-1.jpg)

_______________________________
Öppna appen och välj Lägg till enhet.

![Alt text](1_2-3.jpg)

_______________________________
Välj Gateway Control I vänstra fliken.

![Alt text](1_3-1.jpg)

_______________________________
Välj Gateway (Zigbee). Samma som på bilden.

![Alt text](1_4-2.jpg)

_______________________________
Koppla till Wi-Fi (Viktigt att det är 2.4 Ghz. Välj sedan Nästa.

![Alt text](1_5-4.jpg)

_______________________________
Välj Next.

![Alt text](1_6-1.jpg)

_______________________________
Håll RESET 5 sekunder och välj Next. 

![Alt text](1_7.jpg)
![Alt text](1_8.jpg)

_______________________________
Välj Blink Quickly eller Blink Slowly.

![Alt text](1_9.jpg)

_______________________________
Vänta tills enheten hittats.

![Alt text](1_10.jpg)

_______________________________
Enheten är nu hittad. Välj Klart.

![Alt text](1_11.jpg)

________________________________
Appens Startvy med Cleverio SG100 gateway installerad

![Alt text](1_12.jpg)

_____________________________________
### Installation av dörrsensor Cleverio SS100




Dörrsensor Cleverio SS100

![Alt text](1_1-2.jpg)

________________________________
Startvyn i appen heter ”Min familj”

![Alt text](1_2-4.jpg)

_______________________________
Välj +

![Alt text](1_3-2.jpg)

________________________________
Välj Add Device

![Alt text](1_4-3.jpg)

________________________________
Välj först Sensors i fliken till vänster och sedan Sensor (Zigbee) i fliken till höger.

![Alt text](1_5-5.jpg)

_______________________________
Välj Cleverio SG100

![Alt text](1_6-2.jpg)

_________________________________
Håll i RESET-knappen i 5 sekunder för att det ska blinka

![Alt text](1_7-1.jpg)

________________________________
Bocka i Comfirm the indicator blinking och tryck på Next.

![Alt text](1_8-1.jpg)

__________________________________
 Välj Klart. Sensorn är nu installerad.

 ![Alt text](1_9-1.jpg)

 _________________________________
 Välj bakåtpilen för att komma tillbaka till Startvyn.

![Alt text](1_10-1.jpg)

_________________________________
Startvy. Cleverio SS100 installerad.

![Alt text](1_11-1.jpg)

__________________________________

### Installation av Temperatur- och fuktighetsmätare Aqara


Temperatur- och fuktighetsmätare Aqara

![Alt text](1_1-3.jpg)

__________________________________
 Börja från appens Startvy och välj +

 ![Alt text](1_2-5.jpg)

 _________________________________
 Välj Add Device.

 ![Alt text](1_3-3.jpg)

 __________________________________
 Välj Sensors i fliken till vänster och sedan välj Temperatur och fuktighetsgivare (Zigbee) i fliken till höger. 

![Alt text](1_4-4.jpg)

__________________________________
Välj Cleverio SG100.

![Alt text](1_5-6.jpg)

___________________________________
Tryck på RESET-knappen tills det börjar blinka snabbt.

![Alt text](1_6-3.jpg)

___________________________________
Nu är sensorn hittad. Välj Klart.

![Alt text](1_7-2.jpg)

____________________________________
Välj pil bakåt för att gå till Startvyn.

![Alt text](1_8-2.jpg)

____________________________________
Startvy. Samtliga enheter är nu installerade.

![Alt text](1_9-2.jpg)


______________________________________

### Exempel på att inställning av funktioner för dörrsensor


Cleverio SS100

![Alt text](1_1-4.jpg)

_____________________________________
Välj Scene från Startvyn.

![Alt text](1_2-6.jpg)

____________________________________
Välj först fliken Tap-to-Run och välj sedan Create scene.

![Alt text](1_3-4.jpg)

___________________________________
Välj When device status changes

![Alt text](1_4-5.jpg)

___________________________________
Välj Cleverio SS100.

![Alt text](1_5-7.jpg)

___________________________________
Välj Door and window sensor

![Alt text](1_6-4.jpg)

___________________________________
Välj "ON” Varaktighet.

![Alt text](1_7-3.jpg)

_____________________________________
Justera önskad tid efter hur länge som dörren ska vara öppen innan det larmar. Välj Nästa.

![Alt text](1_8-3.jpg)

___________________________________
Välj + på Then

![Alt text](1_9-3.jpg)

__________________________________
Välj Control Single Device.

![Alt text](1_10-2.jpg)

_______________________________
Välj Cleverio SG100.

![Alt text](1_11-2.jpg)

______________________________
Välj Alarm och sedan Spara.

![Alt text](1_12-1.jpg)

______________________________
Välj Nästa.

![Alt text](1_13.jpg)

______________________________
Välj + på Then

![Alt text](1_14.jpg)

______________________________
Välj Send notification.

![Alt text](1_15.jpg)

______________________________
Välj message center (gratis meddelande) och sedan välj Nästa.

![Alt text](1_16.jpg)

________________________________
Välj Spara.

![Alt text](1_17.jpg)

__________________________________
Skriv namn på funktionen.

![Alt text](1_18.jpg)

__________________________________
Välj Bekräfta.

![Alt text](1_19.jpg)

_________________________________
Välj Yes.

![Alt text](1_20.jpg)

_________________________________
Funtionen är nu sparad och aktiv vid grönt. Kan avaktiveara den vid behov genom att trycka på grön knapp.

![Alt text](1_21.jpg)

_________________________________
Välj Tap-to-Run. 

![Alt text](1_22.jpg)

____________________________________
Välj Create Scene.

![Alt text](1_23.jpg)

____________________________________--
Välj When device status changes.

![Alt text](1_24.jpg)

____________________________________
Välj Cleverio SS100

![Alt text](1_25.jpg)

___________________________________
Välj Door and window sensor

![Alt text](1_26.jpg)

__________________________________
Välj off.

![Alt text](1_27.jpg)

_________________________________
Välj +

![Alt text](1_28.jpg)

_________________________________
Välj Control Single Device

![Alt text](1_29.jpg)

________________________________
Välj Cleverio SG100

![Alt text](1_30.jpg)

________________________________
Välj Gateway status

![Alt text](1_31.jpg)

_______________________________
Välj Normal och sedan välj Spara

![Alt text](1_32.jpg)

________________________________
 Välj Spara

 ![Alt text](1_33.jpg)

 ________________________________
 Skriv ett namn till funktionen och välj Bekräfta

 ![Alt text](1_34.jpg)

 _______________________________
 Välj Yes

 ![Alt text](1_35.jpg)

 __________________________________
 Funktioner är nu programmerade. Alarm och meddelande går efter att dörren varit öppen mer än 30 sekunder och alarm stängs av när sensorn känner attdörren har stängts.

 ![Alt text](1_36.jpg)

 
 ___________________________________


 ### Exempel på att inställning av funktioner för temperatur- och fuktighetsmätare


 Temperatur- och fuktighetsmätare Aqara

 ![Alt text](1_1-5.jpg)

 ________________________________________
 Välj Scene från Startsvyn.

 ![Alt text](1_2-7.jpg)

 _______________________________________
 Välj först fliken Tap-to-Run och välj sedan Create scene.

 ![Alt text](1_3-5.jpg)

 ______________________________________
 Välj When device status changes.

 ![Alt text](1_4-6.jpg)

 _____________________________________
 Välj Temperature and humidity sensor.

 ![Alt text](1_5-8.jpg)

 _____________________________________
 Välj Temperature.

 ![Alt text](1_6-5.jpg)

 ___________________________________
Justera efter önskemål/behov och välj Nästa.

![Alt text](1_7-4.jpg)

___________________________________
Välj + på Then

![Alt text](1_8-4.jpg)

____________________________________
Välj Control Single Device

![Alt text](1_9-4.jpg)

______________________________________
Välj Cleverio SG100.

![Alt text](1_10-3.jpg)

____________________________________
Välj Gateway status.

![Alt text](1_11-3.jpg)

___________________________________
Välj Alarm och Spara.

![Alt text](1_12-2.jpg)

_________________________________
Välj Nästa.

![Alt text](1_13-1.jpg)

____________________________________
Välj + på Then

![Alt text](1_14-1.jpg)

___________________________________
Välj Send notification.

![Alt text](1_15-1.jpg)

__________________________________
Välj Message Center (den är gratis). Välj sedan Nästa.

![Alt text](1_16-1.jpg)

___________________________________
Välj Spara.

![Alt text](1_17-1.jpg)

__________________________________
Skriv namn för funktionen t.ex. “Temperatur över/Alarm på” och sedan välj Bekräfta.

![Alt text](1_18-1.jpg)

________________________________
Nu är samtliga funktioner installerade. Alarm på när temperaturen överstiger 8 plus grader samt dörr öppen mer än 30 sekunder.
Välj Min familj för att gå tillbaka till Startvy.


![Alt text](1_19-1.jpg)



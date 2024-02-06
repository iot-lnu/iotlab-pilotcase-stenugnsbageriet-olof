# Stenugnsbageriet Olof

Stenugnsbageriet Olof är ett bageri som bakar surdegsbröd, bullar och kakor med smör, kärlek och öländskt lantvetemjöl.

- [Om projektet](#om-projektet)
- [Kommunikationsteknologier](#kommunikationsteknologier)
  - [LoRaWAN](#lorawan)
  - [Zigbee](#zigbee)
  - [WiFi](#wifi)
  - [Val av teknologi](#val-av-teknologi)
- [Hårdvaruförslag](#hårdvaruförslag)
  - [Gateway](#gateway)
  - [Sensorer](#sensorer)
- [Instruktioner](#instruktioner)

## Om projektet

Syftet med projektet är att övervaka temperaturen i kylutrymmena och få information om när dörrarna till dessa utrymmen står öppna. Detta görs för att kunna avgöra om kylen är trasig eller om den har lämnats öppen av misstag, med målet att förhindra att matvaror försämras eller blir dåliga.

## Kommunikationsteknologier

Vi börjar med att undersöka LoRaWAN, Zigbee och WiFi som möjliga alternativ för dataöverföring. Det är viktigt för bageriet att lösningen är kostnadseffektiv vid inköp och enkel att underhålla. Helst bör det inte krävas några nya abonnemang. Dessutom måste tekniken kunna penetrera de tjocka väggarna i kyl- och frysförvaringsutrymmena för att fungera effektivt.

| Teknologi                                                 | Inledande kostnad | Kräver abonnemang           | Batteritid   | Räckvidd      |
| --------------------------------------------------------- | ----------------- | --------------------------- | ------------ | ------------- |
| [LoRaWAN](https://www.thethingsnetwork.org/docs/lorawan/) | Hög               | Inte nödvändigtvis          | Väldigt lång | 10-15 km      |
| Zigbee                                                    | Låg               | Inte nödvändigtvis          | Lång         | 10-20 m       |
| WiFi                                                      | Låg               | Inte utöver befintligt WiFi | kortare      | upp till 50 m |

### LoRaWAN

LoRaWAN står ut som ett alternativ för långdistanskommunikation med sin imponerande räckvidd på 10-15 km och en batteritid som kan vara mycket lång, vilket gör det idealiskt för projekt där låg energiförbrukning och bred täckning är avgörande. Den högre inledande kostnaden kan motiveras av dess förmåga att skicka data över långa avstånd utan behov av frekventa batteribyten. Detta gör LoRaWAN till ett attraktivt val för att övervaka avlägsna eller svårtillgängliga platser utan att nödvändigtvis kräva nya abonnemang.

### Zigbee

Zigbee utmärker sig genom sin låga inledande kostnad och förmågan att skapa pålitliga lokala nätverk med lång batteritid, men med en mer begränsad räckvidd på 10-20 meter. Detta gör Zigbee idealiskt för smarta hem-applikationer och inomhus övervakningssystem där enheterna kan interagera nära varandra utan att behöva ett abonnemang. Zigbee-nätverk är också skalbara och flexibla, vilket gör det enkelt att lägga till fler enheter över tid, såsom smarta lampor och sensorer.

### WiFi

WiFi erbjuder en bekant teknologi med låg inledande kostnad och är redan närvarande i många miljöer, vilket eliminerar behovet av ytterligare abonnemang för datatransmission inom dess täckningsområde. Med en räckvidd på upp till 50 meter är WiFi väl lämpat för inomhusmiljöer och kan enkelt integreras med befintlig IT-infrastruktur. Dock har WiFi en kortare batteritid jämfört med LoRaWAN och Zigbee, vilket kan vara en begränsning för batteridrivna enheter.

### Val av teknologi

Efter en diskussion med bageriet framkom det att Zigbee verkar vara ett passande val, eftersom det erbjuder möjligheten att utöka systemet med ytterligare smarta enheter, som till exempel smarta lampor. Ikeas hubb anses också vara ett alternativ för inköp av en central hubb. Dessutom bedömdes WiFi som ett intressant alternativ att fortsätta utforska vid sidan av Zigbee.

## Hårdvaruförslag

Den valda teknologin är Zigbee. Här följer förslag på sensorer och en gateway som kan köpas tillsammans.

### Gateway

För att kunna använda Zigbee behövs en gateway. Följande gateway föreslås. Den har även en inbyggd buzzer som kan användas för att skicka ljudsignaler vid händelser, till exempel när en dörr står öppen. Volymen kan justeras.

| Gateway                                                                                                              | Antal | Pris   |
| -------------------------------------------------------------------------------------------------------------------- | ----- | ------ |
| [Smart Gateway SG100](https://www.kjell.com/se/produkter/smarta-hem/controllers/cleverio-sg100-smart-gateway-p51825) | 1     | 499 kr |

### Sensorer

Följande sensorer föreslås för att övervaka kylutrymmena och kylskåpsdörrarna.

| Sensor                                                                                                                                                                                         | Antal | Pris   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | ------ |
| [Aqara T1 Termometer och hygrometer](https://www.kjell.com/se/produkter/smarta-hem/smarta-hem-losningar/aqara-smarta-hem/aqara-t1-termometer-och-hygrometer-p57864)                            | 1     | 229 kr |
| [Cleverio Smart Magnetsensor med Zigbee 3.0](https://www.kjell.com/se/varumarken/cleverio/smarta-hem/smarta-sensorer/smarta-magnetkontakter/cleverio-smart-magnetsensor-med-zigbee-3.0-p51826) | 1     | 179 kr |

## Instruktioner

För att komma igång med sensorerna och gatewayen följer här en steg-för-steg-guide. Först konfigureras gatewayen och sedan kopplas sensorerna till den och först då kan man ställa in regler för hur sensorerna ska fungera och när de ska skicka notifikationer.

Tryck [här](/instructions.md) för att gå till instruktionerna.

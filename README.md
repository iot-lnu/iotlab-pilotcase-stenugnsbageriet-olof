# Stenugnsbageriet Olof
Vi bakar surdegsbröd, bullar och kakor med smör, kärlek och öländskt lantvetemjöl.

## Kylutrymmen

Målet är att hålla koll på temperatur i kylutrymmen. Få reda på om dörren till kylutrymmet är öppet. Syftet är att veta om kylen är trasig eller har lämnats öppen och förhindra att matvaror blir dåliga. Vi kollar på sensorer rom skickar med hjälp av närverkstypen LORA. Vi misstänker att LORA kommer ha lättare att ta sig igenom de tjocka väggarna i kylutrymmet. 

### Förslag på Temperatursensorer

| Länk                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Pris  | Batteritid                       | Temperaturområde                                  | Mäter också              |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|----------------------------------|---------------------------------------------------|--------------------------|
| [LHT52](https://www.digikey.se/sv/products/detail/seeed-technology-co.,-ltd/101990984/16652883?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMAX%20Shopping_Product_High%20Performers&utm_term=&productid=16652883&utm_content=&utm_id=go_cmp-19549529751_adg-_ad-__dev-c_ext-_prd-16652883_sig-CjwKCAjwysipBhBXEiwApJOcuw7otEcOU48ScTSr2y0KnUQknbza133N0kkmly801l9J1o7VeKdjLhoCU94QAvD_BwE&gclid=CjwKCAjwysipBhBXEiwApJOcuw7otEcOU48ScTSr2y0KnUQknbza133N0kkmly801l9J1o7VeKdjLhoCU94QAvD_BwE) | 413   | "upp till flera år"              | -20~+50                                           | Luftfuktighet            |
| [LHT65](https://www.elfa.se/en/lht65-lorawan-sht20-temperature-and-humidity-sensor-915mhz-seeed-studio-113990755/p/30163014?ext_cid=shgooaqsesv-Shopping-PerformanceMax-CSS&cq_src=google_ads&cq_cmp=20378176311&cq_con=&cq_term=&cq_med=pla&cq_plac=&cq_net=x&cq_pos=&cq_plt=gp&gclid=CjwKCAjwysipBhBXEiwApJOcuwnCMCUkaiSLwhB0_79ztzG6db4bPiu-UFQ9BfnNvDywDtGn3h0C4RoCs2gQAvD_BwE&gclsrc=aw.ds)                                                                                                             | 514   | 1.5-11 år beroende på användning | -40~+125 (intärn sensor) -55~+125 (extärn sensor) | Luftfuktighet            |
| [IOTSU_L3_AQ01_service](https://www.acandia.se/product/lora-sensor-for-temp-rh-co2-och-tvoc-inne?sku=IOTSU_L3_AQ01_service&referer=google-shopping&country=SE&currency=SEK&gclid=CjwKCAjwysipBhBXEiwApJOcu0--bpDlYaCDPKy8FHtRa-13dHoq0e3HYO53bU6824Z3z1_f2PdPMBoCHXcQAvD_BwE)                                                                                                                                                                                                                        | 299   | "normalt 5 års drift"            | 0~+50                                             | Luftfuktighet, CO2, TVOC |
|[EMS Mini LoRa Sensor ](https://www.dustinhome.se/product/5011208976/ems-mini-lora-sensor?gclid=CjwKCAjwysipBhBXEiwApJOcuy7WcbXjWAhYEBPRg41w_hwoTI9LbAZG1rzgJtztjqtwS2-fJdGFXRoC7Z4QAvD_BwE&tab=specification)|895|"Upp till 10 år"|0~+40|Dörr, Fuktighet, Översvämning, Accelerometer|

### Förslag på dörrsensorer

| Länk | pris | Batteritid | Användbar Funktion |
|------|------|------------|--------------------|
|[LDS02](https://www.digikey.se/sv/products/detail/seeed-technology-co.,-ltd/101990921/16128317?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMAX%20Shopping_Product_High%20Performers&utm_term=&productid=16128317&utm_content=&utm_id=go_cmp-19549529751_adg-_ad-__dev-c_ext-_prd-16128317_sig-CjwKCAjwysipBhBXEiwApJOcu2EvPH7vGSeenPXfsRVBm2takXOF7F32n3XnR9Q6WI3hAPAprKYREBoC79AQAvD_BwE&gclid=CjwKCAjwysipBhBXEiwApJOcu2EvPH7vGSeenPXfsRVBm2takXOF7F32n3XnR9Q6WI3hAPAprKYREBoC79AQAvD_BwE)|198| "16,000 ~ 70,000 uplink packets."| "...öppen larmfunktion, användaren kan ställa in denna funktion så att enheten skickar larm om dörren har varit öppen under en viss tid." |
|[EMS Mini LoRa Sensor ](https://www.dustinhome.se/product/5011208976/ems-mini-lora-sensor?gclid=CjwKCAjwysipBhBXEiwApJOcuy7WcbXjWAhYEBPRg41w_hwoTI9LbAZG1rzgJtztjqtwS2-fJdGFXRoC7Z4QAvD_BwE&tab=specification)|895|"Upp till 10 år"|Sensorn reagerar när dörren är öppen ungefär 10 mm men kan påverkas av dörrens material (metall minskar räckvidden)|

### Förslag på dörrsensor som bara är larm
Denna typ av sensorer faller inte in under IOT, men det kanske är vad som bäst skulle fylla de behov som finns i bageriet. 
|Länk|pris|Batteritid|Användbar funktion|
|----|----|----------|------------------|
|[Fridggi](https://www.amazon.com/FRIDGGI-Freezer-Fridge-Delays-120sec/dp/B08B4H3LM8/ref=sr_1_1_sspa?keywords=Refrigerator%2BDoor%2BAlarm&qid=1698155334&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)|22.64$|1 år|Olika typer av larm kan ställas in. Exempel 1: Mjukt larm efter en minut, påminnelse efter 2 minuter. Exempel 2: Ihållande larm efter 3 minuter.|
|[WSDCAM](https://www.amazon.com/Freezer-Seconds-Adjustable-Wireless-Refrigerator/dp/B08LMTF8GM/ref=sr_1_4?keywords=Refrigerator+Door+Alarm&qid=1698155334&sr=8-4)|22.99$|Ingen information|Larmar om dörren varit öppen i 3/15/30 eller 60 sekunder.|
|[Freezer Door Alarm](https://www.amazon.com/Freezer-Window-Reminder-Office-School/dp/B0BX9FZ6CB/ref=sr_1_6?keywords=Refrigerator%2BDoor%2BAlarm&qid=1698155334&sr=8-6&th=1)|16.99 $|ingen information|Kan ställas in att larma efter 30 sekunder. Påminelse var 20e sekund. Slutar efter en timme, eller när dörren stängs|




### Förslag på LORA gateways 

Gatewayens uppgift är att ta emot data från sensorerna och skicka den vidare. 
| Länk | pris |
|------|------|
|[The Things Industries Indoor Gateway](https://se.rs-online.com/web/p/communication-wireless-development-tools/2018876?cm_mmc=SE-PLA-DS3A-_-google-_-CSS_SE_EN_Raspberry_Pi_%26_Arduino_%26_ROCK_%26_Development_Tools_Whoop-_-(SE:Whoop!)+Communication+%26+Wireless+Development+Tools-_-2018876&matchtype=&pla-302930656441&gclid=CjwKCAjw1t2pBhAFEiwA_-A-NOvxPfAQ4cl8sQ8oEuscpmawnXehCW75WMHKWKnB0HmnI4oHW4bPExoCufoQAvD_BwE&gclsrc=aw.ds)| 1460 |
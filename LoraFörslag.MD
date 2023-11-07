# Lora

* LoRa är en trådlös teknik som är känd för sin långa räckvidd och låg strömförbrukning. Det kan vara lämpligt om ditt bageri är ganska stort eller om det finns hinder som kan minska räckvidden för Wi-Fi.

* LoRa-nätverket kräver en gateway för att samla in data från dina sensorer och skicka den till en onlineplattform. LoRa-gatewayen kan kopplas till din befintliga internetanslutning.

* LoRa-temperatursensorer kan vara kostnadseffektiva och kräver vanligtvis inga månatliga abonnemang, men det kan finnas initiala investeringar för LoRa-gateway och sensorer.

Till att börja med föreslogs LORA sensorer. 

## Förslag på Temperatursensorer

| Länk | Pris  | Batteritid                       | Temperaturområde                                  | Mäter också              |
|-|-|-|-|-|
| [LHT52](https://www.digikey.se/sv/products/detail/seeed-technology-co.,-ltd/101990984/16652883?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMAX%20Shopping_Product_High%20Performers&utm_term=&productid=16652883&utm_content=&utm_id=go_cmp-19549529751_adg-_ad-__dev-c_ext-_prd-16652883_sig-CjwKCAjwysipBhBXEiwApJOcuw7otEcOU48ScTSr2y0KnUQknbza133N0kkmly801l9J1o7VeKdjLhoCU94QAvD_BwE&gclid=CjwKCAjwysipBhBXEiwApJOcuw7otEcOU48ScTSr2y0KnUQknbza133N0kkmly801l9J1o7VeKdjLhoCU94QAvD_BwE) | 413   | "upp till flera år"              | -20~+50                                           | Luftfuktighet            |
| [LHT65](https://www.elfa.se/en/lht65-lorawan-sht20-temperature-and-humidity-sensor-915mhz-seeed-studio-113990755/p/30163014?ext_cid=shgooaqsesv-Shopping-PerformanceMax-CSS&cq_src=google_ads&cq_cmp=20378176311&cq_con=&cq_term=&cq_med=pla&cq_plac=&cq_net=x&cq_pos=&cq_plt=gp&gclid=CjwKCAjwysipBhBXEiwApJOcuwnCMCUkaiSLwhB0_79ztzG6db4bPiu-UFQ9BfnNvDywDtGn3h0C4RoCs2gQAvD_BwE&gclsrc=aw.ds)                                                                                                             | 514   | 1.5-11 år beroende på användning | -40~+125 (intärn sensor) -55~+125 (extärn sensor) | Luftfuktighet            |
| [IOTSU_L3_AQ01_service](https://www.acandia.se/product/lora-sensor-for-temp-rh-co2-och-tvoc-inne?sku=IOTSU_L3_AQ01_service&referer=google-shopping&country=SE&currency=SEK&gclid=CjwKCAjwysipBhBXEiwApJOcu0--bpDlYaCDPKy8FHtRa-13dHoq0e3HYO53bU6824Z3z1_f2PdPMBoCHXcQAvD_BwE)                                                                                                                                                                                                                        | 299   | "normalt 5 års drift"            | 0~+50                                             | Luftfuktighet, CO2, TVOC |
|[EMS Mini LoRa Sensor ](https://www.dustinhome.se/product/5011208976/ems-mini-lora-sensor?gclid=CjwKCAjwysipBhBXEiwApJOcuy7WcbXjWAhYEBPRg41w_hwoTI9LbAZG1rzgJtztjqtwS2-fJdGFXRoC7Z4QAvD_BwE&tab=specification)|895|"Upp till 10 år"|0~+40|Dörr, Fuktighet, Översvämning, Accelerometer|

## Förslag på dörrsensorer

| Länk | pris | Batteritid | Användbar Funktion |
|------|------|------------|--------------------|
|[LDS02](https://www.digikey.se/sv/products/detail/seeed-technology-co.,-ltd/101990921/16128317?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMAX%20Shopping_Product_High%20Performers&utm_term=&productid=16128317&utm_content=&utm_id=go_cmp-19549529751_adg-_ad-__dev-c_ext-_prd-16128317_sig-CjwKCAjwysipBhBXEiwApJOcu2EvPH7vGSeenPXfsRVBm2takXOF7F32n3XnR9Q6WI3hAPAprKYREBoC79AQAvD_BwE&gclid=CjwKCAjwysipBhBXEiwApJOcu2EvPH7vGSeenPXfsRVBm2takXOF7F32n3XnR9Q6WI3hAPAprKYREBoC79AQAvD_BwE)|198| "16,000 ~ 70,000 uplink packets."| "...öppen larmfunktion, användaren kan ställa in denna funktion så att enheten skickar larm om dörren har varit öppen under en viss tid." |
|[EMS Mini LoRa Sensor ](https://www.dustinhome.se/product/5011208976/ems-mini-lora-sensor?gclid=CjwKCAjwysipBhBXEiwApJOcuy7WcbXjWAhYEBPRg41w_hwoTI9LbAZG1rzgJtztjqtwS2-fJdGFXRoC7Z4QAvD_BwE&tab=specification)|895|"Upp till 10 år"|Sensorn reagerar när dörren är öppen ungefär 10 mm men kan påverkas av dörrens material (metall minskar räckvidden)|

## Förslag på LORA gateways 

Gatewayens uppgift är att ta emot data från sensorerna och skicka den vidare. 
| Länk | pris |
|------|------|
|[The Things Industries Indoor Gateway](https://se.rs-online.com/web/p/communication-wireless-development-tools/2018876?cm_mmc=SE-PLA-DS3A-_-google-_-CSS_SE_EN_Raspberry_Pi_%26_Arduino_%26_ROCK_%26_Development_Tools_Whoop-_-(SE:Whoop!)+Communication+%26+Wireless+Development+Tools-_-2018876&matchtype=&pla-302930656441&gclid=CjwKCAjw1t2pBhAFEiwA_-A-NOvxPfAQ4cl8sQ8oEuscpmawnXehCW75WMHKWKnB0HmnI4oHW4bPExoCufoQAvD_BwE&gclsrc=aw.ds)| 1460 |The 
# LPRS2_2024

## PD60 Gasoline and Diesel Vehicle Computer Board Fuel Injection Ignition Simulator and Bosch EDC16U1

U ovom projektu povezujemo [PD60](https://vi.aliexpress.com/item/1005006493152183.html?spm=a2g0o.order_list.order_list_main.85.63f61802seDDk8&gatewayAdapt=glo2vnm) sa ECU Bosch EDC16U1, olakšavajući razvoj i testiranje softverskih rešenja za automobilske aplikacije.

### Funkcionalnosti

- Emulacija signala: Mogućnost simuliranja različitih senzora i signala, ključnih za testiranje i validaciju softvera.
  
- Praćenje parametara na OBDII

### Instalacija

1. Preuzimanje koda: Clone-ujte ovaj repozitorijum na lokalni računar koristeći Git.
	'''bash
	git clone [ovaj link](https://github.com/Mackooo99/LPRS2_2024)
	

2. Postavljanje: Povezivanje pd60 sa ecu-om, us pomoć dokumentacije pinout-a ecu-a i uputstva za korišćenje simulatora [pd60](http://en.hao-ok.com/DownloadDetail.aspx?Id=73)

### Korišćenje

1. Pokretanje emulatora: Emulator se, nakon povezivanja, priključuje na napon od 12V

2. Razvoj i testiranje: Za testiranje smo koristili git repozitorijum gde je razvijena [aplikacija](https://github.com/speeduino/Ardu-Stim) za generisanje crank and can signala

### Doprinose

Otvoreni smo za doprinose i sugestije.

### Autori

- Marija Ninković <marijanink@gmail.com>
- Milan Štrbac <milanstrbac1@gmail.com>
- Jovan Crnčević <jovan.crncevic@gmail.com>

### Licenca

Ovaj projekat je dostupan pod MIT licencom.


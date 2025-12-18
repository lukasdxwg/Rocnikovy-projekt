# Projekt: Samostatné zapojení a konfigurace síťového routeru

## Cíl

Cílem tohoto projektu je prokázat, že jsem schopen samostatně zapojit, nakonfigurovat a otestovat domácí síťový router. V rámci projektu jsem se seznámil se základními hardwarovými a softwarovými prostředky používanými v oblasti počítačových sítí, pochopil jsem princip fungování bezdrátových sítí (Wi-Fi) a význam jednotlivých konfiguračních parametrů routeru.

Součástí cíle je také:

* orientace v administraci síťového zařízení,
* pochopení rozdílů mezi pásmy 2.4 GHz a 5 GHz,
* ověření správné funkčnosti sítě na různých zařízeních.

---

## Ověření cílů

* Zapojil jsem router do elektrické sítě a k poskytovateli internetu
* Přihlásil jsem se do administračního rozhraní routeru
* Nakonfiguroval jsem LAN a bezdrátové sítě
* Nastavil jsem zabezpečení Wi‑Fi
* Ověřil jsem funkčnost připojení na PC a mobilním telefonu

---

## 1. Použité hardwarové prostředky

* Síťový router **TP‑Link Archer C6**
* Napájecí adaptér routeru
* Ethernetový kabel (UTP)
* Stolní počítač a notebook
* Mobilní telefon

### Základní popis routeru

Router je zařízení, které propojuje lokální síť s internetem. Zajišťuje směrování dat, přidělování IP adres (DHCP), zabezpečení sítě a bezdrátovou komunikaci pomocí Wi‑Fi.

---

## 2. Zapojení routeru

Router jsem připojil k elektrické síti pomocí napájecího adaptéru. WAN port routeru jsem propojil ethernetovým kabelem s modemem poskytovatele internetu. Pro první konfiguraci jsem počítač připojil k routeru pomocí LAN kabelu, aby byla zajištěna stabilní komunikace během nastavování. Po zapnutí routeru jsem zkontroloval stavové LED diody, které signalizují správnou funkčnost zařízení.

---

## 3. Přihlášení do administrace routeru

Pro konfiguraci routeru jsem použil webové administrační rozhraní. Do administrace jsem se přihlásil přes webový prohlížeč na adrese **[http://192.168.0.1](http://192.168.0.1)** pomocí lokálního administračního hesla. Při resetu routeru do továrního nastavení jsem byl vyzván k vytvoření nového administračního hesla.

---

## 4. Softwarové prostředky

Nastavil jsem parametry lokální i bezdrátové sítě tak, aby router automaticky přiděloval IP adresy, síť byla zabezpečená a všechna zařízení měla stabilní připojení k internetu.

---

## 5. Konfigurace bezdrátové sítě (Wi‑Fi)

### Nastavení 2.4 GHz

* Režim: 802.11 b/g/n mixed
* Kanál: 13
* Šířka kanálu: 20 MHz
* Zabezpečení: WPA2‑PSK (AES)

Pásmo 2.4 GHz jsem zvolil kvůli lepšímu dosahu a stabilitě.

### Nastavení 5 GHz

* Režim: 802.11 a/n/ac mixed
* Kanál: 36
* Šířka kanálu: 80 MHz
* Zabezpečení: WPA2‑PSK (AES)

Pásmo 5 GHz jsem nastavil kvůli vyšší rychlosti připojení na PC.

## 6.  Zabezpečení sítě

Pro zabezpečení bezdrátové sítě bylo použito:

* šifrování WPA2‑PSK,
* silné heslo (kombinace písmen a číslic),
* oddělení názvů sítí pro 2.4 GHz a 5 GHz.

Tím je zabráněno neoprávněnému přístupu do sítě.

---

## 7. Testování funkčnosti

Po dokončení konfigurace jsem síť otestoval. Připojil jsem stolní počítač k 5 GHz síti a ověřil stabilitu připojení. Rychlost internetu jsem měřil pomocí nástroje **Speedtest by Ookla**, kde jsem ověřil rychlost stahování, odesílání a odezvu (ping).

Pro výběr vhodného Wi-Fi kanálu jsem použil aplikaci **WiFi Analyzer**, pomocí které jsem zjistil obsazenost jednotlivých kanálů v okolí a zvolil méně rušený kanál. Tím se podařilo zlepšit stabilitu a kvalitu bezdrátového připojení.

---

## 8. Možné chyby a jejich řešení

* Problémy s připojením k Wi‑Fi jsem řešil změnou kanálu.
* V případě zapomenutého hesla je nutné provést reset routeru do továrního nastavení.

---

## 9. Hodnocení projektu a sebereflexe

Projekt hodnotím jako přínosný, protože mi umožnil prakticky si vyzkoušet práci se síťovým zařízením, se kterým se běžně setkáváme doma i ve škole. Během práce jsem si upevnil znalosti z oblasti počítačových sítí, zejména rozdíly mezi pásmy 2.4 GHz a 5 GHz, význam zabezpečení Wi-Fi a volbu vhodného kanálu.

Největším přínosem pro mě bylo řešení problémů. Při nastavování jsem měl potíže s připojením počítače k 5 GHz síti, které jsem vyřešil úpravou nastavení zabezpečení a kanálu. Díky tomu jsem pochopil, že je nutné brát v úvahu kompatibilitu různých zařízení.

Při práci jsem využil odborné internetové zdroje a konzultoval postup také pomocí nástroje ChatGPT jako studijní pomůcky. Samotné zapojení, konfiguraci a testování routeru jsem provedl samostatně.

Pokud bych projekt realizoval znovu, rozšířil bych jej například o:

* měření reálných rychlostí přenosu dat,
* porovnání výkonu 2.4 GHz a 5 GHz sítě,
* základní nastavení firewallu nebo rodičovské kontroly.

Projekt mi pomohl lépe pochopit teorii probíranou ve výuce a ukázal mi její praktické využití.

---


## 10. Citace
**[1]** BEHFOR. *Choose the Right Channel for your WiFi!*. Online. YouTube, 2023.  
Dostupné z: https://www.youtube.com/watch?v=S_RO92ttpMo  
[cit. 2025-12-17].

**[2]** *Jak nastavit router TP-LINK – TP-Link nastavení routeru – návod TP-Link*. Online. YouTube, 2024.  
Dostupné z: https://www.youtube.com/watch?v=8hMrZ6RmAjc  
[cit. 2025-12-17].

**[3]** OpenAI. *ChatGPT – konzultační dotaz k nastavení routeru*. Online, 2025.  
Použitý prompt:  
> „Mám domácí router TP-Link Archer C6 a potřebuji poradit s jeho nastavením.  
> Vysvětli mi rozdíl mezi Wi-Fi 2.4 GHz a 5 GHz, jak nastavit channel mode, channel width a jak vybrat vhodný kanál.“  
[cit. 2025-12-17].

## Závěr

V tomto projektu jsem samostatně zapojil a nakonfiguroval domácí síťový router. Naučil jsem se pracovat s administračním rozhraním, nastavit bezdrátové sítě a ověřit jejich funkčnost. Projekt splnil stanovené cíle a pomohl mi lépe pochopit základy počítačových sítí.

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
* Stolní počítač / notebook
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

Pro nastavení routeru jsem využil webové administrační rozhraní (Web GUI), které funguje jako webová aplikace. Toto rozhraní mi umožnilo nastavovat síťové parametry, spravovat bezdrátové sítě, konfigurovat zabezpečení a sledovat stav připojení. K přístupu jsem použil běžný webový prohlížeč.

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

Po dokončení konfigurace jsem síť otestoval. Připojil jsem stolní počítač k 5 GHz síti a ověřil stabilitu a rychlost připojení. Dále jsem připojil mobilní telefon k 2.4 GHz i 5 GHz síti. Funkčnost internetu jsem ověřil otevřením webových stránek a pomocí příkazu ping. Všechna zařízení se úspěšně připojila a připojení bylo stabilní.

---

## 8. Možné chyby a jejich řešení

* Problémy s připojením k Wi‑Fi jsem řešil změnou kanálu a typu zabezpečení.
* V případě zapomenutého hesla je nutné provést reset routeru do továrního nastavení.

---

## 9. Hodnocení projektu a sebereflexe

Projekt hodnotím jako přínosný, protože mi umožnil prakticky si vyzkoušet práci se síťovým zařízením, se kterým se běžně setkáváme v domácím i školním prostředí. Během realizace jsem si upevnil znalosti z oblasti počítačových sítí, zejména v tématech jako je rozdíl mezi pásmy 2.4 GHz a 5 GHz, význam šifrování Wi‑Fi, volba vhodného kanálu a základní princip fungování routeru.

Za největší přínos považuji to, že jsem se naučil systematicky řešit problémy. Při konfiguraci jsem narazil na potíže s připojením počítače k 5 GHz síti, které jsem musel analyzovat a odstranit úpravou nastavení zabezpečení a kanálu. Díky tomu jsem pochopil, že ne všechna zařízení podporují stejné standardy a že je nutné brát v úvahu kompatibilitu hardwaru.

Při práci jsem využil odborné internetové zdroje a konzultoval jsem postupy a význam jednotlivých nastavení také pomocí nástroje **ChatGPT**, který mi sloužil jako studijní a konzultační pomůcka. Veškeré zapojení, konfigurace a testování routeru jsem však provedl samostatně.

Pokud bych projekt realizoval znovu, rozšířil bych jej například o:

* měření reálných rychlostí přenosu dat,
* porovnání výkonu 2.4 GHz a 5 GHz sítě,
* základní nastavení firewallu nebo rodičovské kontroly.

Projekt mi pomohl lépe pochopit teorii probíranou ve výuce a ukázal mi její praktické využití.

---

## Závěr

V tomto projektu jsem samostatně zapojil a nakonfiguroval domácí síťový router. Naučil jsem se pracovat s administračním rozhraním, nastavit bezdrátové sítě a ověřit jejich funkčnost. Projekt splnil stanovené cíle a pomohl mi lépe pochopit základy počítačových sítí.


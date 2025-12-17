
# Projekt: Samostatné zapojení a konfigurace síťového routeru

## Cíl

Cílem projektu je prokázat schopnost samostatně zapojit, nakonfigurovat a otestovat domácí síťový router. Student se seznámí se základními hardwarovými a softwarovými prostředky používanými v oblasti počítačových sítí, pochopí princip fungování bezdrátových sítí (Wi‑Fi) a dokáže vysvětlit význam jednotlivých konfiguračních parametrů routeru.

Součástí cíle je také:

* orientace v administraci síťového zařízení,
* pochopení rozdílů mezi pásmy 2.4 GHz a 5 GHz,
* ověření správné funkčnosti sítě na různých zařízeních.

---

## Ověření cílů

* Zapojení routeru do elektrické sítě a k poskytovateli internetu
* Přihlášení do administračního rozhraní routeru
* Základní konfigurace LAN a Wi‑Fi
* Nastavení zabezpečení bezdrátové sítě
* Ověření funkčnosti připojení na PC a mobilním telefonu

---

## 1. Použité hardwarové prostředky

* Síťový router **TP‑Link Archer C6**
* Napájecí adaptér routeru
* Ethernetový kabel (UTP)
* Stolní počítač / notebook
* Mobilní telefon

### Základní popis routeru

Router je síťové zařízení, které propojuje lokální síť (LAN) s externí sítí (WAN – internet). Zajišťuje směrování dat, přidělování IP adres (DHCP), zabezpečení sítě a bezdrátovou komunikaci pomocí Wi‑Fi.

---

## 2. Zapojení routeru

1. Router byl připojen k elektrické síti pomocí napájecího adaptéru.
2. WAN port routeru byl propojen ethernetovým kabelem s modemem poskytovatele internetu.
3. Počítač byl připojen k routeru pomocí LAN kabelu (pro první konfiguraci).
4. Po zapnutí routeru byly zkontrolovány stavové LED diody.

---

## 3. Přihlášení do administrace routeru

Pro konfiguraci routeru bylo použito webové administrační rozhraní:

* Adresa: **[http://192.168.0.1](http://192.168.0.1)**
* Přihlášení pomocí lokálního hesla (Local Password)

Při resetu routeru do továrního nastavení je uživatel vyzván k vytvoření nového administračního hesla.

---

## 4. Softwarové prostředky

### Administrační rozhraní (Web GUI)

Administrace routeru funguje jako webová aplikace, která umožňuje:

* nastavovat síťové parametry,
* spravovat Wi‑Fi sítě,
* konfigurovat zabezpečení,
* sledovat stav připojení.

K přístupu je použit běžný webový prohlížeč (Chrome, Edge apod.).

---

## 5. Konfigurace bezdrátové sítě (Wi‑Fi)

### 5.1 Nastavení 2.4 GHz sítě

* SSID: MojeWiFi‑24G
* Režim: 802.11 b/g/n mixed
* Kanál: **13**
* Šířka kanálu: 20 MHz
* Zabezpečení: WPA2‑PSK
* Šifrování: AES (CCMP)

Pásmo 2.4 GHz nabízí delší dosah a lepší průchod zdmi, ale nižší rychlosti.

### 5.2 Nastavení 5 GHz sítě

* SSID: MojeWiFi‑5G
* Režim: 802.11 a/n/ac mixed
* Kanál: 36
* Šířka kanálu: 80 MHz
* Zabezpečení: WPA2‑PSK
* Šifrování: AES (CCMP)

Pásmo 5 GHz poskytuje vyšší rychlosti a menší rušení, ale kratší dosah.

---

## 6. Zabezpečení sítě

Pro zabezpečení bezdrátové sítě bylo použito:

* šifrování WPA2‑PSK,
* silné heslo (kombinace písmen a číslic),
* oddělení názvů sítí pro 2.4 GHz a 5 GHz.

Tím je zabráněno neoprávněnému přístupu do sítě.

---

## 7. Testování funkčnosti

Po dokončení konfigurace byla síť otestována:

* Připojení PC k 5 GHz síti – ověření stability a rychlosti
* Připojení mobilního telefonu k 2.4 GHz i 5 GHz síti
* Ověření přístupu k internetu (webové stránky, ping)

Všechna zařízení se úspěšně připojila a připojení bylo stabilní.

---

## 8. Možné chyby a jejich řešení

### Konfigurační chyby

* Nesprávný kanál Wi‑Fi → změna na pevně nastavený kanál
* Nepodporované šifrování (WPA3) → přechod na WPA2

### Uživatelské chyby

* Zapomenuté administrační heslo → reset routeru do továrního nastavení

---

## 9. Hodnocení projektu a sebereflexe

Projekt hodnotím jako přínosný, protože mi umožnil prakticky si vyzkoušet práci se síťovým zařízením, se kterým se běžně setkáváme v domácím i školním prostředí. Během realizace jsem si upevnil znalosti z oblasti počítačových sítí, zejména v tématech jako je rozdíl mezi pásmy 2.4 GHz a 5 GHz, význam šifrování Wi-Fi, volba vhodného kanálu a základní princip fungování routeru.

Za největší přínos považuji to, že jsem se naučil systematicky řešit problémy. Při konfiguraci jsem narazil na potíže s připojením počítače k 5 GHz síti, které jsem musel analyzovat a odstranit úpravou nastavení zabezpečení a kanálu. Díky tomu jsem pochopil, že ne všechna zařízení podporují stejné standardy a že je nutné brát v úvahu kompatibilitu hardwaru.

Při práci jsem využil odborné internetové zdroje a konzultoval jsem postupy a význam jednotlivých nastavení také pomocí nástroje **ChatGPT**, který mi sloužil jako studijní a konzultační pomůcka. Veškeré zapojení, konfigurace a testování routeru jsem však provedl samostatně.

Pokud bych projekt realizoval znovu, rozšířil bych jej například o:

* měření reálných rychlostí přenosu dat,
* porovnání výkonu 2.4 GHz a 5 GHz sítě,
* základní nastavení firewallu nebo rodičovské kontroly.

Projekt mi pomohl lépe pochopit teorii probíranou ve výuce a ukázal mi její praktické využití.

---

## Závěr

V rámci projektu se mi podařilo úspěšně zapojit a nakonfigurovat domácí síťový router. Práce mi umožnila propojit teoretické znalosti s praktickou činností a ověřit si funkčnost sítě na reálných zařízeních.

Projekt splnil stanovené cíle a považuji jej za užitečnou zkušenost pro další studium oboru Informační technologie i pro budoucí praxi.

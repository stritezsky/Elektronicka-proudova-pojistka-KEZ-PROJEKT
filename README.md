# Elektronická proudová pojistka

Tento projekt představuje návrh a implementaci elektronické proudové pojistky, zadané v rámci cvičení KEZ na VUT FEKT v Brně. Cílem projektu bylo překreslit dodané schéma zapojení, navrhnout desku plošných spojů (DPS) s využitím softwaru KiCad a připravit projekt k odevzdání.

**Hlavní body projektu:**

* **Návrh DPS:** Vytvoření návrhu desky plošných spojů na základě dodaného schématu zapojení. Deska je navržena jako jednovrstvá nebo dvouvrstvá s ohledem na použití starších typů součástek (konstrukční třída 3 nebo 4).
* **Použité součástky:** Projekt zahrnuje klasické THT součástky, SMD součástky nebo jejich kombinaci. Důraz byl kladen na správné použití doporučených značek a pouzder z knihoven KiCadu.
* **Funkčnost:** Elektronická proudová pojistka je navržena k jištění elektrických obvodů proti nadměrnému proudu. Vypínací proud je nastavitelný pomocí konfigurace děliče napětí s rezistory R7 až R14 a propojky na kontaktních kolících KK1.
* **Napájení:** Pojistka je napájena stabilizovaným stejnosměrným napětím 12 V a obsahuje stabilizátor 78L05 pro získání referenčního napětí +5 V. Záporné napětí pro operační zesilovač je generováno astabilním multivibrátorem NE555 a zdvojovačem napětí.

**Technologie a nástroje:**

* **KiCad:** Návrh schématu a desky plošných spojů byl realizován v open-source EDA softwaru KiCad.
* **THT a SMD součástky:** Projekt zahrnuje návrh pro klasické průchozí (THT) i povrchově montované (SMD) součástky.

**Poznámky k vývoji:**

* Projekt byl vyvíjen v rámci individuálního cvičení BPC-KEZ pod vedením Ing. Pavla Hanáka, Ph.D.
* Při návrhu DPS bylo dbáno na správné rozmístění součástek a optimalizaci vedení spojů s ohledem na funkčnost a výrobitelnost desky.
* Byly zohledněny požadavky zadání, včetně možnosti použití jednovrstvé nebo dvouvrstvé desky a použití součástek s konstrukční třídou 3 nebo 4.

**Odevzdání projektu:**

Hotový KiCad projekt bude odevzdán ve stanoveném termínu. 

**Proč je tento projekt v mém CV?**

Tento projekt demonstruje mé schopnosti v oblasti:

* **Návrhu elektronických obvodů:** Pochopení schématu zapojení a jeho převedení do návrhu desky plošných spojů.
* **Práce s EDA nástroji:** Zkušenost s profesionálním softwarem pro návrh elektroniky KiCad.
* **Znalosti elektronických součástek:** Orientace v typech pouzder (THT, SMD) a jejich správném použití.
* **Řešení technických zadání:** Schopnost splnit zadané požadavky a odevzdat kompletní a funkční výsledek.
* **Samostatné práce na projektu:** Realizace individuálního projektu od zadání po finální návrh.

Schéma
![image](https://github.com/user-attachments/assets/e36651b2-2666-4f82-b5da-c950c836598f)

PCB
![image](https://github.com/user-attachments/assets/1802a8dd-4917-44b1-baa8-49b38c7e745d)


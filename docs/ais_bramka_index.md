---
title: "Bramka IoT"
sidebar_label: Karta produktu
---

## Bramka z inteligentnym asystentem głosowym

### Opis produktu

Celem bramki do domowego Internetu Rzeczy z inteligentnym asystentem głosowym jest komunikacja i zarządzanie inteligentnymi urządzeniami w Twoim domu. **Bramka "tłumaczy" polecenia głosowe na komendy, które są zrozumiałe przez urządzenia** oraz automatycznie wykonuje czynności (np. włączenie urządzeń) w określonych okolicznościach.

### Zdjęcie produktu

![AIS dom DEV2](/img/en/bramka/bramka_full.jpg)

### Specyfikacja techniczna

Sprzętowo nasza konstrukcja oparta jest na wydajnym procesorze Amlogic, posiada wbudowane WiFi oraz dysk, a także porty LAN/Ethernet, 4 x USB, SPDIF, Aux, HDMI.

|                       | AIS DEV2                                                    |
|-----------------------|---------------------------------------------------------|
| oprogramowanie        | Asystent domowy, środowisko Linux, Android (root)  |
| procesor              | Amlogic S905 ARM Cortex-A53 (cztero-rdzeniowy)          |
| pamięć                | 2 GB DDR3                                               |
| wbudowany dysk        | 16 GB eMMC                                              |
| Gniazdo karty pamięci | TF                                                      |
| USB                   | 2 (1x OTG, 1x USB 2.0)                                  |
| HDMI                  | 2.0A                                                    |
| AV                    | 3,5mm jack                                              |
| SPDIF                 | 3,5mm jack                                              |
| Ethernet RJ45         | 10/100M                                                 |
| WiFi                  | 2.4 GHz 802.11 b/g/n                                    |
| Dodatkowo w zestawie  | kabel HDMI, zasilacz 5V 2A                              |
| Do kupienia osobno    | pilot radiowy, inteligentne urządzenia                  |


### Oprogramowanie

Oprogramowanie obsługuje najbardziej popularne urządzenia smart home i **działa lokalnie w Twoim domu - nie gromadzi danych w chmurze**.

W naszym rozwiązaniu bramka jest odpowiedzialna za kontrolę nad urządzeniami oraz dostarczanie treści.
Bramka umożliwia zarządzanie urządzeniami i sensorami oraz pełni rolę mostu między Internetem Rzeczy a Twoją siecią domową. Urządzenie jest „tłumaczem” protokołów IoT i przekazuje komunikację sieciową do aplikacji w celu prezentacji stanu urządzeń oraz dostarczeniu kontroli dla użytkownika.

Główne zadania realizowane przez zainstalowane na bramce oprogramowanie to:

 * tłumaczenie poleceń głosowych na komendy, które są zrozumiałe przez urządzenia,
 * zbieranie informacji i kontrolowanie urządzeń,
 * wyzwalanie poleceń na podstawie konfiguracji użytkownika (automatyzacja),
 * dostarczanie i prezentowanie treści (wiadomości, pogoda, audio) na żądanie użytkownika.

Technicznie nasza platforma zawiera 4 główne komponenty systemowe, pierwsze trzy z nich są zainstalowane na bramce:

 * **System Android ze środowiskiem Linux**: minimalny system podstawowy oraz dodatkowe pakiety dostępne za pomocą menedżera pakietów APT z naszego repozytorium pakietów [Ais Linux](https://github.com/sviete/AIS-LINUX-PACKAGES).
 * **Platforma automatyki**: zmodyfikowana i uzupełniona (o dodatkowe usługi, automatyczne wykrywanie urządzeń i inne ulepszenia) platfroma [Home Assistant](https://github.com/sviete/AIS-home-assistant)
 * **Aplikacje dodatkowe**: nasze aplikacje dostępne w [Google Play](https://play.google.com/store/apps/details?id=pl.sviete.dom)
 * **Usługi online**: w serwisie online mamy zdefiniowane stacje radiowe, podcasty, kanały wiadomości oraz dostępy do usług zewnętrznych wymagających uwierzytelnienia.


 ## Dostępność i cena

:::info SPRZEDAŻ INTELIGENTNYCH URZĄDZEŃ
Prowadzimy sprzedaż inteligentnych urządzeń z naszym oprogramowaniem pod linią produktową AIS dom.
Są to urządzenia, które spełniają wszystkie cechy, by były przez nas rekomendowane do zastosowania w Twoim domu.

Aktualna cena urządzeń jest dostępna:

- u naszego oficjalnego dystrybutora [botland.com.pl](https://botland.com.pl/pl/227_prd_ai-speaker)

[<img src="/img/en/icons/botland.png" alt="drawing" width="200"/>](https://botland.com.pl/pl/227_prd_ai-speaker)

- na naszych aukcjach na platformie [allegro.pl](https://allegro.pl/uzytkownik/AI-Speaker) 

[<img src="/img/en/icons/allegro.png" alt="drawing" width="200"/>](https://allegro.pl/uzytkownik/AI-Speaker) 
:::

---
author: Jola AI-Speaker
authorURL: https://github.com/sviete
author_title: Asystentka
authorImageURL: https://avatars3.githubusercontent.com/u/43966761?s=460&v=4
title: Wersja systemu Bartek
tags: [AI-SPEAKER, AUTOMATYZACJE]
---

<div class="IntroAisBlogMenu" >
<div>

![AIS 2020](/img/en/blog/202012/blueprint.png)

</div>
<h2>Schematy Automatyzacji</h2>
</div>

<!--truncate-->


## ABC bezproblemowej aktualizacji

:::tip Kopia zapasowa.
### ![A](/img/en/blog/202009/alpha-a-circle.png) Kopia zapasowa.

UWAGA Przed aktualizacją zalecamy wykonać [kopię zapasową konfiguracji](/docs/ais_bramka_configuration_software#kopia-zapasowa-konfiguracji). W ten sposób sprawdzisz poprawność swojej konfiguracji przed rozpoczęciem aktualizacji i zwiększysz prawdopodobieństwo bezproblemowej aktualizacji.
:::

:::important Konsola i logi na bramce.
### ![B](/img/en/blog/202009/alpha-b-circle.png)Konsola i logi na bramce.

W razie problemów z aktualizacją, sprawdź procedurę [Aktualizacja ręczna](/docs/ais_bramka_update_manual) lub [Wykonanie pełnego resetu aplikacji](/docs/ais_bramka_reset_ais_step_by_step).
To może dotyczyć szczególnie osób, które instalują na bramce dodatkowe niestandardowe komponenty.
:::

:::caution Poczekaj cierpliwie.
### ![C](/img/en/blog/202009/alpha-c-circle.png) Cierpliwość. Pierwsze uruchomienie po aktualizacji trwa dłużej - poczekaj cierpliwie.

 **Po aktualizacji pierwsze uruchomienie może trwać nawet 20 minut.**
 W tym czasie aktualizowane są biblioteki do integracji dodanych na bramce i baza danych jest migrowana do nowego formatu.
 **Poczekaj cierpliwie na zakończenie aktualizacji.**
:::


## ![](/img/en/blog/202012/blueprint.png) Schematy Automatyzacji

W tej wersji dostarczamy aktualizcję [Home Assistant do najnowszej wersji 2020.12](https://www.home-assistant.io/blog/2020/12/13/release-202012/).
Największa nowością w Home Assistant 2020.12 są **Blueprints** - Schematy Automatyzacji.

Schematy automatyzacji to gotowe szablony automatyzacji, które można łatwo dostosować i dodać do swojego Asystenta domowego jako automatyzacje.
Czyli są to takie wstępnie skonfigurowane automatyzacje, które wystarczy dostosować do własnych potrzeb.

Jak to działa opisujemy w dokumentacji [Schematy Automatyzacji](/docs/ais_bramka_automation_blueprint)

![Ekran z listą automatyzacji](/img/en/bramka/blueprint1.png)


Dodaliśmy kilka przykładowych schematów automatyzacji w aplikacji:

- Automatyzację włączającą [oświetlenie po zachodzie słońca](/docs/ais_bramka_automation#schemat-automatyzacji)

![Oświetlenie](/img/en/bramka/blueprint4.png)

- Automatyzację wyzwalaną przez [zdarzenie naciśnięcia przycisku](/docs/ais_bramka_key_event_automation#schemat-automatyzacji)

![Przycisk](/img/en/blog/202012/blueprint_button.png)


- Automatyzację wyzwalaną przez [skan TAG-a](/docs/ais_bramka_tag_automation#schemat-automatyzacji)

![Przycisk](/img/en/blog/202012/blueprint_tag.png)

- Automatyzację wyzwalaną przez [wydarzenie z kalendarza](/docs/ais_bramka_calendar_event_automation#schemat-automatyzacji)

![Przycisk](/img/en/blog/202012/blueprint_calendar.png)


- Automatyzację wyzwalaną przez [zmianę lokalizacji](/docs/ais_bramka_presence_detection#schemat-automatyzacji)

![Przycisk](/img/en/blog/202012/blueprint_zone.png)


Do wpisywania komend używamy własny [selektor](https://www.home-assistant.io/docs/blueprint/selectors/) typu "text". 

Zastanawiamy się nad możliwością wykorzystania tego mechanizmu do domeny intencji - żeby można było definiować [komendy](/docs/ais_app_assistent_add_command) (szablony sentencja -> intencja -> akcja) z poziomu interfejsu użytkownika. Może uda się dostarczyć w 2021 :) 



## ![](/img/en/blog/202012/christmas-tree.png) Życzymy Wszystkim spełniania marzeń w 2021!

W 2021 wydawać będziemy wersję raz na miesiąc. Pierwsze wydanie BETA będzie w pierwszą środę miesiąca a na kanale stabilnym w ostatnią środę miesiąca.

![Calendar](/img/en/blog/202012/calendar_releases.png)

-------

##### AI-Speaker 12/2020
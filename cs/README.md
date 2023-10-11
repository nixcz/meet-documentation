<table>
<tr><td style="vertical-align: top; padding: 0">

[![MEET](../_data/MEET_H_04.svg#gh-dark-mode-only "MEET")](../README.md#gh-dark-mode-only)
[![MEET](../_data/MEET_H_03.svg#gh-light-mode-only "MEET")](../README.md#gh-light-mode-only)
![](../_data/w100.gif)
# Příručka pro administrátora
</td>
<td width="210" style="vertical-align: top">
<small style="font-size: 9px">

```
 __  __ ___ ___ _____ 
|  \/  | __| __|_   _|
| |\/| | _|| _|  | |  
|_|_ |_|___|___| |_|  
|   \ / _ \ / __/ __| 
| |) | (_) | (__\__ \
|___/ \___/ \___|___/
CZ 0.1a / 20230926
``` 
</small>
</td>
</tr>
</table>

- **[Vyjasnění technických požadavků s NIX.cz](pages/0000.md)** ⚠️

- [Přihlášení do administrace](pages/0001.md)

- [Dashboard, základní rozdělení aplikace](pages/0002.md)

- **[Základní konfigurace aplikace MEET](pages/0003.md)** ⚠️

- **[Import uživatelů pomocí API](pages/0004.md)**

- [FAQ - často kladené dotazy](pages/0005.md)

<br />

## Rozpis funkcí jednotlivých modulů (🚧 TODO?)
- Core (Hlavní moduly)
    - **Users** - správa uživatelů, možnost exportu qr kódů atd 
    - **Companies** - správa společností

- Meeting (Moduly související s organizací eventu)
    - **Events** - správa Eventů (aplikace podporuje spravovat a uchovávat více Eventů)
    - **Subevents**
    - **Registrations** - veškeré registrace na konkrétní eventy, včetně jejich stavů
    - **Slots**
    - **Locations**
    - **Meetings**

- Messaging (Moduly související s emaily, komentáři a soukromými zprávami)
    - **Mail Templates**
    - **Messages**
    - **Queued Mails**

- Api
    - **Tokens**

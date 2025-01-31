<table>
<tr><td style="vertical-align: top; padding: 0">

[![MEET](../_data/MEET_H_04.svg#gh-dark-mode-only "MEET")](../README.md#gh-dark-mode-only)
[![MEET](../_data/MEET_H_03.svg#gh-light-mode-only "MEET")](../README.md#gh-light-mode-only)
![](../_data/w100.gif)
# 📘 Příručka pro administrátora
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
CZ 0.3 / 20250201
``` 
</small>

</td>
</tr>
</table>

> [!IMPORTANT]  
>✨ **NOVINKY** - takto jsou označené funkce které jsou součástí nejnovějšího release aplikace

<details>
<summary><strong>⚠️ LEGENDA ikon použitých napříč dokumentací 📌</strong>
<br /><br />
</summary>

>
> ✨ **NOVINKA**  
> ⚠️ **Důležitá informace**  
> 🚧 **Nepoužívá se, připraveno do budoucna, rozpracované**
>
> ---
> 📦 **Modul** - Aplikace je rozdělena na drobnější části *(moduly)*
>
>   - 🔧 **Administrační modul** - potřebný pro nastavení aplikace
> 
>   - 🌎 **Frontendový modul** - pro ukládání vyplněných dat z frontendu, pro statistiky, samotnou organizaci eventu atd.
>
>   - 📄 **Výpis záznamů** - první část modulu
>       - 🔍 **Filtrování** - Přes jaká pole lze v modulu filtrovat, nebo zda je umožněno fulltextové vyhledávání
>       - 💡 **Hromadné akce**, které je možné ve výpisu vyvolat
>   - ✏️ **Editační Formulář** - druhá, editační část modulu
>       - 🔖 **Karta *(tab)*** - v případě rozsáhlejšího formuláře je formulář rozdělen na karty
>       -  💎 **Funkční tlačítka** - tlačítka v pravé části 
editačního formuláře
>       - 📍 **Template Tags** - speciální značky, které je možné použít v emailových šablonách
>       - 👁 **Readonly** formulářové pole - většinou jde o datumy vytvoření, poslední úpravy či vazby které nelze měnit.
</details>


- **[Vyjasnění technických požadavků s NIX.cz](pages/0000.md)** ⚠️

- [Přihlášení do administrace](pages/0001.md)
- [Dashboard, základní rozdělení aplikace](pages/0002.md)

- **[Základní konfigurace aplikace MEET](pages/0003.md)** ⚠️

- ✨ **[Import registrací, uživatelů a firem](pages/0004a.md)**

- **[Import uživatelů pomocí API](pages/0004b.md)**

- [FAQ - často kladené dotazy](pages/0005.md)

<br />

## 📦 Moduly aplikace MEET


> [!IMPORTANT]  
**[Základní rozvržení modulů](pages/0006.md)** a jak s nimi pracovat

- ![Dashboard](../_data/000.svg#gh-light-mode-only) ![Dashboard](../_data/dark/000.svg#gh-dark-mode-only)  **[Dashboard](pages/0002.md)** 


- **[Core](pages/0007.md)** *(Hlavní moduly)*
    - ![Users](../_data/00.svg#gh-light-mode-only) ![Users](../_data/dark/00.svg#gh-dark-mode-only)
    &nbsp;**[Users](pages/0007.md#_1)** 🌎🔧
    - ![Companies](../_data/01.svg#gh-light-mode-only) ![Companies](../_data/dark/01.svg#gh-dark-mode-only)
    &nbsp;**[Companies](pages/0007.md#_2)** 🔧
- **[Meeting](pages/0008.md)** *(Moduly související s organizací eventu)*
    - ![Events](../_data/02.svg#gh-light-mode-only) ![Events](../_data/dark/02.svg#gh-dark-mode-only)
    &nbsp;**[Events](pages/0008.md#_1)** 🔧
    - ![Subevents](../_data/03.svg#gh-light-mode-only) ![Subevents](../_data/dark/03.svg#gh-dark-mode-only)
    &nbsp;**[Subevents](pages/0008.md#_2)** 🔧
    - ![Subevent Participants](../_data/04.svg#gh-light-mode-only) ![Subevent Participants](../_data/dark/04.svg#gh-dark-mode-only)
    &nbsp;**[Subevent Participants](pages/0008.md#_3)** 🔧
    - ![Registrations](../_data/05.svg#gh-light-mode-only) ![Registrations](../_data/dark/05.svg#gh-dark-mode-only)
    &nbsp;**[Registrations](pages/0008.md#_4)** 🌎
    - ![Slots](../_data/06.svg#gh-light-mode-only) ![Slots](../_data/dark/06.svg#gh-dark-mode-only)
    &nbsp;**[Slots](pages/0008.md#_5)** 🔧
    - ![Locations](../_data/07.svg#gh-light-mode-only) ![Locations](../_data/dark/07.svg#gh-dark-mode-only) 
    &nbsp;**[Locations](pages/0008.md#_6)** 🔧
    - ![Meetings](../_data/08.svg#gh-light-mode-only) ![Meetings](../_data/dark/08.svg#gh-dark-mode-only)
    &nbsp;**[Meetings](pages/0008.md#_7)** 🌎

- **[Messaging](pages/0009.md)** *(Moduly související s emaily, komentáři a soukromými zprávami)*
    - ![Mail Templates](../_data/09.svg#gh-light-mode-only) ![Mail Templates](../_data/dark/09.svg#gh-dark-mode-only) 
    &nbsp;**[Mail Templates](pages/0009.md#_1)** 🔧
    - ![Messages](../_data/10.svg#gh-light-mode-only) ![Messages](../_data/dark/10.svg#gh-dark-mode-only)
    &nbsp;**[Messages](pages/0009.md#_2)** 🌎
    - ![Queued Mails](../_data/17.svg#gh-light-mode-only) ![Queued Mails](../_data/dark/17.svg#gh-dark-mode-only)
    &nbsp;**[Queued Mails](pages/0009.md#_3)** 🌎

- **[Settings](pages/0010.md)** *(Moduly s nastavením)*
    - ![Global Configuration](../_data/18.svg#gh-light-mode-only) ![Global Configuration](../_data/dark/18.svg#gh-dark-mode-only)
    **[Global Configuration](pages/0010.md#_1)** 🔧
    - ![Grafana Statistics](../_data/22.svg#gh-light-mode-only) ![Grafana Statistics](../_data/dark/22.svg#gh-dark-mode-only)
    **[Grafana Statistics](pages/0010.md#_2)** 🔧
    - ![API Tokens](../_data/12.svg#gh-light-mode-only) ![API Tokens](../_data/dark/12.svg#gh-dark-mode-only)
    &nbsp;**[API Tokens](pages/0010.md#_3)** 🔧

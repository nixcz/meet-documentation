<table>
<tr><td style="vertical-align: top; padding: 0">

[![MEET](../_data/MEET_H_04.svg#gh-dark-mode-only "MEET")](../README.md#gh-dark-mode-only)
[![MEET](../_data/MEET_H_03.svg#gh-light-mode-only "MEET")](../README.md#gh-light-mode-only)
![](../_data/w100.gif)
# 📘 Administrator's Guide
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
CZ 0.15 / 20231130
``` 
</small>

</td>
</tr>
</table>

> [!IMPORTANT]
>🚧 This documentation is still being intensively worked on!!! 🚧

<details>
<summary><strong>⚠️ LEGEND of icons used across documentation 📌</strong>
<br /><br />
</summary>

>
> ⚠️ **Important information**
>
> 🚧 **Not used, future ready, under development**
>
> ---
> 📦 **Module** - The application is divided into smaller parts *(modules)*
>
> - 🔧 **Administrative module** - needed to set up the application
>
> - 🌎 **Frontend module** - for storing completed data from the frontend, for statistics, the organization of the event itself, etc.
>
> - 📄 **List of records** - the first part of the module
> - 🔍 **Filtering** - Which fields can be filtered through in the module, or whether full-text search is enabled
> - 💡 **Mass actions** that can be invoked in the statement
> - ✏️ **Editing Form** - the second, editing part of the module
> - 🔖 **Tab *(tab)*** - in the case of a more extensive form, the form is divided into tabs
> - 💎 **Functional buttons** - buttons in the right part
editing form
> - 📍 **Template Tags** - special tags that can be used in email templates
> - 👁 **Readonly** form fields - mostly dates of creation, last modification or links that cannot be changed.
</details>


- **[Clarification of technical requirements with NIX.cz](pages/0000.md)** ⚠️

- [Log in to administration](pages/0001.md)
- [Dashboard, basic division of the application](pages/0002.md)

- **[Basic configuration of the MEET application](pages/0003.md)** ⚠️

- **[Import users using API](pages/0004.md)**

- [FAQ - frequently asked questions](pages/0005.md)

<br />

## 📦 MEET application modules


> [!IMPORTANT]
**[Basic module layout](pages/0006.md)** and how to work with them

- ![Dashboard](../_data/000.svg#gh-light-mode-only) ![Dashboard](../_data/dark/000.svg#gh-dark-mode-only) **[ Dashboard](pages/0002.md)**


- **[Core](pages/0007.md)** *(Main Modules)*
     - ![Users](../_data/00.svg#gh-light-mode-only) ![Users](../_data/dark/00.svg#gh-dark-mode-only)
     &nbsp;**[Users](pages/0007.md#_1)** 🌎🔧
     - ![Companies](../_data/01.svg#gh-light-mode-only) ![Companies](../_data/dark/01.svg#gh-dark-mode-only)
     &nbsp;**[Companies](pages/0007.md#_2)** 🔧
- **[Meeting](pages/0008.md)** *(Modules related to event organization)*
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

- **[Messaging](pages/0009.md)** *(Modules related to emails, comments and private messages)*
     - ![Mail Templates](../_data/09.svg#gh-light-mode-only) ![Mail Templates](../_data/dark/09.svg#gh-dark-mode-only)
     &nbsp;**[Mail Templates](pages/0009.md#_1)** 🔧
     - ![Messages](../_data/10.svg#gh-light-mode-only) ![Messages](../_data/dark/10.svg#gh-dark-mode-only)
     &nbsp;**[Messages](pages/0009.md#_2)** 🌎
     - ![Queued Mails](../_data/17.svg#gh-light-mode-only) ![Queued Mails](../_data/dark/17.svg#gh-dark-mode-only)
     &nbsp;**[Queued Mails](pages/0009.md#_3)** 🌎

- **[Settings](pages/0010.md)** *(Modules with settings)*
     - ![API Tokens](../_data/18.svg#gh-light-mode-only) ![API Tokens](../_data/dark/18.svg#gh-dark-mode-only)
     **[MEET Server Settings](pages/0010.md#_2)** 🔧
     - ![API Tokens](../_data/12.svg#gh-light-mode-only) ![API Tokens](../_data/dark/12.svg#gh-dark-mode-only)
     &nbsp;**[API Tokens](pages/0010.md#_2)** 🔧

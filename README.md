# MediaGrabber

[![Latest release](https://img.shields.io/github/v/release/petrjones/MediaGrabber)](https://github.com/petrjones/MediaGrabber/releases/latest)
[![Windows x64](https://img.shields.io/badge/Windows-10%20%2F%2011%20x64-0078D6)](https://github.com/petrjones/MediaGrabber/releases/latest)
[![9 language variants](https://img.shields.io/badge/language%20variants-9-268BD2)](#languages)

[English](#english) · [Česky](#česky)

## English

**MediaGrabber by PJSoft is a free, portable Windows application for downloading videos, audio and playlists.** It provides a graphical interface for yt-dlp and FFmpeg, with Basic and Advanced controls for quality, subtitles, playlist selections, album organization, audio loudness and optional SponsorBlock editing.

### Download

**[Download the latest MediaGrabber release](https://github.com/petrjones/MediaGrabber/releases/latest)**

Choose the **MediaGrabber-…-Windows-x64-Portable.zip** file in the release's **Assets** section. Extract the entire ZIP into a folder and run:

```text
MediaGrabber.exe
```

No installation is required. Application files are directly inside the ZIP; keep the extracted files and subfolders together.

**Requirements:** Windows 10 version 1809 or later / Windows 11, 64-bit.

### Main features

- **Basic and Advanced modes:** keep everyday controls simple and expand additional options when needed. The active-options summary discloses settings in collapsed sections.
- **Remember last settings:** optionally restore general download preferences without carrying source links, omissions or time selections over to unrelated jobs.
- **Pause, resume and reorder:** finish the current item before pausing, move waiting albums or videos up/down, then continue. Optional sleep protection keeps the computer awake while downloading; the display may turn off.
- **Multiple links and TXT lists:** use shared settings or configure format, quality, destination and playlist selection separately for each link.
- **History and queue backup:** export/import links and settings without copying media. Already-downloaded warnings take settings and existing files into account.
- **Audio loudness:** keep audio unchanged, write ReplayGain/R128 playback tags, or adjust the audio during final encoding. Level tracks individually or preserve album differences with shared album gain.
- **Optional SponsorBlock:** remove community-marked sponsor messages, intro animations, endcards/credits and subscribe/like reminders from YouTube videos or audio. Works with selected playlist entries; downloaded SRT subtitle timing is adjusted after editing.
- Download video with audio or audio only, with quality and format choices including MP3 presets up to 320 kb/s. Available quality depends on the source.
- Preview available artwork, titles, duration and source information before downloading.
- Select individual playlist items, select all, clear or invert a selection, and enter omissions as compact number ranges. Optional renumbering is available.
- Download a selected time segment. Split a continuous recording into individual tracks when the source provides valid chapter timings, with chapter selection in the preview.
- Organize music into album folders and independently write available metadata and embedded artwork. Album numbering restarts in each album folder.
- Optionally create **cover.jpg**, an **album.m3u8** playback list and an **album.txt** overview with source links.
- Check for duplicates in the chosen destination and its subfolders. A reusable local folder index speeds up subsequent searches.
- Review completed, failed and skipped items with available titles, source links and actual error messages. Retry unfinished items while keeping successful downloads.
- Optionally save unfinished queue jobs and offer to restore them after restarting the application, including their order and paused state.
- Use an optional download history to locate files, copy source links, repeat downloads or remove records without deleting media. Quickly choose among five recent destinations.
- Keep downloading while minimized or behind another application. Optional Always on top, contextual help and silent Windows completion notifications are available.
- Search for alternative recordings in a side panel and review available information before choosing a different link.
- View included component information, licenses and offline guides in **About**. Check GitHub for application updates and update yt-dlp separately from the application.

### Languages

**Nine language variants:** Czech, English, Spanish, German, French, Portuguese (Portugal), Portuguese (Brazil), Polish and Italian.

On first launch without a saved choice, MediaGrabber selects a supported language from the Windows interface language. Unsupported languages use English. A saved manual choice takes precedence.

Changing the interface selects corresponding subtitles, which can also be changed independently or disabled. Subtitle availability depends on the source. Offline guides are included for all interface variants. Source titles and messages from external tools may remain in their original language.

### Audio, albums and duplicate checks

Source audio information and measured output are shown separately. A converted MP3 can have a bitrate of 320 kb/s even when the source used a lower bitrate or another codec. Conversion does not restore details missing from the source, and bitrate alone cannot compare listening quality across different codecs.

Chapter splitting requires timing information supplied by the source; it does not automatically identify songs by listening. A continuous album stored as one video requires its source recording before selected chapters can be exported. Artwork and album metadata are used when available.

The first duplicate index may take longer for a large archive or slow drive and is built in the background. Previously recorded downloads can be verified using their source, settings and existing output files. Older filename matches are suggestions, not proof of an identical recording. Alternative-recording search also uses text and technical information, not audio fingerprinting.

### Audio loudness and SponsorBlock

Loudness processing is **off by default** and currently applies to **audio-only output**. ReplayGain/R128 needs a compatible player with tag-based leveling enabled. Actual file adjustment works independently of that support. Shared album gain preserves relative loudness between album tracks; peak protection can keep some results quieter. Loudness adjustment does not restore missing source quality.

SponsorBlock is **off by default** and relies on community marks for YouTube. Without suitable marks the recording remains whole. A recognized service failure can leave a successful uncut download with a notice; genuine media errors remain errors. It removes marked messages inside recordings, not separate YouTube ads.

Fast cuts preserve the video encoding but can have imprecise boundaries. The optional more precise mode re-encodes the video, takes longer and may change picture quality; frame-perfect boundaries are not guaranteed. SponsorBlock is suspended for manual time segments or chapter splitting. Existing destination files are preserved; choose another folder for an edited variant of an already downloaded recording.

### What's new

Version **4.3.0** brings together Basic and Advanced modes, remembered download preferences, batch links with individual settings, history/queue backup, queue pause and reordering, sleep protection, audio loudness options and optional SponsorBlock editing. Subtitle fallback and chapter-track results have also been improved.

**[Read the 4.3.0 release notes in English and Czech](https://github.com/petrjones/MediaGrabber/releases/tag/v4.3.0)**

### Free use and voluntary support

MediaGrabber is free and will remain free. Contributions toward further development are entirely voluntary. Contributing or declining has no effect on application functionality.

The application includes a support option for those who wish to help with development, testing, translations and ongoing maintenance. Included third-party components retain their respective licenses; details are provided with the application.

---

## Česky

**MediaGrabber od PJSoft je bezplatná přenosná aplikace pro Windows ke stahování videí, zvuku a playlistů.** Nabízí grafické rozhraní pro yt-dlp a FFmpeg se Základním a Rozšířeným ovládáním kvality, titulků, položek playlistu, uspořádání alb, hlasitosti zvuku a volitelného střihu pomocí SponsorBlocku.

### Stažení

**[Stáhnout nejnovější vydání MediaGrabberu](https://github.com/petrjones/MediaGrabber/releases/latest)**

V části **Assets** u vydání vyberte soubor **MediaGrabber-…-Windows-x64-Portable.zip**. Celý ZIP rozbalte do složky a spusťte:

```text
MediaGrabber.exe
```

Instalace není potřeba. Soubory aplikace jsou přímo v kořeni ZIPu; rozbalené soubory a podsložky ponechte pohromadě.

**Požadavky:** Windows 10 verze 1809 nebo novější / Windows 11, 64 bitů.

### Hlavní funkce

- **Základní a Rozšířený režim:** jednoduché běžné ovládání a rozbalení podrobností podle potřeby. Přehled aktivních voleb ukazuje i nastavení ve sbalených nabídkách.
- **Zapamatovat poslední nastavení:** volitelné obnovení obecných předvoleb bez přenášení odkazů, vynechaných položek či časových výběrů na nesouvisející úlohy.
- **Pozastavení, pokračování a změna pořadí:** před pozastavením se dokončí aktuální položka, čekající alba či videa lze přesouvat šipkami. Volitelná ochrana před uspáním udržuje počítač při stahování v chodu; obrazovka může zhasnout.
- **Více odkazů a seznamy TXT:** společné nastavení nebo samostatná volba formátu, kvality, cíle a výběru playlistu pro každý odkaz.
- **Záloha historie a fronty:** export/import odkazů a nastavení bez kopírování médií. Upozornění na již stažené záznamy zohledňuje nastavení i existenci souborů.
- **Srovnání hlasitosti zvuku:** ponechání beze změny, zápis údajů ReplayGain/R128 nebo skutečná úprava při vytváření výsledného zvuku. Lze srovnávat skladby jednotlivě nebo zachovat rozdíly uvnitř alba společným zesílením.
- **Volitelný SponsorBlock:** vystřižení komunitou označených sponzorských vzkazů, úvodních znělek, závěrů/titulků a připomínek odběru či hodnocení z videí nebo zvuku YouTube. Podporuje vybrané položky playlistu a úpravu časování stažených titulků SRT.
- Stažení videa se zvukem nebo samotné zvukové stopy, výběr kvality a formátu včetně předvoleb MP3 až 320 kb/s. Dostupná kvalita závisí na zdroji.
- Náhled dostupného obrázku, názvu, délky a údajů o zdroji před stahováním.
- Výběr jednotlivých položek playlistu, označení všech, zrušení či inverze výběru a zadání vynechání číselnými rozsahy. Volitelné přečíslování.
- Stažení zvoleného časového úseku. Rozdělení souvislého záznamu na jednotlivé skladby, pokud zdroj poskytuje platné časové kapitoly, s výběrem kapitol v náhledu.
- Uspořádání hudby do albových složek a nezávislý zápis dostupných metadat a vložených obalů. Číslování začíná v každé albové složce znovu.
- Volitelné vytvoření obalu **cover.jpg**, seznamu skladeb **album.m3u8** a přehledu **album.txt** se zdrojovými odkazy.
- Kontrola duplicit v cílové složce včetně podsložek. Uložený místní index urychluje další hledání.
- Přehled dokončených, neúspěšných a přeskočených položek s dostupnými názvy, odkazy a skutečnými chybovými zprávami. Opakování nedokončených položek se zachováním hotových souborů.
- Volitelné ukládání rozpracované fronty s nabídkou obnovení po dalším spuštění, včetně pořadí a pozastavení.
- Volitelná historie pro zobrazení souboru, kopírování zdrojového odkazu, opakování stažení či odstranění záznamu bez smazání médií. Rychlý výběr z pěti posledních cílových složek.
- Stahování pokračuje i při minimalizaci nebo překrytí jiným oknem. K dispozici je režim Vždy navrchu, bublinová nápověda a tichá oznámení Windows.
- Hledání alternativních nahrávek v bočním panelu s možností posoudit dostupné údaje před výběrem jiného odkazu.
- Dialog **O aplikaci** s informacemi o součástech, licencemi a místními návody. Kontrola aktualizací aplikace přes GitHub a samostatná aktualizace yt-dlp přímo z programu.

### Jazyky

**Devět jazykových variant:** čeština, angličtina, španělština, němčina, francouzština, portugalština pro Portugalsko, brazilská portugalština, polština a italština.

Při prvním spuštění bez uložené volby se vybere podporovaný jazyk podle jazyka rozhraní Windows. Pokud překlad neexistuje, použije se angličtina. Uložený ruční výběr má přednost.

Přepnutí rozhraní nabídne odpovídající titulky, které lze nezávisle změnit nebo vypnout. Jejich dostupnost závisí na zdroji. Součástí jsou místní návody pro všechny jazykové varianty. Názvy obsahu a zprávy externích nástrojů mohou zůstat v původním jazyce.

### Zvuk, alba a kontrola duplicit

Údaje o zvuku zdroje a změřeném výstupu se zobrazují odděleně. Převedené MP3 může mít datový tok 320 kb/s, i když zdroj používal nižší tok nebo jiný kodek. Převod neobnoví detaily, které ve zdroji chybějí, a samotný datový tok neumožňuje porovnávat poslechovou kvalitu různých kodeků.

Rozdělení podle kapitol vyžaduje časové údaje zdroje; skladby se automaticky nerozpoznávají poslechem. U souvislého alba v jediném videu je před exportem vybraných kapitol potřeba získat zdrojový záznam. Obaly a údaje o albu se používají, pokud jsou dostupné.

První vytvoření indexu duplicit může ve velkém archivu či na pomalém disku trvat déle a probíhá na pozadí. Dříve zaznamenaná stažení lze ověřit podle zdroje, nastavení a existujících výsledných souborů. Shody názvů starších souborů jsou návrhy, nikoli důkaz totožné nahrávky. Také hledání alternativ pracuje s textovými a technickými informacemi, nikoli s hudebními otisky.

### Srovnání hlasitosti a SponsorBlock

Srovnání hlasitosti je **ve výchozím nastavení vypnuté** a zatím se týká **pouze zvukového výstupu**. ReplayGain/R128 vyžaduje podporovaný přehrávač se zapnutým vyrovnáváním podle těchto údajů. Skutečná úprava souboru na této podpoře nezávisí. Společné zesílení alba zachovává rozdíly mezi jeho skladbami; ochrana špiček může ponechat některý výsledek tišší. Funkce neobnovuje chybějící kvalitu zdroje.

SponsorBlock je **ve výchozím nastavení vypnutý** a využívá komunitní označení pro YouTube. Bez vhodného označení zůstává záznam celý. Při rozpoznaném výpadku služby může stažení proběhnout bez střihu s upozorněním; skutečné chyby médií zůstávají chybami. Odstraňuje označená sdělení uvnitř záznamů, nikoli samostatné reklamy YouTube.

Rychlý střih zachovává kódování obrazu, ale může mít nepřesné hranice. Volitelný přesnější střih video znovu kóduje, trvá déle a může změnit kvalitu; přesnost na každý snímek není zaručena. Při ručním časovém úseku nebo dělení kapitol je SponsorBlock pozastaven. Existující cílové soubory zůstávají zachované; pro upravenou variantu dříve staženého záznamu zvolte jinou složku.

### Co je nového

Verze **4.3.0** spojuje Základní a Rozšířený režim, zapamatování předvoleb, hromadné odkazy s individuálním nastavením, zálohu historie a fronty, pozastavení a změnu pořadí, ochranu před uspáním, srovnání hlasitosti zvuku a volitelný SponsorBlock. Vylepšeno je také chování při chybách titulků a počítání skladeb podle kapitol.

**[Přečíst poznámky k vydání 4.3.0 anglicky a česky](https://github.com/petrjones/MediaGrabber/releases/tag/v4.3.0)**

### Zdarma a s dobrovolnou podporou

MediaGrabber je zdarma a zůstane zdarma. Příspěvky na další vývoj jsou zcela dobrovolné. Příspěvek ani jeho odmítnutí nemají vliv na funkčnost aplikace.

Pokud chcete pomoci s vývojem, testováním, překlady a průběžnou údržbou, můžete využít možnost podpory přímo v aplikaci. Přibalené součásti třetích stran si ponechávají vlastní licence; podrobnosti jsou součástí programu.

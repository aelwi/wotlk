# evl_Tricks
## Was kann evl_Tricks?

evl_Tricks wurde ursprünglich rein für Schurken geschrieben, um die Handhabung von Tricks of the Trade Makros zu vereinfachen.
Um nicht in jedem Raid ein Tricks Makro auf einen neuen (off-) Tank umschreiben zu müssen, erlaubt Euch evl_Tricks per Knopfdruck ein Makro auf Euer derzeitiges Ziel umzuschreiben.

Das erspart lästiges Eintragen von Namen, besonders wenn Sonderzeichen enthalten sind (á la "ßµêæ").

Je nach dem mit welcher Klasse Ihr evl_Tricks benutzt, werden unterschiedliche Spells als Grundlage genommen.

Diese sind (Klasse, SpellID, Name):

- DRUID       = 29166, -- Innervate 
- ROGUE		    = 57934, -- Tricks of the Trade
- HUNTER 		  = 34477, -- Misdirect
- MAGE 		    = 54646, -- Focus Magic
- DEATHKNIGHT = 49016, -- Unholy Frenzy
- PALADIN		  =  1022, -- Hand of Protection
- SHAMAN		  =   974, -- Earth Shield
- PRIEST		  = 10060, -- Power Infusion
- WARRIOR		  = 50720, -- Vigilance

## Wie funktioniert evl_Tricks?

evl_Tricks erzeugt in Euren allgemeinen Makros ein neues Makro namens "evl_Tricks".
Ihr habt die Möglichkeit, bis zu 3 Ziele als Empfänger einzutragen, diese werden der Reihenfolge nach abgearbeitet.

Existiert das erste Ziel nicht mehr (Offline, nicht mehr im Raid, ...) wird das zweite Ziel priorisiert, existiert dies auch nicht mehr, wird das dritte und letzte Ziel genommen.

Euer derzeitiges Ziel mit Namen seht Ihr über Eurem derzeitigen Chatfenster: https://imgur.com/a/1HIZM9S

## Wie lege ich Ziele fest?
https://imgur.com/a/CvimPhC

In den Keybinding-Optionen unter Sonstige (Other im englishen Client) könnt IHr für jedes Ziel eine Tastenbelegung vergeben.

- Primary Recipient   -> Erstes Ziel
- Secondary Recipient -> Zweites Ziel
- Tertiary Recipient  -> Drittes Ziel

## Was kann evl_Tricks nicht?
evl_Tricks kann keine Echtzeit-Anpassung von Makros vornehmen.
Hierbei handelt es sich um eine Limitierung seitens Blizzard, zudem kann im Kampf kein Makro umgeschrieben / geändert werden.

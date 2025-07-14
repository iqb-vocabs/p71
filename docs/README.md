# Metadatenprofile für Testaufgaben: Mathematik Sek I

ID of profile-store: `mas1`

Publisher: IQB - Institut zur Qualitätsentwicklung im Bildungswesen

2 Profile definiert:

## Profil "IQB Mathematik Sek I - Aufgabe"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p71/master/unit.json`

### Stimulus

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Entwickler:in | Text | Einzeilig, Sprache(n): de   | iqb_author |
| Klassenstufe | [Vokabular](http://w3id.org/openeduhub/vocabs/educationalLevel/) | url: 'http://w3id.org/openeduhub/vocabs/educationalLevel/', Mehrfachauswahl, Nummerierung unterdrückt | f0 |
| Schulform | [Vokabular](https://w3id.org/kim/schularten/) | url: 'https://w3id.org/kim/schularten/', Mehrfachauswahl, Nummerierung unterdrückt | f1 |
| Für SPF geeignet | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | a1 |
| Kopfhörereinsatz | [Vokabular](https://w3id.org/iqb/v24/kh/) | url: 'https://w3id.org/iqb/v24/kh/', Einmalauswahl, Nummerierung unterdrückt | iqb_phones |
| Leitidee | [Vokabular](https://w3id.org/iqb/v51/im/) | url: 'https://w3id.org/iqb/v51/im/', Einmalauswahl, Zeige nur erste Ebene, Nummerierung unterdrückt | w0 |
| Stimuluszeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_stimulus |
| Aufgabenzeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_unit |
| Anzahl Vorspielen | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_play |
| Quellenangaben | Text | Mehrzeilig, Sprache(n): de   | iqb_copyright |
| Notizfeld | Text | Mehrzeilig, Sprache(n): de   | iqb_note_field |
| Unverträgliche Aufgaben | Text | Einzeilig, Sprache(n): de   | iqb_compatibility |

### Hörsequenz/Video

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Transkript | Text | Mehrzeilig, Sprache(n): de   | iqb_transcript |

## Profil "IQB Mathematik Sek I - Item"

ID of profile: `https://raw.githubusercontent.com/iqb-vocabs/p71/master/item.json`

| Name/Label | Typ | Parameter | ID Profil-Eintrag |
| :--- | :---: | :--- | :---: |
| Taschenrechnereinsatz | Ja/Nein | Text für WAHR: ja, Text für FALSCH: nein | iqb_calculator |
| Itemformat | [Vokabular](https://w3id.org/iqb/v27/ms/) | url: 'https://w3id.org/iqb/v27/ms/', Einmalauswahl, Nummerierung unterdrückt | s1 |
| Anforderungsbereich | [Vokabular](https://w3id.org/iqb/v51/a1/) | url: 'https://w3id.org/iqb/v51/a1/', Einmalauswahl, Nummerierung unterdrückt | s2 |
| Inhaltsbezogener Bildungsstandard ESA primär | [Vokabular](https://w3id.org/iqb/v51/ie/) | url: 'https://w3id.org/iqb/v51/ie/', Mehrfachauswahl | s3 |
| Inhaltsbezogener Bildungsstandard MSA primär | [Vokabular](https://w3id.org/iqb/v51/im/) | url: 'https://w3id.org/iqb/v51/im/', Mehrfachauswahl | s4 |
| Prozessbezogener Bildungsstandard | [Vokabular](https://w3id.org/iqb/v51/p1/) | url: 'https://w3id.org/iqb/v51/p1/', Mehrfachauswahl | s6 |
| Inhaltsbezogener Bildungsstandard ESA sekundär | [Vokabular](https://w3id.org/iqb/v51/ie/) | url: 'https://w3id.org/iqb/v51/ie/', Mehrfachauswahl | s7 |
| Inhaltsbezogener Bildungsstandard MSA sekundär | [Vokabular](https://w3id.org/iqb/v51/im/) | url: 'https://w3id.org/iqb/v51/im/', Mehrfachauswahl | s8 |
| Itemzeit | Zahl | Kommastellen: 0, Mindestwert: 0, Maximalwert: kein, als Sekunden | iqb_time_item |
| Geschätzte Schwierigkeit | [Vokabular](https://w3id.org/iqb/v26/ea/) | url: 'https://w3id.org/iqb/v26/ea/', Einmalauswahl | e4 |
| Technische Besonderheiten der Antwortoptionen | [Vokabular](https://w3id.org/iqb/v27/ti/) | url: 'https://w3id.org/iqb/v27/ti/', Mehrfachauswahl | iqb_itemtech |


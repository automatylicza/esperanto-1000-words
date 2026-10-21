# The 1,000 most common Esperanto words

The 1,000 most frequent Esperanto words, ranked by how often they appear in the Tatoeba sentence corpus, with the part of speech and a short meaning in 11 languages. Ready to use as CSV files and as Anki decks.

The list and its method are explained on [Esperantopedia: the 1,000 most common Esperanto words](https://esperantopedia.org/learn/common-words/), where you can also practise them as [flashcards](https://esperantopedia.org/tools/flashcards/).

## Files

| Language | CSV | Anki |
|---|---|---|
| English | [csv/en.csv](csv/en.csv) | [anki/en.txt](anki/en.txt) |
| German | [csv/de.csv](csv/de.csv) | [anki/de.txt](anki/de.txt) |
| Spanish | [csv/es.csv](csv/es.csv) | [anki/es.txt](anki/es.txt) |
| French | [csv/fr.csv](csv/fr.csv) | [anki/fr.txt](anki/fr.txt) |
| Italian | [csv/it.csv](csv/it.csv) | [anki/it.txt](anki/it.txt) |
| Japanese | [csv/ja.csv](csv/ja.csv) | [anki/ja.txt](anki/ja.txt) |
| Dutch | [csv/nl.csv](csv/nl.csv) | [anki/nl.txt](anki/nl.txt) |
| Polish | [csv/pl.csv](csv/pl.csv) | [anki/pl.txt](anki/pl.txt) |
| Portuguese | [csv/pt.csv](csv/pt.csv) | [anki/pt.txt](anki/pt.txt) |
| Russian | [csv/ru.csv](csv/ru.csv) | [anki/ru.txt](anki/ru.txt) |
| Chinese | [csv/zh.csv](csv/zh.csv) | [anki/zh.txt](anki/zh.txt) |

**CSV** (UTF-8, comma-separated, header row): `rank`, `word` (dictionary form), `part_of_speech`, the meaning in the file's language (column named after the language, e.g. `english`), `per_million` (occurrences per million words of the corpus).

**Anki** (UTF-8, tab-separated): Esperanto word, meaning. In Anki: File → Import, choose the file, "Fields separated by: Tab".

## How the list was made

- **Corpus:** all 822,296 Esperanto sentences in the [Tatoeba](https://tatoeba.org/) export downloaded on 7 October 2026 (5,831,657 words), each sentence counted once.
- **Dictionary forms:** plural *-j* and accusative *-n* removed, all verb forms counted under the infinitive (*lernas* → *lerni*); derived words stay separate (*bona*, *bone* and *malbona* are three entries).
- **Real words only:** a form counts if its dictionary form is in ESPDIC, the Reta Vortaro or Wiktionary, or splits into known roots and affixes. Names are left out.
- **At least 30 contributors:** a word must occur in sentences by at least 30 different Tatoeba contributors, so that one person's template sentences do not push it up.
- **Meanings:** the English meanings come from the English Wiktionary and ESPDIC, shortened and edited; the meanings of grammar words are our own. The other ten languages are translations of the English meanings.

Tatoeba is a collection of written, mostly everyday sentences, many of them translations, so the order differs from lists based on novels, news or speech. The full method and its limits are on the [Esperantopedia page](https://esperantopedia.org/learn/common-words/).

## Licence

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Credit "Esperantopedia (esperantopedia.org)" and share your version under the same licence.

The list builds on sentences from Tatoeba ([CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/)), meanings from [Wiktionary](https://en.wiktionary.org/wiki/Category:Esperanto_lemmas) (CC BY-SA 4.0) and [ESPDIC](http://www.denisowski.org/Esperanto/ESPDIC/espdic_readme.html) by Paul Denisowski (CC BY 3.0).

## Corrections

Found a wrong meaning or a missing word? Open an issue here, or use "Report an error" on any page of [esperantopedia.org](https://esperantopedia.org/).

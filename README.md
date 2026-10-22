# kizamu decks

Anki decks with audio for **German** (vocabulary, grammar, sentences) and **American
English** (C1, C2). Every word, example and sentence has audio.

**[Try sample cards in the browser](https://salmanmohebi.github.io/kizamu-decks-releases/)** ·
**[Download the decks](https://github.com/salmanmohebi/kizamu-decks-releases/releases/latest)** ·
**[Audio on Hugging Face](https://huggingface.co/datasets/salmanmohebi/kizamu-audio)**

## Decks

| File | Deck in Anki | Notes | Cards | Size |
|---|---|---|---|---|
| `kizamu-german-vocab-A1.apkg` | `kizamu-german::vocab::A1` | 784 | 1,568 | 55 MB |
| `kizamu-german-vocab-A2.apkg` | `kizamu-german::vocab::A2` | 652 | 1,304 | 51 MB |
| `kizamu-german-vocab-B1.apkg` | `kizamu-german::vocab::B1` | 1,481 | 2,962 | 131 MB |
| `kizamu-german-grammar.apkg` | `kizamu-german::grammar` | 5,291 | 5,320 | 298 MB |
| `kizamu-german-sentences.apkg` | `kizamu-german::sentences` | 3,187 | 6,374 | 83 MB |
| `kizamu-english-C1.apkg` | `kizamu-english::C1` | 3,000 | 6,000 | 420 MB |
| `kizamu-english-C2.apkg` | `kizamu-english::C2` | 3,000 | 6,000 | 435 MB |

**German vocabulary (A1, A2, B1).** One note per word or sense, two cards: Deutsch →
English and English → Deutsch. The answer shows the forms and grammar, the meaning,
related words and contrasts, usage notes and three translated examples. Nouns come with
the article; short cues separate words with the same spelling (*die Bank*: bank or bench).

**German grammar (A1–B2 + 22 hard topics up to C1).** Fill-the-gap sentences and drills
(rule check, transform, find the mistake, word order, choose the form, join the
sentences). The back explains *this* sentence, shows a typical mistake, gives two more
examples and the rule of the topic. Plus the irregular verbs with all key forms.

**German sentences.** Whole sentences English → Deutsch, listening cards, and
situational phrases (*Themen*: at the doctor, on the phone, …) in both directions.

**American English C1 and C2.** 3,000 notes per level in 60 decks: collocations, phrasal
verbs, idioms, conversation, informal English, work and academic English, key words,
nuance and confusables, pronunciation, grammar. Each note has a Meaning card and a
Usage card (fill the gap, say it, or listen). Set 01 of every category holds the most
useful items. The two levels share no items.

## Import

1. Download the `.apkg` files you want from the
   [latest release](https://github.com/salmanmohebi/kizamu-decks-releases/releases/latest).
2. In Anki (desktop 2.1.50 or newer, AnkiDroid or AnkiMobile): **File → Import**, choose
   the file.
3. The decks come with their own preset (daily new cards, study order, audio autoplay).
   All cards start as new.

Study the parent deck (for example `kizamu-english::C1`) to get a mix of all
categories, or a subdeck to focus on one area.

## How the decks were made

The content was written and then reviewed in separate passes with large language
models, following written authoring guides, and checked by validation scripts
(structure, cloze answers, duplicates, spelling). The audio is synthetic, made with
[Qwen3-TTS VoiceDesign](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-1.7B-VoiceDesign):
a German voice for the German decks and an American English voice for the English
decks. Every clip was transcribed with Whisper and generated again when the transcript
did not match the text. Mistakes are still possible: please open an issue if you find
one.

## License

The decks and the audio are released under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The German vocabulary
uses definitions and inflection data adapted from
[Wiktionary](https://en.wiktionary.org/) (CC BY-SA 4.0), extracted by
[Wiktextract / kaikki.org](https://kaikki.org/).

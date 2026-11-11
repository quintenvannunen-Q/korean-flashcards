# Korean Flashcards (한글)

Flashcard website for practising Korean vocabulary from my Hangeul textbook.

- Flip-card mode and type-the-answer mode
- Korean → English, English → Korean, or mixed
- Missed words come back later in the round
- Pronunciation via the browser's Korean text-to-speech

Everything is in `index.html` — no build step needed.

## Adding words

Open `index.html` and find `const DECKS = [`. Each deck looks like this:

```js
{id:"f2", name:"Final consonants 2", words:[["딸기","strawberry"],["물","water"]]},
```

Add a new line with a unique `id`, a `name`, and a list of `["Korean","English"]` pairs.

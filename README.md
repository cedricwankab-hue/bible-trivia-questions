# Bible Trivia Questions and Answers (KJV): open dataset

500 multiple-choice Bible trivia questions with answers, a short explanation and a King James Version reference for every answer. Made by [Bible Academy](https://bibleacademyapp.com), the Bible quiz app for young adults.

- **264** questions on the 66 books of the Bible (4 per book)
- **224** questions on 112 Bible characters (2 per character)
- **12** questions on well-known Bible stories
- Levels: 256 easy, 178 medium, 66 hard
- Every answer is explained and tied to a verse (KJV, public domain)
- Formats: [`bible-trivia-questions.json`](bible-trivia-questions.json) and [`bible-trivia-questions.csv`](bible-trivia-questions.csv)

Free to use for youth group games, Sunday school, small groups, Bible study apps, Discord or Telegram bots, quiz generators and research, as long as you credit Bible Academy (see License).

## Fields

| Field | Description |
|---|---|
| `id` | Stable identifier, `BA0001` to `BA0500` |
| `category` | `book`, `character` or `story` |
| `subject` | The book, character or story the question is about |
| `level` | `easy`, `medium` or `hard` |
| `question` | The question |
| `choice_a` to `choice_d` | Four answer choices |
| `answer` | The correct letter (`A` to `D`) |
| `answer_text` | The correct answer, written out |
| `explanation` | Why this is the answer, in one or two sentences |
| `reference_kjv` | Where the answer is found, e.g. `1 Samuel 17:40` |
| `source` | The quiz page on bibleacademyapp.com this question comes from |

## Example

```json
{
  "id": "BA0301",
  "category": "character",
  "subject": "Caiaphas",
  "level": "easy",
  "question": "What office did Caiaphas hold?",
  "choice_a": "Commander of the temple",
  "choice_b": "Governor of Judea",
  "choice_c": "Ruler of the synagogue",
  "choice_d": "High priest",
  "answer": "D",
  "answer_text": "High priest",
  "explanation": "Matthew speaks of “Caiaphas the high priest,” to whose house Jesus was taken after his arrest; John adds that he held the office “that same year.”",
  "reference_kjv": "Matthew 26:57"
}
```

## How the questions were made

The questions come from the question bank of the Bible Academy app. Each question has a single correct answer found in the biblical text, an explanation, and a reference. Verse quotations are taken from the King James Version (public domain). The questions are written from a Protestant, evangelical point of view, and where Christians disagree on an interpretation the question sticks to what the text says.

Found a mistake? Open an issue with the question `id` and the reference, and it will be corrected.

## More

- Thousands more questions, at your level, with every answer explained: [Bible Academy on the App Store](https://apps.apple.com/us/app/bible-academy-quiz-study/id6824841635) and on the web at [app.bibleacademyapp.com](https://app.bibleacademyapp.com)
- Free Bible quizzes by book and by character: [bibleacademyapp.com/quiz](https://bibleacademyapp.com/quiz/)
- Free printable Bible trivia PDFs: [bibleacademyapp.com/printables](https://bibleacademyapp.com/printables/)

## License

The questions, answer choices and explanations are © 2026 Bible Academy and licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You can copy, adapt and use them, including commercially, as long as you give credit, for example:

> Bible trivia questions from Bible Academy (https://bibleacademyapp.com), CC BY 4.0

Bible verses quoted are from the King James Version, which is in the public domain.

## Citation

```
Bible Academy (2026). Bible Trivia Questions and Answers (KJV): open dataset of 500 questions. https://bibleacademyapp.com
```

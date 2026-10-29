# Review — N3 (Claude Fable 5.1)

## Difficulty

- **vocab**: too_easy — Most items are genuine N3, but several target words (旅行, 閉める, 休む, 忘れる, 持つ, 散歩, 曇る) are N5/N4 level and drag the section below N3.
- **grammar_reading**: on_level — Grammar points and reading passages are squarely N3 and keys are correct, but every もんだい1 and もんだい3 answer is option 1 (21/39 overall), so positions must be shuffled before use.
- **listening**: on_level — Scripts are natural, support the marked answers, and spoken options match the printed ones; the distractor-elimination patterns are typical of N3 聴解.

## Local checks

- grammar_reading: answer 1 is correct for 21/39 questions — positions are unbalanced

## Fixed automatically (7)

- `vocab` もんだい2 問12 — **too_easy**: 旅行 is an N5 word with N5 kanji; asking an N3 candidate to pick 旅行 from 族行/旅考/旅幸 tests nothing at this level.
- `vocab` もんだい2 問13 — **too_easy**: 閉める is N5 vocabulary and 閉 is a basic kanji; the item is well below N3 kanji-writing level.
- `vocab` もんだい3 問21 — **too_easy**: 学校を休む with 熱 is N5-level vocabulary and context; distractors are also elementary.
- `vocab` もんだい3 問25 — **too_easy**: かさを電車に忘れた is a textbook N5 sentence; the target verb 忘れる and all distractors are N5.
- `grammar_reading` もんだい1 文の文法1 問12 — **too_easy**: もし～たら with ～ましょう is basic N4 conditional usage and the distractors (ても/のに/ながら) are not competing conditionals, so no N3 'conditional nuance' is tested.
- `grammar_reading` もんだい2 文の文法2 問23 — **multiple_correct**: Two natural orderings exist: 部長にかわって私が (★=かわって, option 2) and 私が部長にかわって (★=に, option 4). 「今日は私が部長にかわって新しい計画を説明します」is fully natural, so the key is not unique.
- `grammar_reading` もんだい2 文の文法2 問26 — **multiple_correct**: Besides 兄はもう家に帰っている (★=家に), the ordering 兄は家にもう帰っている (★=もう) is grammatical and acceptable, so the ★ position has two defensible answers.

## Reported, not changed (0)


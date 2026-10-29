# Review — N3 (Claude Fable 5.1)

## Difficulty

- **vocab**: on_level — Readings, kanji choices, collocations and usage items (解決, 混雑, 表情, 延期, 保つ, 落ち着く, 断る) sit squarely in the N3 word list, with only a few N4-leaning items such as 届ける and 参加.
- **grammar_reading**: on_level — Grammar points and reading passages are appropriate for N3, but all 18 items in もんだい1 and 21 of 39 overall have option 1 as the key, so the answer positions must be reshuffled before use.
- **listening**: on_level — Dialogues use N3 grammar (させられる, わけじゃない, さえ) at a reasonable pace, though the もんだい3 scripts omit the spoken options and every もんだい4 key is option 1, so positions should be rebalanced.

## Local checks

- grammar_reading: answer 1 is correct for 21/39 questions — positions are unbalanced

## Fixed automatically (4)

- `grammar_reading` もんだい2 文の文法2 問19 — **multiple_correct**: Both 「私はだんだん日本の生活に慣れてきたと思います」 and 「私は日本の生活にだんだん慣れてきたと思います」 are natural, so ★ can be either 生活に (option 2) or だんだん (option 4). The adverb だんだん is freely movable, which makes two keys defensible.
- `listening` もんだい3 問13 — **script_mismatch**: The もんだい3 instruction says nothing is printed on the answer sheet and that the question and choices are heard, but the script only contains the question; the four options are never spoken, so the learner cannot answer. The spoken options must be added to the script.
- `listening` もんだい3 問14 — **script_mismatch**: Same problem as Q13: the instruction states the options are only heard, not printed, but the script never reads out the four choices.
- `listening` もんだい3 問15 — **script_mismatch**: Same problem as Q13 and Q14: the four options are not spoken in the script although the instruction says they are only heard, not printed.

## Reported, not changed (2)

- `grammar_reading` もんだい2 文の文法2 問24 — **ambiguous**: The intended order 部長にかわって私が説明をしました gives ★＝私が, but 部長にかわって説明を私がしました (★＝説明を) is also grammatical, so the item does not have a single clean ordering as a 文の組み立て item should.
- `listening` もんだい2 問10 — **unnatural_japanese**: The line 「雨や事故によるものではございません」 is not something a real station announcement would say; it exists only to eliminate distractors and sounds artificial. Removing it would also make the item a fairer listening test.

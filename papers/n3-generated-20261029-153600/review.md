# Review — N3 (Claude Fable 5.1)

## Difficulty

- **vocab**: on_level — Kanji readings and vocabulary are mostly N3 (預ける, 制度, 混む, 複雑, 賛成, くたくた, あらゆる), though a handful of items (人口, 結果, 準備, 練習) sit at N4 and make the set slightly soft.
- **grammar_reading**: on_level — Grammar items squarely target the listed N3 points (うちに, さえ, にかわって, わけではない, causative-passive, いただけませんか) and the reading passages are appropriate though on the short/simple side for N3 中文.
- **listening**: on_level — Dialogues use N3-appropriate keigo and business/daily situations, but several もんだい5 items are N4-level, and most もんだい1/2 scripts omit the opening situation+question line that the instructions promise (only Q8 has it), which should be added before recording.

## Fixed automatically (5)

- `vocab` もんだい5 問34 — **multiple_correct**: 「人がたまる」(e.g. 駅前に人がたまっている) is attested, natural colloquial Japanese, so option 2 is also defensible as a correct use of たまる. Replace it with a clearly wrong sentence.
- `grammar_reading` もんだい1 文の文法1 問1 — **multiple_correct**: 「雨が降らないあいだに洗濯物を取り込みましょう」is grammatical and used by native speakers, so option 1 competes with the keyed うちに. Replace あいだに with a distractor that cannot follow 降らない.
- `grammar_reading` もんだい2 文の文法2 問21 — **multiple_correct**: Two orderings are grammatical: 「私にとって家族は何より大切なものだ」(★=は) and 「私にとって何より家族は大切なものだ」(★=家族), so the ★ slot has two defensible answers. Rewrite so only one order works.
- `grammar_reading` もんだい2 文の文法2 問22 — **multiple_correct**: Both 「部長にかわって私が会議に出席する」(★=私が) and 「部長にかわって会議に私が出席する」(★=会議に) are grammatical, so options 1 and 4 can both fill ★. Merge 会議に with the verb to force a single order.
- `listening` もんだい5 問27 — **too_easy**: 「何名様ですか」→「二人です」is an N5/N4-level exchange with transparent distractors; it does not test N3 listening or grammar. Replace with a polite-request exchange at N3 level.

## Reported, not changed (0)


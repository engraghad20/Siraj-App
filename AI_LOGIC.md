Surah: An-Nas
Total words: 20

## Scoring Logic ##
accuracy = ((20 - totalMistakes) / 20) * 100
totalMistakes = missingCount + extraCount + replacedCount

## Recommendation Rules ##
If accuracy >= 90: Excellent! Repeat once for reinforcement.
If 70 <= accuracy < 90: Good! Repeat twice and focus on mistakes.
If accuracy < 70: Split the surah and repeat verse-by-verse.

## Mistake Types ##
- Missing word
- Extra word
- Replaced word

## Output Structure (Example) ##
mistakes:
- missing: [ ... ]
- extra: [ ... ]
- replaced: [ {expected:"...", got:"..."} ]

## Sample Output ##
Accuracy: 80%
Mistakes: missing=[الناس], replaced=[{expected: "ملك", got: "مالك"}]
Recommendation: Good! Repeat twice and focus on mistakes.

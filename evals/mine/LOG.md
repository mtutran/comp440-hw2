# Drafts log: mine-format_rules

Items 001 to 003 were written by the student. Below is every item Claude drafted, and the
student's decision on each (accepted, edited or rejected).

## Batch 1 (7 drafts, asked for on 2026-10-24)

### Draft 1
{"subtype": "text", "prompt": "Write a text to my study group saying Thursday's meeting moves to the library at 6 pm. Use exactly three bullet points.", "must_mention": ["thursday", "library"], "task_check": "Is a message to the study group saying Thursday's meeting moves to the library at 6 pm, written as exactly three bullet points.", "length_hint": "3 bullet points", "predicted_winner": "succinct", "why": "Tests whether the answer uses exactly three bullet points as specified."}

Decision: accepted

### Draft 2
{"subtype": "apology", "prompt": "Write a one-sentence apology to my roommate Priya for eating her leftover pizza.", "must_mention": ["priya", "pizza"], "task_check": "Is an apology to Priya for eating her leftover pizza, and is exactly one sentence.", "length_hint": "1 sentence", "predicted_winner": "succinct", "why": "Tests whether the answer stays at exactly one sentence as specified."}

Decision: accepted

### Draft 3
{"subtype": "congratulations", "prompt": "Write a congratulations message to my cousin Malik on finishing his first marathon, all in lowercase letters.", "must_mention": ["malik", "marathon"], "task_check": "Is a congratulations message to Malik on finishing his first marathon, with no capital letters.", "length_hint": "1-3 sentences", "predicted_winner": "succinct", "why": "Tests whether the answer uses only lowercase letters as specified."}

Decision: accepted

### Draft 4
{"subtype": "reminder", "prompt": "Write a reminder to my soccer team that practice on Saturday is cancelled because of rain. Do not use any exclamation marks.", "must_mention": ["practice", "rain"], "task_check": "Is a reminder to the soccer team that Saturday practice is cancelled because of rain, and contains no exclamation marks.", "length_hint": "1-3 sentences", "predicted_winner": "succinct", "why": "Tests whether the answer avoids exclamation marks as specified."}

Decision: accepted

### Draft 5
{"subtype": "request", "prompt": "Write a message to my landlord asking them to fix the leaking kitchen sink. Do not use any numbers.", "must_mention": ["sink", "leak"], "task_check": "Is a message to the landlord asking them to fix the leaking kitchen sink, and contains no numbers, written as digits or as words.", "length_hint": "2-4 sentences", "predicted_winner": "succinct", "why": "Tests whether the answer avoids numbers as specified."}

Decision: edited (the prompt should state explicitly no numbers, written as digits or as words). Edited prompt: "Write a message to my landlord asking them to fix the leaking kitchen sink. Do not use any numbers, written as digits or as words."

### Draft 6
{"subtype": "decline", "prompt": "Write a note to my teammate Sofia declining her invitation to the hackathon this weekend. Keep it under 15 words.", "must_mention": ["sofia", "hackathon"], "task_check": "Is a note to Sofia declining her invitation to the hackathon this weekend, in fewer than 15 words.", "length_hint": "under 15 words", "predicted_winner": "succinct", "why": "Tests whether the answer stays under 15 words as specified."}

Decision: rejected (tests the same thing as item 003, a word limit)

### Draft 7
{"subtype": "welcome", "prompt": "Write a short welcome message for new members of the chess club, ending with a question.", "must_mention": ["chess", "welcome"], "task_check": "Is a welcome message to new members of the chess club whose last sentence is a question.", "length_hint": "2-3 sentences", "predicted_winner": "succinct", "why": "Tests whether the answer ends with a question as specified."}

Decision: accepted

## Batch 2 (2 drafts, asked for on 2026-10-25)

### Draft 8
{"subtype": "instructions", "prompt": "Write instructions for my little brother on how to feed my cat while I'm away. Write them as a numbered list of exactly four steps.", "must_mention": ["cat", "feed"], "task_check": "Is a set of instructions for feeding the cat, written as a numbered list of exactly four steps.", "length_hint": "4 numbered steps", "predicted_winner": "succinct", "why": "Tests whether the answer is a numbered list with exactly four steps as specified."}

Decision: accepted

### Draft 9
{"subtype": "email", "prompt": "Write an email to my lab partner Daniel asking to swap our Wednesday lab slot. Start with a subject line written in all capital letters.", "must_mention": ["daniel", "wednesday"], "task_check": "Is an email to Daniel asking to swap the Wednesday lab slot, whose first line is a subject line written entirely in capital letters.", "length_hint": "subject line plus 2-4 sentences", "predicted_winner": "succinct", "why": "Tests whether the answer starts with an all-capitals subject line as specified."}

Decision: accepted

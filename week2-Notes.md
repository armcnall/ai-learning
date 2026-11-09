# Week 2 Notes

## Chp 1: Basic Prompt Structure
- messages alternate user and assistant, starting with user
- Use PROMPT for individual messsages. Use SYSTEM_PROMPT for overall style of responses.

## Chp 2: Being Clear and Direct
- in these exercises you can prompt Claude simply to meet grading requirements. For example, if the grading criteria is only a story of more than 800 words, you can just put the grading criteria in the prompt.

## Chp 3: Role Prompts
- You can create a role context for Claude by entering a role description in the SYSTEM PROMPT

## Chp 4: Separating Data and Instructions
- XML tags are a simple way to separate instructions from data and variables.

## Chp 5: Formatting Output & Speaking For Claude
- no notes from this section

## Chp: 6 Procognition Thinking
- order of concepts and tags can influence Claude's answer. For example, it can take sarcasm literally unless you flag it with XML tags.

## Task 2: Prompt practice (MTSamples specialty routing)

**Setup:** claude-haiku-5-5, 8 practice notes, 6 specialties, 2 few-shot examples

### Run 1 (baseline)
- Plain accuracy: 1.0
- Thinking accuracy: 1.0
- Format failures: 0
- Misses: (note number, dataset label, Claude's answer, my verdict: Claude wrong / label debatable)

### Changes
| # | What I changed | Plain | Thinking | Effect |
|---|----------------|-------|----------|--------|
| 1 |                |       |          |        |
| 2 |                |       |          |        |

### Labels I think the dataset got wrong
-

### Thinking vs. no thinking
- Did thinking change any answers? Which ones? No
- Was the reasoning useful when I read it? yes
- Worth roughly double the cost for Objective 3? Yes / No, because...

### Takeaways for Objective 3
-
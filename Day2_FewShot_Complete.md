# Day 2: Few-Shot Prompting - Zero/One/Few-Shot Testing
**Date:** January 2, 2026
**Status:** Partial practice (went out). Tested Scenario 1 & 2 fully.

## Core Notes (Few-Shot Framework)
Examples > Instructions (AI copies patterns better than following rules)

1. More examples = Better accuracy (2-5 usually enough)
   Why: The Model recognizes pattern to follow.

2. Structure matters: INPUT/OUTPUT vs colon vs Q/A  
   Why: Specific format prevents default generic output.

3. Use for: Classification, extraction, content creation, and psychology exercises.

**Formats that work:**
- Q: question A: answer
- "Text": "Classification"
- INPUT: text OUTPUT: classification
- QUESTION/ANSWER

**Limits:**
- Too many examples = token limit (model loses context)
- Bad examples = bad patterns (toxic/biased output)

## Test Results: Scenario 1 (Psychology Exercises)

**Zero-Shot:**
- Overly explained, no structure
- Used pre-trained general data
- No pattern recognition

**One-Shot:**
- Recognized example pattern
- Word count still exceeded
- Sentences not concise (1 line each)
- Relied on pre-trained data as a starting point

**Few-Shot (2+ examples):**
- Exact intended output
- Perfect structure (3 steps)
- Good pattern = Good results

**Insight:** 2+ examples = quality adherence to user needs.

## Test Results: Scenario 2 (Job Extraction)

**Zero-Shot:**
- "Extract" worked as an action word
- Output in steps, not single sentence format

**One-Shot & Few-Shot:**
- Both followed the example pattern (: separator)
- Structured exactly like examples

**Insight:** Examples control format perfectly.

## Key Takeaways
1. Few-shot = Show AI the exact pattern you want
2. Zero-shot = Generic rambling
3. One-shot = Better but inconsistent
4. **Client value:** Structured outputs (tables/lists) = ₹5k/gig
5. **My edge:** Psychology scenarios + perfect structure

  

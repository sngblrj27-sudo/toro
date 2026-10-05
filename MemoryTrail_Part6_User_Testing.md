# MemoryTrail — Part 6 User Testing

## Objective
We tested whether MemoryTrail helps users retrieve photos using incomplete memories instead of exact dates, album names, or device information.

## Participants
Planned testing with 5 users representing parents/families, students, professionals, travelers, and users with large photo libraries.

## Test Scenarios
1. Birthday + child + red dress
2. Beach trip + uncertain location
3. Family event + blue clothing
4. Failed search + guided refinement
5. Open-ended personal memory

## Metrics
- Search success rate
- Time-to-photo
- Number of searches
- Refinement attempts
- Abandonment
- Wrong selections
- User confidence
- Ease of use

## Key Findings (proposed/simulated — replace with real observations)
1. Users naturally describe memories using events, people and visual clues rather than exact metadata.
2. Users expect uncertain information such as “maybe Goa” or “around 2018” to remain flexible.
3. Users need more context explaining why a result matches their memory.
4. Guided refinement is important when the first search fails.
5. Showing relevant memory cues alongside results can increase user confidence.

## What We Learned
The MVP direction is promising because it moves photo retrieval from rigid keyword/metadata search toward memory-based retrieval. Real-user testing is required to validate retrieval accuracy, usability and time-to-photo.

## Next Improvements
- Improve result explanations
- Make uncertain clues softer
- Add guided refinement suggestions
- Cluster similar photos by event/person
- Test with larger real-world photo libraries

## Success Criteria
The MVP will be considered successful if users can find the intended photo faster, with fewer failed searches and less abandonment.

## 5-User Testing Script

### Introduction
“We are testing this prototype, not you. There are no right or wrong answers. Please think aloud while you use it. Try to find the photo as you naturally would. If you get stuck, tell us what you expected to happen rather than asking us how to proceed.”

### Task 1 — Birthday + red dress
“Imagine you want to show someone a birthday photo of your child. You remember your child was wearing a red dress, but you don't remember the year, album, or device.”

Ask: “Using MemoryTrail, find the photo you believe matches this memory.”

### Task 2 — Beach trip + uncertain location
“You remember a beach trip, but you're not sure whether it was in Goa. You don't remember the year.”

Ask: “Find the photo from this trip.”

### Task 3 — Family event + blue clothing
“Find a family-event photo where someone was wearing blue. You don't remember the date.”

### Task 4 — Failed search and refinement
“Find a photo from a family trip where my friend was wearing a yellow shirt.”

After an imperfect result: “This isn't the photo you were looking for. What would you do next?”

### Task 5 — Open-ended memory retrieval
“Think of a memorable photo in your library that you would normally have difficulty finding. Try to find it using MemoryTrail.”

## Example Proposed Findings / Quotes
These are examples only and must not be presented as actual participant quotes until live testing is completed.

Finding 1: Users naturally describe memories.
Example: “I don't remember the year. I just remember it was my daughter's birthday and she was wearing red.”

Finding 2: Uncertain information should not become a hard filter.
Example: “I'm not completely sure it was Goa, so I don't want Goa to remove the photo.”

Finding 3: Users need an explanation for why a result appeared.
Example: “This looks like the photo, but why did you show me this one?”

Finding 4: Guided refinement reduces abandonment.
Example: “I know this isn't it, but I don't know what else I should search.”

## Example Results Table — Template Only
| User | Tasks completed | Avg. time | Refinements | Main issue |
|---|---:|---:|---:|---|
| U1 | 4/5 | 42 sec | 2 | Wanted more result context |
| U2 | 5/5 | 35 sec | 1 | Understood search quickly |
| U3 | 4/5 | 51 sec | 3 | Didn't understand refinement |
| U4 | 5/5 | 39 sec | 2 | Uncertain location worked well |
| U5 | 3/5 | 64 sec | 4 | Too many similar results |

Do not claim these example numbers came from real participants. Replace them after actual testing.

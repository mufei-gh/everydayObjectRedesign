# Object Analysis & Missing Affordances of Stanley Cups
## 1. Awareness Gaps
### Use Scenario: 
A commuter brings the tumbler to work, refilling it throughout the day and moving between desk, meeting rooms, and common areas. The tumbler is sometimes placed into a bag between meetings and sometimes left behind on a surface.
### The Gap: The tumbler has no awareness of its own state.
- Doesn’t know whether it’s been washed recently.
- Doesn’t know how long the liquid has been sitting inside. Old water is unknowingly sitting
for days. Stale water is being consumed unknowingly. Subtle mold/smell buildup
- Doesn’t know whether the lid is fully sealed or misaligned. Surprise leaks when the straw
or the lid isn’t properly aligned
- Doesn’t know where it was placed.
- Doesn’t know the temperature of the liquid inside (Listed here but low priority? Since we
all know when it’s too hot to drink)
### Opportunities: State awareness
- An indicator (e.g., color change ring) showing “time since refill” or detecting
mold/limescale
- A simple mechanical or magnetic cue indicating lid alignment/seal status
- A minimal findability or “last interaction” cue that helps users recover the cup when it
slips out of attention
### Justification
- Users care and might worry about cleanliness. This externalizes that cognitive load
- Also saves the cognitive load and energy to remember where the cup was left or find the
cup
- Hygiene issues are common but invisible until they’re gross
- The cost of uncertainty (smell, leaks, embarrassment) is higher than the cost of state
signaling?/Prevent errors at a lower cost than responding after failure
## 2. Feedback Gaps
### Use Scenario: 
A user finishes assembling the tumbler (lid on, straw inserted) and prepares to either drink from it or put it into a bag.
### The Gap: The tumbler does not clearly communicate their location and whether it is in a safe or transportable state.
- The cup doesn’t tell whether its scale-free/clean
- There is no clear confirmation that the lid is fully seated
- There is no feedback indicating whether the straw is positioned safely. Errors (leaks,
spills) are only discovered after failure
- No indicator for need to clean/drink/carry mode. The cup feels unpredictable when moved
Overall, users rely on habit or assumption
### Opportunities: System-level feedback
- Tactile or audible confirmation when the lid reaches a fully sealed state
- Clear visual cues that communicate “safe to drink” vs. “safe to carry”
- Feedback that reflects the combined state of lid and straw, not just individual parts
- Sends signals to the user about where it was left
### Justification
- Users think in terms of outcomes, not mechanisms. They don’t ask, “Is the lid aligned?” Instead, they ask, “Can I put this in my bag?”
- Leaving the gaps unaddressed forces users to mentally simulate risk every time they move the cup.
- Providing clear feedback reduces errors and anxiety, and adds efficiency.
## 3. Adaptation Gaps
### Use Scenario:
Different users, small hands, left-handed users, people with limited grip strength, use the tumbler across desk, gym, and commuting contexts.
### The Gap: The tumbler is physically static and assumes a single “average” user.
- Handle size is fixed
- Straw height is fixed
- Weight does not adapt as the cup empties

### Opportunities: System-level feedback
- Optional grip sleeves or straw variants

### Justification
- Adaptation improves inclusivity without changing the core function of the object. Given the tumbler’s wide demographic adoption, a one-size-fits-all design quietly excludes many users.
- Addressing this gap increases comfort and long-term use

## 4. Anticipation Gaps
### Use Scenario: 
A user transitions from drinking at a desk to carrying the tumbler in a bag or car.

### The Gap: The tumbler does not anticipate context changes.
- The straw remains open even when transport is likely
- Risk management is entirely manual

### Opportunities: 
- A transport-oriented state that restricts the straw when movement is detected
- A lid behavior that defaults to safety during transitions

### Justification
- When an object requires users to always think one step ahead, it fails to support real-world attention limits. Addressing this gap makes the tumbler more reliable in motion, where failures are most costly.

## 5. Social Fit Gaps
### Use Scenario: 
A user brings the tumbler into meetings, classrooms, or shared public spaces.

### The Gap: 
- There is no clean way to store or rest the straw
- Users must invent workarounds (napkins, removal, avoidance)

### Opportunities: Design a clear straw resting state
- A built-in dock or cover for the straw
- A closed configuration suitable for formal or shared environments

### Justification
- Objects that fit socially are used more consistently.
- This gap affects confidence and triggers hygiene anxiety in daily adoption. Leaving it unresolved silently discourages use in exactly the environments where the object is most visible.

# Propose a Redesign

## 1. Design Rationale
- Unknown hygiene state (time since refill/wash, moisture persistence, limescale accumulation), Awareness 
- Unknown seal state (lid + straw alignment), Awareness
- Unknown location / presence (“I forgot where I put my cup”), Awareness
- No confirmation of “safe to drink” and “safe to carry” system state, Feedback
- No proactive response when transitioning into transport or being left behind, Anticipation
- There is no clean way to store or rest the straw, Social Fit

“Is my cup okay to drink from, safe to carry, and still with me?”

## 2. Proposed Features

- Color-Change Hygiene Ring
  - A thin ring near the lid interior made from moisture-reactive material
  - Gradually changes color based on prolonged moisture exposure

- Magnetic Alignment + Tactile Click + Visual Feedback
  - Small embedded magnets align lid and straw correctly
  - When aligned:
    - Lid snaps into place
    - Produces a tactile and audible “click”
    - A green dot lights up

- Recessed Straw Dock + Visual Feedback
  - Straw snaps horizontally or vertically into a recessed groove
  - When docked:
    - Straw opening is covered
    - Visual state reads as “closed”

## 3. Social Considerations: 

- Habit Change:
  - Today: users instinctively try to “put the straw away,” wipe it, or avoid bags
  - With the redesign, the user uses a straw dock

- The redesign is largely invisible and normalized.
  - No screens, sounds, or attention-seeking feedback
  - Visual cues (status indicator, hygiene ring) are subtle and glanceable
  - The mechanism reads as good mechanical design, not “smart tech”

## 4. Tradeoff Analysis: 
- Folding mechanism may loosen after extended use
- Repeated sliding could degrade gasket effectiveness over time

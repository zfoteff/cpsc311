Exam 1 Review
===============
# Norman Design Principles
## Affordances
Relationship between the interacting agent (usually person) and an object.  
Relationship between what you want to do and what is possible with the object  
NOT properties of objects
* Interacting agent has capabilities and intentions that dictate how object might be used
* Object has properties that suggest how it might be used
## Signifiers
Signifiers "signify" affordances. Indicat where the action should take place on an object using labels, markers, sounds, or other indicators
Add signifiers to instictively let a person know how to use an obj  
* Line on train platform
* Spots on clear windows
* Pull/pull labels on doors
## Contraints
**Constriant**: Percieved limitiation of the actions that are possible with an object, based on the objects appearance  
Limits set of possible actions with an object  
* Helps prevent user from selecting incorrect options 

Four types of constraints:
1. Physical
    * Usb type c: reversible
    * USB micro b: not reversible, but legacy cable and easy to find
    * Lightning cable: reversible, but proprietary
2. Cultural: Allowable actions in social situations
    * Face forward in elevator
    * Give seats up for older people on bus
    * Others
    * Can be universally or culturally specific
      * Can change over time
3. Semantic: Possible actions constrained by the meaning of a situation
    * Driver faces towards road in a car
    * Skiers face down the mountain
    * Must face a computer screen to do work
4. Logical: Possible actions constrained by what is left over when all other actions are exhasted
## Mappings
Layout of interaction objects
## Feedback
Sending information back to the user about what has abeen done. Includes sound, tactile, and visual feedbacks  
Feedback should be:
* Immidiate
* Prioritized
* Specific
* Relevant
## Conceptual Model
Simplified description of how something works, including parts and possible actions and effects  
Each conceptual model is specific to the person using the thing  
A correct conceptual model should allow a person to simulate its interactions mentally

## Visibility
Make the important actions the user can take on the object distinct and clear

## Transfer effects
Transfer knowledge of a system's iteractions across applications and platforms 

# Seven Stages of Action Model
## Seven Stages of Action
1. Establish goal
2. Plan course of action to meet goal
3. Specify sequence of action steps
4. Perform the steps
5. Percieve the state of the system
6. Interpret the perception
7. Compare outcome against the goal

Gulfs of Execution occur when user cannot map their intention to an action
* Occurs within stages 2-4
  * Can users perform action without extra effort? ("How do I work this?")
  * Do system level actions match the ones the user wants to perform? ("What can I do?")

Gulfs of Evaluation occur when the user can't tell whether an action succeeded
* Occurs withing stages 5-7
  * System should provide info on its state that is easy to interpret and maintain, as well as match the way the user thinks about the system

## 3 Levels of Processing
Emotions influence action. There are three levels of cognitive and emotional processing:  
1. Visceral: Reaction to present state (pre-emotional). Generated in performing an percieving.
   * Reponses are fast and subconscious
   * Linked to musculature
     * tense = positive
     * relaxed = negative
   * Examples
     * Startle reflex
     * Fear of height
     * Dislike of bitter things
2. Behavioral: Reaction to matches between present state and learned patterns. Generated by expectations relative to specifications or interpretations.
   * Responses are largely subconscious, producing unexplainable actions 
   * Linked to thoughts
   * Examples
     * Picking up a cup
     * Hitting a ball
     * Talking
3. Reflective: After the fact reasoning analysis and decision making. Generated by planning or comparing
   * Responses are slow, deep, and conscious
   * Linked to assigning causality to past, present, and future events
   * Examples
     * Guilt
     * Pride
     * Praise
     * Blame

# Cognitive Walkthrough
Can be viewed as a practical application of Normans 7-stages model  
**What is it:** Simulating users completing tasks with a user interface  
**Goals:**
* Identify potential usability problems
* Generate ideas for improving design

**Advantages:**
* No real users needed

**Disadvantages:**
* Value depends on skill of evaluator
* Analysis can be narrow or superficial
* Does not estimate severity or scope of problems identified

**Steps:**
1. Gather Material
2. Walk through correct action sequences from perspective of typical users, keeping in mind the following questions
   * Will the user know what to do next? 
   * Will the user notice how to perform the correct action (Gulf of exec.?)
   * Will the user interpret the system response correctly (Gulf of eval.?)
3. Summarize results
4. Brainstorm solutions to identified problems

# Perception
## Perceptual bias
### Perceptual priming
* Biased by context
* Biased by goals
* Inattentional blindness
* Implications for design
  * Prime users to interpret information displays as you want them to
  * Consistency
### Gestalt principles
Gestalt principles of visual perception
* **Proximity**: Relative distance between objects in a display affects our perception of whether and how the objects are organized into subgroups. Objects that are near each other appear grouped, while those farther apart do not
* **Similarity**: Objects that look similar appear grouped, all other things appear equal
* **Continuity**: Visual perception is biased to perceive continuous forms rather than disconnected segments. This describes our abilitity to resolve ambiguous or missing data
* **Closure**: Our visual system automatically tries to close open figures to they are percieved as objects, rather than segments of a whole
* **Symmetry**: We tend to parse complex scenes in a way that reduces the complexity. This often means data in our visual field usually has more than one interpretation, but we organize it in such a way that it is simplified and symmetric
* **Figure/ground**: Our mind seperates the visual field into the figure (foreground) and the ground (background). The foreground consists of elements in the scene that are the object of our primary attention and the background is everyone else. For example, when a smaller element overlaps a larger element the smaller is considered the foreground, and the larger is considered the background
* **Common fate**: This concerns moving objects. Objects that move together are percieved as grouped or related
## Limits of vision
### Color
Our vision is optimized to see contrasts. Color descrimination depends on how the colors are presented  
**Key Point**: Don't rely solely on color to encode information
* Pale colors are harder to distinguish
* Smaller color patches are harder to distinguish
* Color patches harder to distinguish if they are seperated
* Red-green color-blindness is most common, and should be accounted for in designs by putting color scheme through color filter or rendering in black and white 
### Peripheral vision is poor
Our peripheral vision is best at detecting motion and contrast
**Key Point**: Design implication: Put key information in foveal field (where users are looking) 
### Reading is unnatural
**Key Point**: Don't make users read too much. Avoid unfamiliar words.
## Limits of memory
Working memory is limited to 3-5 items  
**Key Points**:
* Don't make users remember things across screens
* Allow users to see instructions while doing things
* Be careful with modes
  * Users should always know what mode they are in
  * Avoid them otherwise
* One "call-to-action" per page

Long-term memory is faulty  
**Key Points**:
* Don't burden long-term memory
* Provide resources to remind users of difficult-to-remember information like passwords
* Make interface consistant
* **Recognition is better than recall**
  * Humans have evolved to recognize things quickly 
  * We assess situations quickly (often wrong)
  * Recognize faces extremely fast
  * Recognize complex patterns

User's focus intently on their goals, not the interface  
They will only notice and remember things crucial to their task, and will be blind to other changes to the interface. When a goal is reached, users will tend to forget to wrap up loose ends. Users also tend to interpret iterface items literally relative to our goals.

**Key Points**:
* Make changes obvious
* Provide external memory aids to help users keep track of progress
* Automatically wrap up loose ends for the user, or help them wrap them up
* Anticipate users' goals and match options at each decision point

# Learning and Decision Making
## System 1
"Old brain" + "mid brain"  
System 1 = fast, automatic, inpulsive, associative, emotional, and unconscious process

## System 2
"New brain"  
System 2 = slower, conscious, reflective, deliberative, analytical, rational, logical processing

## System 1 v. System 2
We are of two minds: unconscious and conscious

### System 1 (Unconscious)
'Zombie' or 'robotic' processes
* Substitutes easier problem for problem it can't solve
* Bases judgments only on what it perceives
  * If conflicting data isn't present, it doesn't exist
* Filters perceptions based on goals and beliefs provided by system 2

### System 2 (Conscious)
Processes that require focus and attention
* Often lazy; Accepts system 1's inaccurate estimates
* Effort and will required to operate it
* Need to get things exactly right

**Key Points:**
Don’t require users to engage system 2 unnecessarily 
* Indicate system status and progress toward goal 
* Guide users towards their goals 
* Let people fall into learned, automatic routines 
* Tell users exactly what they need to know 
* Don’t make people diagnose system problems 
* Minimize the number and complexity of settings 
* Let people use perception rather than calculation 
* Make the system familiar 
* Let the computer do the math
* **Scaffolding**: Promote learning by providing users with challenging tasks that are just beyond their 
current knowledge level and skills 
* Promote learning through active engagement 

## Decision Making
People are irrational: We will gamble (take are chances with low odds) in order to avoid big losses, or in 
order to obtain a large gain. People are biased by vivid memories and their imaginations. People are biased by what is immediately before them

**Key Points** Decision support: Help System 2 override System 1  
* Provide all options (abstract if necessary) 
* Help users find alternatives 
* Present unbiased data 
* Don’t make people perform calculations 
* Prompt users to make assumptions and assertions explicit 
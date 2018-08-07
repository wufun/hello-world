- *freehand movements with a single camera.*
- **Challenges**
1. accuracy
2. fine movements
3. tactile feedback
4. gesture delimiter
# 1. Related Work
## 1.1 Selection on a 2D surface
* pie menus reduce selection time and errors compared to linear menus
* marking menus are faster than linear menus
* target or goal crossing technique  *faster than point and click.*
## 1.2 Selection with 3D tracking devices
- Ray-casting have **better** target selection performance than hand extension approach
- moving forward and backward for selection was significantly slower than other directions
- Depth Ray: 1-step approach faster than other 2-step techniques.\
outperformed other one-step approaches *eg. point cursor and 3D bubble cursor.*
## 1.3 Freehand interaction
- intuitive but needs more precise operation
# 2. Touching the third dimension with freehand gestures
*bare hands tracked by a single remote camera without wearing any markers or holding any devices*
## 2.1 Design space comparison
- A stylus could make better straight strokes compared to a mouse.
## 2.2 Design challenges for freehand gestural interaction
### 2.2.1 Gesture delimiters
### 2.2.2 Gesture input and feedback
- resolution - fatigue - feedback: visual or auditory
### 2.2.3 High presicision interaction
# 3. Study 1: object selection in densely populated 3D environments
## 3.1 Freehand selection technique design
### 3.1.1 Selection metaphor
- Cone cast selection technique
### 3.1.2 Disambiguation method
- maker and menu disambiguation techniques
### 3.1.3 Gesture Design
1. **Marker cone**:
- &ensp;&ensp; selection and disambiguation in one phase
- &ensp;&ensp; select the closest object to the marker in 3D
- &ensp;&ensp; *two hands*. raise the other hands for confirmation
2. **Menu cone**:
- pull or push as confirmation
- hand motion speed as the trigger.
## 3.2 experiment result
- **menu cone ❤️** outperformed marker cone for freehand gestural selection.
## 3.3 Environment effects
- Affected by target visibility
- target distance: no significant effect
- preferable in some directions: right and down. visual feedback;
# 4. Study 2: option selection in 2D layout.
- goal crossing: Reach // speed: Stroke
- Reach is slower but more accurate than Stroke.
# 5. Study 3: option selection in a 3D layout

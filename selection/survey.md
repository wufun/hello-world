# 1. Introduction
- Two main 3D
selection metaphors can be identified: \
virtual hand and
virtual pointing 
- Unlike classical virtual hand techniques,virtual
pointing techniques allow the user to select objects beyond their
area ofreach and require relatively less physical movement.
# 2. Human pointing models
- Fitts' law: most successful and complete explanation from all the existing human motor models
## 2.1 Fitts' law
> Several works have extended the Fitts’ Law formulation to
higher dimensional tasks [66] and to account for noise [47] and
latency [97].
## 2.2 Optimized initial impulse model
- To explain the logarithmic speed-accuracy trade-off defined by Fitts' law.
- **Acqusition tasks** are subdivided in two phases:
&ensp;&ensp;1. ballistic phase 
&ensp;&ensp;2. corrective phase
# 3. Classification of selection techniques

## 3.1 Selection tool
- virtual hand and virtual pointing techniques are completely determined by
the selection tool.
- ***Virtual hand techniques*** use 3D cursors (the underlying selection tools,e.g.a sphere,cube or hand avatar),
- ***virtual pointing techniques*** employ virtual rays (the underlying selection tool is typically a ray or a cone).
- ***!!!*** HYBRID APPROSCH : Depth ray
## 3.2 Tool control
- one hand or both hands; wrist orientation; 
- **Virtual Pointing**: eye-hand visibility mismatch \
&ensp;&ensp;Raycasting from the eye

### 3.2.1 Selection tool DoFs
- The number of effective DoF depends on the technique.
- $$$ Tow handed techniques also increase the number of DoFs the user has to control.

### 3.2.2 Control-display ratio
- determines how translations
and rotations of the input device(x) are transferred to the selection
tool (X).
- A constant CD ratio dosen't change the ID (Index of Difficulty)
- CD ratio-based techniques can be
classified into three groups: \
&ensp;&ensp;&ensp;manual switching, target oriented
and velocity oriented techniques.

## 3.3 Motor and visual space relationship
- Two main interaction spaces are involved during the selection
of a 3D object in a VE: the motor space and the visual space.
- **Coupled**: propriopceptive feedback of the hand. (virtual hand)
- **Decoupled**: visual feedback;
- Motor space - Control space - Visual space.
- Control space: define the scope of the user's actions.

## 3.4 Disambiguation mechanism
dense environment
1. manual 
2. heuristic
3. behavioral

## 3.5 Selection trigger
- Selection Confirmation
1. Event
2. Gesture
3. Voice Command
4. No explicit command

## 3.6 Feedback
- visual feedback
- haptic and acoustic feedback

# 4. Factors influencing performance
Froma
usability point of view, a selection technique has to \
(1) provide rapid selection,\
(2) be accurate and error-proof,\
(3) be easy to understand and control and\
(4) produce low levels of fatigue.
## 4.1 Target geometry
- Object's size and location can effect selection performance.
- Techniques attempting to increase W:
&ensp;&ensp; 1. increase the area of influence of the selection tool
&ensp;&ensp; 2. increase the activation area of targets in control space 
&ensp;&ensp; 3. dynamically increase the size of the targets
- increase both W and A: CD ratio adjestment
&ensp;&ensp;&ensp;&ensp;A can be reduced by decreasing the CD ratio during
ballistic movements and W can be increased by increasing the
CD ratio during corrective movements.

## 4.2 Object distance and area of reach
- Depth perception becomes an additional limiting factor when
selecting distant objects
- navigate-to-select

## 4.3 Object density


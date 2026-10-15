# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

### AIM: 
### To model/draw the 2D mechanical component according to the specified 
### dimensions using CAD software (e.g., AutoCAD) or traditional engineering 
### drawing tools.

### Requirements / Tools Needed: 
### * *Software:* CAD software (AutoCAD, SolidWorks, CATIA) OR *Drawing 
### Instruments:* Mini-drafter, compass, protractor, set squares, engineering 
### scale, pencils (H, 2H), eraser, and drawing sheet. 
### * *Commands / Drafting Tools:* 
### * *Draw Commands:* Line, Circle (Center-Radius, Center-Diameter), Arc, Trim, 
### Offset.

### Procedure           
### 1: Set Up Workspace & Reference Axes* 
### 1. Set units to millimeters (mm) and precision to 0.00. 
### 2. Draw a vertical center line passing through the vertical axis of symmetry. 
### 3. Establish key horizontal center lines relative to a origin reference (center of the central 
### profile): 
### * Top circle center: *65 mm* above the central axis. 
### * Middle lower horizontal reference: *26 mm* below the central axis. 
### * Bottom circle center: *24 mm* below the middle horizontal reference (*50 mm* total below 
### central axis). 
<img width="559" height="611" alt="{3093CA51-6B42-4684-9D53-EB9CD69F7BBF}" src="https://github.com/user-attachments/assets/79555a3b-4650-45f5-b16d-4a50f4cd4b0b" />


### Step 2: Draw the Central Profile (Spline / Keyway Design)
### 1. Draw the central reference circles from the main origin: 
### * Inner circle: *$\varnothing 40\text{ mm}$* (Radius = 20 mm). 
### * Outer pitch circle: *$\varnothing 66\text{ mm}$* (Radius = 33 mm).  
### 2. Create the internal circular cutouts: 
### * Radius: *$R6\text{ mm}$*. 
### * Position these $R6$ semicircular cutouts evenly spaced (Polar Array with 6 items) 
### centered around the central circle profile. 
### 3. Trim unnecessary arcs to form the continuous internal star/spline shape.
<img width="633" height="549" alt="{8822EF33-6DBE-429C-AC77-BDC88829FA5B}" src="https://github.com/user-attachments/assets/79de891b-74e0-4c8d-8f1d-165beb37b86b" />


### Step 3: Draw Outer Lugs & Circular End 
### 1. *Top Lug:* 
### * At $65\text{ mm}$ above the center, draw an inner hole of *$\varnothing 20\text{ mm}$* 
### ($R10\text{ mm}$) and an outer boundary circle of *$\varnothing 32\text{ mm}$* ($R16\text{ 
### mm}$). 
### 2. *Bottom Center Lug:* 
### * At $50\text{ mm}$ below the main center along the vertical center line, draw an inner hole 
### of *$\varnothing 10\text{ mm}$* ($R5\text{ mm}$) and outer arc of *$\varnothing 20\text{ 
### mm}$* ($R10\text{ mm}$). 
### 3. *Left and Right Lower Lugs:* 
### * Locate centers at horizontal distance *$47\text{ mm}$* left and right of vertical center line, 
### and vertical distance *$26\text{ mm}$* below the main center. 
### * Left side: Inner hole radius *$R7\text{ mm}$, outer curve radius *$R10\text{ mm}$**. 
### * Right side: Outer curve radius *$R10\text{ mm}$* with symmetric layout.
<img width="728" height="713" alt="{886C0BC7-9D4C-4DF9-B25C-E054C4E244D2}" src="https://github.com/user-attachments/assets/37c23c29-144d-42ce-8c4c-86308fe0a2a8" />



### Step 4: Draw Connecting Tangent Arcs & Fillets 
### 1. *Upper Outer Curves:* 
### * Connect top lug outer boundary to central profile using concave arcs of radius *$R64\text{ 
### mm}$* on both left and right sides (using Tangent-Tangent-Radius / TTR Fillet). 
### 2. *Lower Outer Tangent Arcs:* 
### * Draw connecting fillets between the central body and side lugs: 
### * Left side transition fillet: *$R20\text{ mm}$*. 
### * Right side transition fillet: *$R10\text{ mm}$*.
### * Draw the bottom arc linking the bottom center lug to side lower lugs with radius *$R20\text{ 
### mm}$*.


### Step 5: Trimming and Dimensioning 
### 1. Use the *Trim* tool to remove all construction lines, overlapping arcs, and internal
### geometric entities. 
### 2. Apply centerlines to all circular holes. 
### 3. Add key dimensions as shown in the diagram ($\varnothing 20$, $\varnothing 32$, 
### $\varnothing 40$, $\varnothing 66$, $R64$, $R20$, $R10$, $R7$, $R6$, and linear offsets 
### $65$, $26$, $24$, $47$).

### Output:
<img width="748" height="545" alt="{E87F6EF9-6779-4CE7-9536-27DCBB6CC616}" src="https://github.com/user-attachments/assets/bd820233-8764-4e88-a42e-7f18d85b33a1" />

<img width="760" height="637" alt="image" src="https://github.com/user-attachments/assets/f12e1986-58be-498d-98ee-9e40eef6726a" />




### Result: 
### Thus the given sketch is drawn  and drafted using fusion 360 tool

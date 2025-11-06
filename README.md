# CIS 5660 HW04 Procedural Buildings

## Reference Images
The goal is to recreate a very simplified case of this piece I drew a while back:
<img width="778" alt="temple" src="https://github.com/user-attachments/assets/625699f9-a808-4a03-afb0-c0d504618b6b" />

You can find the design breakdown here:
https://www.artstation.com/artwork/q9gZO2

References used heavily for this piece:

![Red](https://github.com/user-attachments/assets/4c7f6f81-8351-4cee-891a-56d304fa12b7)
- from Spirited Away

![t_120-byodoin-temple-top-01](https://github.com/user-attachments/assets/b763c3a2-b052-43a6-88a2-f43c5ceb0217)
- toy model from https://www.japan-wooden-model-kits-zootoyz.shop/contents/en-us/p25104_Byodoin-Hououdo-Wooden-Japanese-Temple-Model-Kits-by-Woody-JOE.html
---
### Main Architectural Features + Assets
The design can be broken down to three levels: 
- The top
  - Embellished design on the tip of the roof, rounded top with small gated courtyard. with horizontally elongated windows and golden plated designs underneath 
- The middle
   - Middle building structures have a different window style (red panel then window panel)

- The bottom
   - Bottom buildings are mostly red wall with small windows in the top

- Red rectangular gates
- Frilly rooftop that fans out
- Cube-like shape in sub-buildings
- large rectangular window panes divided up into squares
- white paper screen above glass windows
- Golden ribs under roof for support
- Red pillars
- Triangular caved-in rooftops on parts of buildings jutting out

- For this assignment, we will be ignoring the trees and rocks for now.

### Result
- Here is the final result of the scene:

<img width="575" height="458" alt="building" src="https://github.com/user-attachments/assets/b5f5dd56-5c43-45f1-867e-881291452ae0" />
<img width="664" height="472" alt="buildings" src="https://github.com/user-attachments/assets/bde4ba4b-d3ea-4c7b-8f41-8f72b8b9bf67" />

- User inputs include stacking on multiple floors, and adjust each floor's width, height, and depth. Optionally, the user can also toggle on and off pillars in that particular floor:
  
<img width="1236" height="643" alt="Screenshot 2025-11-05 at 11 20 19 PM" src="https://github.com/user-attachments/assets/32411114-8ad4-4478-8d5a-f2f2966fedb3" />

- Sticking onto the building are two types of windows, the screen door, which the user can manually adjust its width and height altogether, and are automatically generated based upon the width and depth of the building floor unit. The fences will resize based upon the width and depth, as well. The roof's slope and ridge-frequency are also adjustable parameters in the scene:
  <img width="1224" height="546" alt="Screenshot 2025-11-05 at 11 25 25 PM" src="https://github.com/user-attachments/assets/45caa387-4417-42db-8c86-9bee552f21bc" />


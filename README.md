# TheCatsitter_BAE305
This is the documentation and Online Design profile for the BAE 305 semester design project. Group Members: Rebecca Deason, Kaitlyn Duncan, Elizabeth Howard, Lauren Doyle, Colby Redding 

# Summary
For the BAE 305 group project, the CatSitter was invented. The CatSitter is a consumer good that allows cat owners to be at ease when gone for long periods of time during the day and even on vacation, knowing that their pet is holistically taken care of. The device is an automated pet feeder that dispenses a specified amount of food at timed intervals during the day (owners can chose 1/2 cup or full cup to be dispensed every 12 hours by pressing a blue or red button). This feeding mechanism utilizes servo motors, a 3D printed tube, and a 2 liter bottle that holds kibble. In addition to feeding your pet, the device has a treat dispensing mechanism so owners can give their pets extra love by sending treats at timed intervals (every 2 hours). The treat dispensing mechanism is very similar to the food dispensing mechanism, just on a much smaller scale. The CatSitter also includes a play function that activates at timed intervals (every 3 hours). This mechanism utilizes two servo motors which work together to move a laser pointer in different planes of motion. A cat can chase the laser dot for enrichment and physical activity. All of the circuitry for these 3 mechanisms (the feeder, the treat dispenser, and the laser pointer) as well as battery packs which act as the power source are enclosed in a box designed with openings for only what the cat needs to be in contact with. A scrum agile sprint method was used throughout the semester to track goals and progress on this project to ensure completion and success. 
# Design Description


## Materials used: 

-	3- 1'x2' ¼” birch plywood sheets 
-	500g of Various colors of PLA 
-	10- sticks of Hot melt glue
-	2- 1" diameter magnets
-	Wood glue
-	2L soda bottle 
-	Plastic disposable water bottle
-	2- 1” hinges with screws 
-	2- ¼” nut and bolts
-	Electical tape
-	2- push buttons attachable to a breadboard
-	5- mini-servos 
-	20- jumper wires
-	3- buzzers attachable to a breadboard
-	3- RedBoard Arduino controllers
-	3- 2"x3.5" breadboards
-	6" of 3M Velco tape

## Special tools used: 
-	Glue gun
-	Prusa 3D printers
-	Laser cutter
-	Bandsaw 
-	Small screw driver
-	Xacto Knife
-	Wood clamps
-	A ruler/measurement devices

## Mechanic Design:

### 3D Printed parts assembly
Some specific pieces were 3D modeled for the feeder using OnShape online. The treat dispenser works similarly to the food dispenser, and also required some parts to be 3D modeled.  The 4 parts total that had to be 3D modeled include: 
1.	The feed dispenser
2.	The treat dispenser
3.	The food holder
4.	3 rotating plates 

All the STL files can be accessed in the Github repository. All of these parts were 3D printed using PLA on the Prusa 3D printers. The tubes for both the feeder and treat dispenser are complicated, round designs that would be difficult to 3D print as whole, singular pieces. So, the pieces were sliced in half in OnShape, and the halves were printed separately. Later they were attached together using hot glue and a ¼” nut and bolt.

The food dispenser is the most important part of this project. The food dispenser tube piece has 3 different 3D printed parts attached to it: the food holder base (this connects the 2 liter to the tube that dispenses the kibbles into the cat’s bowl) and 2 moving plates. This assembly rendering illustrates how this pieces are connected:
![Assembly 1](https://user-images.githubusercontent.com/102251593/165393820-82d2c84a-5e47-40f7-9d0c-e028c64fae9d.png)
A 1" diameter magnet of depth 0.156" was hot glued into the small circular cutout to aid in the attachment of the 2 liter to the tube. 2 inches lengthwise from the opening of the bottle were removed, and 0.5" long slots were cut into the end. These slots allowed for glue to seep in between them when attaching the bottle to the base piece. Additionally, 4 “ were removed from the other end of the bottle. That piece was saved, and is used as a removable top. 4 pea-sized glue nubs were glued onto the bottle to help with the secure attachment of the removable top.

Plates were designed to attach perfectly onto the head of the servo, and the servos were attached to the side of the box using glue and tape to secure them into place. The servos were attached such that the movement of the plate would not be inhibited in any way.

![Tube_magnet holder](https://user-images.githubusercontent.com/102251593/165538759-7411145d-2647-418e-a037-0d6c0b18a0f1.png)
The treat dispenser works the same as the food dispenser, but was scaled down. A plate slides in and out of the thin cutout of the tube. This allows for the dispensation of the treats when necessary, and holds the treats back when it is not time to dispense. An image of this assembly can be seen below. Additionally, a small water bottle was used to hold the treat supply, similar to the 2 L bottle in the food dispenser mechanism. The part of the bottle where the cap screws on and the cap itself were both used to attach the bottle to the treat dispensing tube. The cap sat in a cutout in the wooden top of the box, and was hollowed out. This way, the treat holding bottle could be easily screwed in or unscrewed from the box. About 1” down from the thick end the water bottle, the plastic was cut, leaving a small bit connected. This way, the treat holder had a sort of lid that could be opened for the easy refilling of treats.
![Assembly 2 (1)](https://user-images.githubusercontent.com/102251593/165395272-aa60b9f2-5a4c-48f8-a666-930bae5a280d.png)


### Box Assembly
The box was constructed of ¼” birch plywood. Other types of wood and plywood can be used, but most woods do not work well in the laser cutter due to fumes and unsafe materials being burnt.  Illustrator was used to create the design, which was then exported to a lasercutter. All Illustrator files are attached in the Github library for reference. 
To build the box, we cut the wood into two 12”x8” sections for the sides of the box, a 12”x8.5” piece for the base, two pieces measuring 7.75”x8” for the front and back, and 3 smaller pieces for the top. One of the pieces is particularly thin, and sits between the other 2 top pieces. Hinges are attached to this thin middle piece, such that the other two pieces can be lifted up for viewing the inside of the box. Additionally, another piece was cut (measuring 7.75”x8”) to help support the feeder tube. The illustration below shows the design of the box. All pieces were attached using standard wood glue and clamps to hold the pieces together while they dry. The middle section and the top pieces were glued lastly, after all the 3D printed pieces were in place. This was done so that the inside was easily accessible while assembling all of the circuitry and tubes and such.

![Top pic](https://user-images.githubusercontent.com/102251593/165577752-f8b6315e-9757-4ae3-981c-ecfc5e0e675d.jpg)

Once the base and sides of the box were glued together, the 3D printed parts were glued in. The food dispenser tube was hot glued to front side of the box (on the inside) such that the hole in the tube aligned with the hole in the wood. The middle supporting piece of wood was glued in next, wedging the food tube between front piece of wood and the middle piece of wood. The treat dispenser was glued on so that the hole in the tube fit flush into the circular hole cut out in the wood on the left side of the box. Additionally, the top of the treat dispenser tube was aligned with a circular hole in the top of the box. Next, the 3 top sections of wood were glued on using wood glue and clamps. The top pieces were attached in the same order that they appear in the illustrator file, with the thinnest piece of wood laying between the two wider pieces.

### Laser Pointer Assembly
The laser pointer was created with 2 mini servos, one controlling movement in the xy plane and one controlling movement along the z axis. The laser pointer was attached to the arm of the z-axis servo using electrical tape. The z-servo motor was attached to the xy-servo moving arm with hot glue. The xy-servo was attached via a 3D printed part found online. This STL file can be found in the model files labeled “laser case”. The servo was glued to this case and the case was glued onto the left side of the box wall at about 2” in with the top of the servo case flush with the top of the box. There should be nothing inhibiting movement of either of the servo arms. 
![IMG-0791](https://user-images.githubusercontent.com/102251593/165579792-ac6e9481-960a-42b4-8b90-6768f8f5d05b.jpg)
A breadboard with the 2 control buttons was placed in the rectangle cutout on the right side of the box. This hole was covered by tape so only the two buttons were visible and accessible. Other 2 breadboard and Arduino controllers were attached to the sides of the box using 3M Velco tape and electrical tape. All wires for each board were bundled together and extended using electrical tape. 

Both bottles should be removable, and the box can optionally be painted. We painted our pet-friendly black and attached fun charms to bling it up. But this is purely cosmetic and completely optional. 
![IMG-0789](https://user-images.githubusercontent.com/102251593/165579783-0d365616-ca6b-4582-ae9f-a519a382bf2e.jpg)
## Circuit Design 


### Cat Feeder code summary:
In the Cat feeder code, there is an if else loop. The first loop is run when the red button(button1) is pressed. When going through the first loop the first servo opens for 2 milliseconds which releases about XX cup of food into the holding department then shuts. The second servo opens for several seconds allowing for all the food to be released into the bowl and shuts the servo gate back. A buzzer then goes off for one second alerting the cat there is food in the bowl. The if else loops have the process as the if loop, but with different time amount for the first servo to open. In this loop the gate is open for 5 milliseconds allowing for XX cups to be dropped. Both the if and if else loop repeat every12 hours to feed the cat. The else loop is for when neither button is pressed and keeps both servos in the closed position until one button is pressed. 
<img width="577" alt="cat feeder circuit" src="https://user-images.githubusercontent.com/102251593/165538922-eaa1a985-7b93-4617-ba75-329e9722380b.png">
### Treat code summary:  

The treat dispenser code is very similar to that of the food dispenser but only uses one servo. A speaker alerts the cat treats are about to drop then opens a servo for 2 milliseconds releasing a few treats then closes back and waits 2 hours before releasing more treats.  

<img width="536" alt="treat dispenser" src="https://user-images.githubusercontent.com/102251593/165538906-a9279138-ef0f-4154-88a9-fc2b32617530.png">

### Laser Code Summary:

The void loop in the laser code has a list of different servo positions that move each servo to a different location when the laser is on and holds a position for a certain amount of time before moving again. There is also a buzzer hooked up to the circuit that plays a different sound than the treat and food dispenser to alert the cat that it is time to play with the laser. 

<img width="583" alt="laser pointer" src="https://user-images.githubusercontent.com/102251593/165538932-2e7458c7-55ef-40b3-acd7-414b12f7d46b.png">

# Discussion of Design
### Measuring Design
The food dispenser uses the speed of a servo arm to precisely measure the amount of food that the pet is given. The servo is normally closed, sealing off the bottom of the 2 liter of food. To dispense food, the servo quickly rotates out of and back into the slit in the tube, allowing a specific amount of food to dispense. This amount can vary based on the delay set in the code for the servo. If the same design is used with the same parts, this should replicate perfectly. The benefit of this mechanism is that it is easy to control and is precise enough for our purposes. This feeder does not necessarily need to be extremely precise. The food should be within a 1/16th of a cup, and this system allows for that much precision. This design could improve in precision by using stronger and more precise motors. 

Another servo is attached to the front plate for the food to sit in that slot until it is time to deliver the food. This servo is designed to stay closed and open when the food from the measuring plate is dropped in the tube. This arm rotates about 10 seconds after the food is dispensed into the slot. This makes the design more insect repellent by having an extra boundary between the environments and the food. 

The treat feeder was designed in a similar way. The design is simpler by not including a base servo to control when the tube is open or closed. This makes for a better design, as the base plate would be overkill on such a small part and would not fit nicely into the box. 

### Model design
The models were custom designed for this project. Each plate was designed to be thin and fit snuggly on the end of the servo to create a simple design. These are modeled to include a bevel to be more accurate in movement, and much smaller than the slot size to avoid friction which can greatly affect the efficiency of the servo.

The tubes were designed with attachment to the box in mind. The base tube is designed to sit in the wall of the box, hence the small horizontal section at the bottom of the tube. This design helps with stability of the piece and creates a more cohesive product. The custom design includes a top section that holds the base of the food holder. This part includes a lip that the holder fits into along with a magnet that lines up with a magnet on the food holder base. This magnet helps with the stability of the part and will avoid being turned over by the cat. The tube also has a base of an L-bracket. This bracket also assists in stability of the product and rests on a small piece of wood glued into place. The advantage of this design is that it is very specific yet simple. Each piece fits perfectly into place and is designed for that very purpose. This allows for a fluid design that looks good and functions well. 

### Laser design
The laser toy on the side of the cat feeder was designed with two servos attached to each other. one servo moves in the xy plane while the other moves along the z axis. We attached the two servos by gluing them together, along with taping the laser pointer onto the z-servo. We attached the bottom servo(xy plane) to the side of the catsitter with a 3D printed servo holder that was glued on the side of the box. This allows for the toy to easily be removed and placed in the box if need be.


# Testing Description
This project began with a few brainstorming sessions, where we came up with an original design that would include mechanics, code, and circuitry. The first prototype was made using lower quality materials, in order to test that the servos could work with the mechanical design of the project, and to see if our general design was plausible. After having success with that, we further developed the initial prototype and tested how much space we would need in the box itself for circuitry and stability structures, so that we could start making final design work. After designing the structure and buying and/or printing materials, we dry-fitted all parts that would need to connect to one another to test for tolerance clearance. Parts that did not fit together were filed, sanded, or Dremel'd in order to allow them to fit together comfortably. Once we worked out the tolerances and assembled the project, finally we tested to see that the whole project worked smoothly in conjunction. At this point, we tested the timing of the servo to see how much time was needed to allow the kibble and treats to be dispensed at the proper amounts. While the procedure for releasing food worked, we had to lengthen the amount of time that the treats were released for in order for them to fall down, due to the individual treats being larger than kibble.
# Discussion of Testing
Our system works best for cat owners who are leaving their indoor cats home for a non-extended period of time. Because our design only has space to hold a limited amount of kibble, depending on how much and how often a cat eats, it would only work to take care of the cat for shorter away periods. For example, the Catsitter would be insufficient to care for a cat long-term and shouldn't be used as a singular care method if the owner were to be gone for several months or more. Additionally, the materials used to make the design were limited by our personal funding and would not be very weather resistant, and so the Catsitter is best suited for indoor use only. 
# Testing Results
Our initial prototype did function the way we were expecting it to; that is, the servos were able to rotate a piece – we used paper at the time- that would allow for cat food to be held back and then released. This would act as our primary actuation mechanism for the project. We were also able to troubleshoot any other complications we ran into during described testing, and the project did work properly once assembled. Our first issue we ran into with system capabilities when testing was that our 3D printed part for food actuation did not allow for the servo pieces we had also designed and printed to open all the way, at which point we used a Dremel to remove extra material so that the pieces could open fully to allow food to fall through. We also tested all three of the Catsitter's caretaking aspects- the food dispenser, treat dispenser, and laser play toy- to make sure that they worked when placed in our structure and hooked up to the code. The food dispenser and laser play toy functioned as expected, but the time that the treat dispenser is coded to stay open for had to be adjusted. Initially, we had used the same amount of time as the food dispenser. However, because the treats we used to test were larger than the kibble, this initial time that we were using was not sufficient to allow the treats to fall through, and had to be lengthened.

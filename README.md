# TheCatsitter_BAE305
This is the documentation and Online Design profile for the BAE 305 semester design project. Group Members: Rebecca Deason, Kaitlyn Duncan, Elizabeth Howard, Lauren Doyle, Colby Redding 

# Summary
For the BAE 305 group project, the CatSitter was invented. The CatSitter is a consumer good that allows cat owners to be at ease when gone for long periods of time during the day and even on vacation, knowing that their pet is holistically taken care of. The device is an automated pet feeder that dispenses a specified amount of food at timed intervals during the day (owners can chose 1/2 cup or full cup to be dispensed every 12 hours by pressing a blue or red button). This mechanism utilizes servo motors and a 3D printed structure that holds kibble. In addition to feeding your pet, the device has a treat function where you can give your pet extra love by sending treats at timed intervals (every 2 hours) which uses a similar dispensing design mechanism with a servo motor as the feeder just at a much smaller scale. There is also a play function at timed intervals (every 3 hours) where the device utilizes two servo motors to move a laser around in different planes of motion for a cat to chase for enrichment and physical activity. These three functions and their mechanisms along with circuitry that has code loaded and the power source of battery packs are enclosed in a box designed with openings for only what the cat needs to be in contact with. A scrum agile sprint method was used throughout the semester to track goals and progress on this project to ensure completion and success. 
# Design Description


Materials used: 

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

Special tools used: 
-	Glue gun
-	Prusa 3D printers
-	Laser cutter
-	Bandsaw 
-	Other simple wood-working tools
-	A ruler/measurement devices

Mechanic Design:

The basis of this design was based on a gravity feeder with servo arm controlling the amount of food that would exit the feed holder. This piece of design will be how food is measured and is controlled by a delay. To execute this design, many specific pieces where designed. The mechanic design was 3D modeled using OnShape online. There were 6 parts that were designed and modeled by hand. There include: 
1.	The feed dispenser
2.	The treat dispenser
3.	The food holder base
4.	3 rotating plates 

All the STL files can be accessed in the Github repository. All of these parts were 3D printed using PLA on the Prusa 3D printers. The tubes both are complicated round designs that would be hard to 3D print like normal, so the pieces were sliced in half to print both sides separately and be attached with glue and a ¼” nut and bolt through the flange section. 

The dispenser part is the main part of this design. The tube piece is that base that has 3 parts attached to it. This assembly rendering illustrates how this is connected: 

The treat dispenser works the same as the food dispenser but on a smaller and similar scale. The treat plate fills in the slot in the treat dispenser and has the same functionality as the food feeder. Additionally, the whole small water bottle was used. The top had the center cut out but the screw sides still in tack, and that piece would glue into the tube enough so the water bottle could fulling screw into place. About 1” down from the top of the water bottle was cut almost 80% around, leaving a bit connected to have the top still attached to the bottle. This bottle will act as the treat holder.

The food holder is attached similarly, but slightly different. The base was 3D printed to have a 2L attach to it and a magnet in the round cut out on the flat edge. A 1" magnet of depth 0.156" was hot met glued into this slot. A 2L had 2 inches from the opening of the bottle removed and 0.5" slots cut vertically fron this cut. These edges were seperated out and hot melt glued onto the base piece. The bottom of the bottle was completely cut off about 4" down. This will be used as a top, but is now removable. Then 4 pea-sized glue nubs were melted into place to secure the top. 

The plates were designed to attach perfectly onto the head of the servo and be attached to the side of the treat dispenser and the food dispenser via glue and tape to secure them into place. They were attached in a way that would not inhibit the movement of the plate in any way and were sitting in the slot of their designated design. 



A box constructed of ¼” birch plywood. A design was created in Illustrator to be exported to the laser cutter to laser cut the wood. Other types of wood and plywood can be used but be careful as most woods do not work well in the laser cutter due to fumes and unsafe materials being burnt. 

The box was constructed of 2 12”x8” sides, a 12”x8.5” base, a front and back of 8”x8”, a top consisting of 3 pieces that are connected with a hinge, and a middle 8”x8” piece that holds that adds structure to the feeder. The illustration below shows the design of the box. All pieces were attached using standard wood glue and clamps to hold the pieces together while they dry. The middle section and the top were not added until later to ensure all the 3D printed pieces were in place. 

Once the box was constructed, the 3D printed parts could be attached. The food dispenser tube could be attached with hot melt glue to the front piece along with the middle piece, wedging both sides into it. The front of the tube should fit flush with the front wood piece. Now what this piece is in place, the top can be assembled on top using wood glue and clamps. These pieces were spaced out and attached in the same way they are designed in the Illustrator file. 
To attach the treat dispenser, the piece was glued to fit flush into the circular hole cut out in the left side piece. The top was also glued to the top sectional piece, with the hole matching up with the slot in the treat dispenser. 



Circuit Design 


Cat Feeder code summary:
In the Cat feeder code, there is an if else loop. The first loop is run when the red button(button1) is pressed. When going through the first loop the first servo opens for 2 milliseconds which releases about XX cup of food into the holding department then shuts. The second servo opens for several seconds allowing for all the food to be released into the bowl and shuts the servo gate back. A buzzer then goes off for one second alerting the cat there is food in the bowl. The if else loops have the process as the if loop, but with different time amount for the first servo to open. In this loop the gate is open for 5 milliseconds allowing for XX cups to be dropped. Both the if and if else loop repeat every12 hours to feed the cat. The else loop is for when neither button is pressed and keeps both servos in the closed position until one button is pressed. 

Treat code summary:  

The treat dispenser code is very similar to that of the food dispenser but only uses one servo. A speaker alerts the cat treats are about to drop then opens a servo for 2 milliseconds releasing a few treats then closes back and waits 2 hours before releasing more treats.  



Laser Code Summary:

The void loop in the laser code has a list of different servo positions that move each servo to a different location when the laser is on and holds a position for a certain amount of time before moving again. There is also a buzzer hooked up to the circuit that plays a different sound than the treat and food dispenser to alert the cat that it is time to play with the laser. 



# Discussion of Design

# Testing Description

# Discussion of Testing

# Testing Results



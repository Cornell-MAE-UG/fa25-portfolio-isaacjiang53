--- 
layout: project
title: Lantern Fly Eradication Unit
image: /assets/images/how-to-control-and-kill-spotted-lanternflies.jpg
technologies: [CAD, 3D Printing, Mechanical Assembly]
--- 
## Table of Contents
* [Client Pitch](#client-pitch)
* [Functional Prototype](#functional-prototype)

---

<a name="client-pitch"></a>
## Client Pitch

<p align="center">
  <b>Reducing Spotted Lanternfly Contamination During Mechanical Grape Harvest</b><br>
  <b>Lantern Fly Eradication Unit</b>
</p>

<p align="center">
  <b>Problem Statement</b>
</p>

During mechanical grape harvest, spotted lantern flies (SLF) remain on the vines and can be collected with the fruit, contaminating loads. Even minimal contamination is unacceptable: as few as 1–2 SLFs (~0.5–1 g each) can contaminate a 1000 g core sample, triggering shipment rejection. With deliveries occurring every 10 minutes at roughly 22 tons per load, a single rejected shipment results in substantial product loss, contributing to an estimated $14.3 million of damages across the Lake Erie and Finger Lakes regions in the first three years of infestation. Current solutions, such as chemical treatments or post-harvest separation, are either ineffective during active harvest, reduce yield, or are operationally inefficient. The challenge is therefore to deter SLF from vines before or during harvest, or to separate them from harvested material, without damaging grape quality or reducing yield.

---

<p align="center">
  <b>Why This Matters to the End-User</b>
</p>

Solving this problem would allow vineyards to avoid yield loss from post-harvest washing, reduce SLF contamination in harvested loads, and eliminate the need for additional chemical treatments during a critical harvest window. By preventing shipment rejections and harvest slowdowns, the solution would preserve grape quality, protect the winery’s reputation, and reduce significant economic losses.

---

<p align="center">
  <b>Proposed Directions</b>
</p>

**Smoke Machine Attached to Harvester** — Attach a smoke (or similar gas) delivery system to the front of the harvester to temporarily deter SLFs from the vines immediately before harvest. The goal is to use a non-lethal substance to clear the vines without relying on pesticides, potentially by rerouting harvester exhaust or using a small gas canister with forward-facing nozzles. We would prototype with a canister connected to two spray nozzles with an attachment mechanism to the harvester. Key risks/unknowns include whether SLFs will consistently fly away when exposed to smoke or exhaust, whether exposure could affect grape quality, and whether harvesters have sufficient space and power capacity to support the system. These factors would require rigorous prototyping and testing.

**Bristles as a Filter** — Install a system of brush bristles along the inner conveyor of the harvester to mechanically filter SLFs from grapes immediately after harvest. The bristles would comb over the harvested material, allowing grapes and juice to pass while removing SLFs from the harvest. We would prototype this by designing a brush and running it over grapes with flour or another substance on them. Key risks/unknowns include whether the bristles can reliably filter out SLFs without blocking or damaging grapes, and whether they are durable enough for long-term use. Effective implementation would require experimentation with bristle density and spacing.

---

<p align="center">
  <b>Our Questions</b>
</p>

* **Will SLF consistently disperse when exposed to smoke or exhaust?** — Determines whether or not we move forward with the gas or bristle solution.
* **Are there grape regulatory or flavor concerns regarding smoke or gas exposure?** — Clarifies feasibility of the smoke solution, ensuring regulations and flavor are not compromised.
* **Given a known deterrent, how long will it take for SLFs to return to the vines?** — Important for designing the potency, speed, and distribution of our solution.
* **What are the constraints to the modification of the harvester?** — Ensures feasibility of attaching a tank to the front of the harvester.
* **Is there space in the internal compartment of most grape harvesters to add enough bristles to be an effective filter?** — Determines whether we move forward with the bristle solution.

---

<p align="center">
  <b>Works Cited</b>
</p>

Bekelja, K., & Russo, J. *Spotted Lanternfly Discussion*. Zoom meeting recording, MAE 2250, Spring 2026.

Cornell University. “Spotted SLFs Could Cost NYS Grape Industry Millions.” *Cornell Chronicle*, January 2025.  
[https://news.cornell.edu/stories/2025/01/spotted-SLFs-could-cost-nys-grape-industry-millions](https://news.cornell.edu/stories/2025/01/spotted-SLFs-could-cost-nys-grape-industry-millions)





--- 
<a name="functional-prototype"></a>

### Functional Prototype

### Design Documentation

<p align="center">
  <b>Parts list:</b>
</p>

![Prototype parts list]({{ "/assets/images/prototype-parts-list.png" | relative_url }}){: class="project-image" style="max-width: 500px; display: block; margin: 0 auto; float: none;"}


<p align="center">
  <b>Fabrication of parts list:</b>
</p>

1. Cut the 12-inch by 12-inch wooden slab into three equal-width sections
2. Glued them together with wood glue and clamped them together at the four corners allowed it to rest for 24 hours.
3. Cut the tube down to roughly an 8-inch length, just to make sure there was not too much excess, making the mechanism difficult to use. 
4. Cut down the 24-inch length, wooden shaft into four 6-inch pieces to prevent motion.  
5. Cut one more wooden shaft to roughly 8 inches, and attach it to one gear using tape to use it as a handle. 
6. 3D printed gears with CAD from McMaster at the RPL, slightly edited CAD to add a larger hole in the center to decrease the rotational inertia of the mechanism. 
7. Drill a 27/64 inch drill bit into the wooden base and glue it down to ensure it is secure. Push two wooden shafts through the two 3D printed gears, but allow the gears to freely rotate. (This was supposed to be down with wooden screws, but our part didn’t come)
8. Attach the modified 8-inch tubing horizontally to one gear with tape. (This was supposed to be drilled down, but out clamp were a different dimension than intended)
9. Attach the 8-inch wooden shaft horizontally to the other gear with tape. This will be used for control of the rotational motion of the gears.
10. Drilled a ¼ inch drill bit on each side of the 8-inch wooden shaft. Glue down the two 6-inch wooden shafts into the two holes.


<p align="center">
  <b>Prototype Sketch</b>
</p>
![Functional Prototype Sketch]({{ "/assets/images/prototype-sketch.png" | relative_url }}){: class="project-image" style="max-width: 500px; display: block; margin: 0 auto; float: none;"}
<br>

<p align="center">
  <b>Assembly Instructions</b>
</p>

Assembly Instructions:
We need arrows in assembly for movement
  1. Fasten gears to wooden board with screws so gears so gears are toothed toigether
  2. Fasten tube for gas dispersion to one gear
  3. Fasten handle to the other gear to allow for controlled rotation
  4. Attach wooden shafts into wooden board to constrain the rotation of the gears


<p align="center">
  <b>Design vs. Drawing Discrepancies:</b>
</p>

1. One major discrepancy is our use of tape as a fastener. This is due to the fact that the clamps we ordered were much larger than we expected, and ended up not being useful for us. This mistake was due to a miscommunication of the tube’s radius and diameter. The team has worked this out, and we have decided to always communicate using diameter due to that being the engineering standard.
2. Another discrepancy is our lack of wood screws through the center of our gears. This is due to our screw order getting delayed. Although unfortunate, we can prevent this in the future by pushing forward our ordering deadlines on our schedule. 


<p align="center">
  <b>Design Testing & Outcomes</b>
</p>

<b>Test 1:<b> Rotation Smoothness
<b>Part tested:<b> Gears
<b>What it tests for:<b> Whether the handle-driven gears rotate the nozzle smoothly without binding, slipping, or excessive friction
<b>How we tested it:<b> Handle was rotated through desired range of motion while observing gear motion and checking for slip, jerky motion, or interference
<b>Test results:<b> Before applying constraints to the range of motion, we rotated the gears through 20 full rotations of 360 degrees. Throughout the test, there was no slippage or binding of the gear teeth.
<b>Conclusion for next iteration:<b> While we did not see any slipping/binding, we noted that the gears must be perfectly placed to achieve that. To provide slight room for error, if we re-fabricate the gears we will increase the gear tooth height by 5mm.

<b>Test 2:<b> Aiming Range
<b>Part tested:<b> Tube/Nozzle
<b>What it tests for:<b> Whether gear system allows tube/nozzle to rotate through motion required to cover desired volumetric space by the gas
<b>How we tested it:<b> Handle was turned from one extreme to the other and total angular rotation of the nozzle was measured
<b>Test results:<b> The gear system completed 10 full back-and-forth cycles. With the constraints we applied, we achieved a range of motion of 90 degrees. There were 0 instances of slipping or binding by the gear teeth during the test, and the nozzle was able to achieve the range of motion without exhibiting any significant stress.
<b>Conclusion for next iteration:<b> Our method of constraining the gears was effective. However, to make the design more robust, we will increase the diameter of the wooden cylinder constraints and use an aluminum base instead of wood.

<b>Test 3:<b> Repeated-Use Durability
<b>Part tested:<b> Screws/Gears/Wooden Board assembly
<b>What it tests for:<b> If mechanism maintains functionality after repeated use without loosening, slipping, or increasing friction
<b>How we tested it:<b> Handle was cycled at a minimum of 20 times while observing changes in motion smoothness, gear interface, and structural stability 
<b>Test results:<b> We cycled the gear through 20 full cycles at 20 RPM once the design was fully constructed, including constraints. The design held up with no clear signs of wear and tear.
<b>Conclusion for next iteration:<b> While out initial design holds up, it is primarily constructed out of cheap wood and tape, meaning that it will lose significant strength over time. For our final design, we will convert the constraint shafts and the base to aluminum. We will also use screws to keep the gears in place instead of a wooden sticks.

<b>Test 4:<b> Tube Stability
<b>Part tested:<b> Pipe Clamp
<b>What it tests for:<b> Whether gas tube remains securely attached and doesn’t interfere with nozzle rotation during operation
<b>How we tested it:v Rotate tube through full range of motion while observing clamps, checking for twisting, sagging, or resistance to rotation.
<b>Test results:<b> Unfortunately we were not able to directly test this due to our clamp ordering mishap. We however can confidently say that the clamps would hold up in the design, because we taped evetrything down with painter’s tape, which is significantly weaker. Through all of our previous rotations, roughly 20 full cycles at varying speeds, the tape held up just fine. This makes us feel confident to say our clamps would hold up fine, due to the strength of all portions of the clamps being orders of magnitude stronger than the tape. The tape also did not prevent rotation, which means the clamps would not as well due to it being in a similar position and not interfering with the gear teeth. 
<b>Conclusion for next iteration:<b> We are confident that once we have the correct clamps, they will be strong enough to hold our tube and handle down to demonstrate functionality of our design. 

<b>Test 5:<b> Structural Stability
<b>Part tested:<b> Wood Mounting Board
<b>What it tests for:<b> If wooden base remains rigid and maintains gear alignment during use
<b>How we tested it:<b> Handle was rotated repeatedly while checking for board flexing, shifting, or misalignment of the gears
<b>Test results:<b> We rotated the board through 10 full cycles at 20 RPM while the tube was held down to simulate stress from the harvester, applying a force on the mechanism of 10 Newtons. The wooden base exhibited no signs of flexing/bending, and the gears remained tightly connected with no slippage.
<b>Conclusion for next iteration:<b> The fact that the base did not flex or shift shows that our design does not have misalignment or place significant stress on the base. That being said, we still plan to use an aluminum base in the next iteration to ensure durability over more extended periods of time.



<p align="center">
  <b>Success Criteria</b>
</p>

Our main goal of this iteration is to ensure our gear rotation system for gas dispersion is effective and is durable enough to remain undamaged. A successful test should follow all of our outlined design criteria, and effectively demonstrate the ability to move our nozzle in a periodic type of motion to achieve better gas dispersion. 
  - After repeated and continuous testing for over 1 minute, where gears spin at least 90 degrees, all gears still spin as intended without interference or skipping
    - The gears would need to spin well for the entirety of the harvesting process for multiple harvests. This is important because we would want our solution to work long term for the farmers, so they don’t have to do continuous maintenance of our lanternfly gas dispersal system. An effective lanternfly prevention system is durable, so for our solution to work well we would need it to not only effectively deter lanternflies away from grapes, but also be durable enough to last a long time. 
  - After repeated and continuous testing for over 1 minute, where gears spin at least 90 degrees, all parts remain structurally stable/intact without breaking apart
    - The gears would need to spin well for the entirety of the harvesting process for multiple harvests. This is important because we would want our solution to work long term for the farmers, so they don’t have to do continuous maintenance of our lanternfly gas dispersal system. An effective lanternfly prevention system is durable, so for our solution to work well we would need it to not only effectively deter lanternflies away from grapes, but also be durable enough to last a long time. 
  - Gears that are constrained such that the gas dispersion tube only has an approximate 90-degree range of motion without experiencing significant resistance forces (friction, etc.)
    - Effective gas dispersion is crucial for our project to work, because it theoretically means the lanternflies would be better dispersed away from the grapes due to a lack of oxygen. 


<p align="center">
  <b>Prototype Testing Visuals</b>
</p>
Upon spinning the handle, the nozzle rotates with a 90 degrees free rotation due to the smooth rotation of the spur gears connected underneath.

![Prototype Test 1]({{ "/assets/images/prototype-test1.png" | relative_url }}){: class="project-image" style="max-width: 500px; display: block; margin: 0 auto; float: none;"}
![Prototype Test 2]({{ "/assets/images/prototype-test2.png" | relative_url }}){: class="project-image" style="max-width: 500px; display: block; margin: 0 auto; float: none;"}

[PDF of assignment:]({{"assets/MAE 2250_ODP_5_ Functional Prototype - Google Docs.pdf" | relative_url}})
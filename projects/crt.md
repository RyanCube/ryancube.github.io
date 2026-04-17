[← Back to Home](../)

# CRT Television Repair & Restoration

---

## Backstory
I found this on Facebook Marketplace listed as parts only. It's Bratz-themed CRT television from the early 2000s. These specialty kids' sets were made in limited quantities and are now rare and collectible. The housing was missing a few screws and the display was messed up, but I was drawn to the challenge.

I've been into CRT technology for a while now and I collect them for the retro gaming events I run. This deal was too good to pass up.

<div align="center">
  <img src="../images/bratz.jpg" style="width:75%; height:auto;">
  <p><em>Bratz CRT TV</em></p>
</div>

---

## Initial Assessment
It powered on, which was promising. But the picture had a black bar across the top, the whole image was tilted at an angle, and both sides of the screen were bowing inward. I ran it through a display testing tool to get a better read on what I was dealing with. It was clear this CRT needed to be taken apart.

<div style="display:flex; gap:10px; justify-content:center;">
  <div style="text-align:center;">
    <img src="../images/vertical_issue.jpg" style="width:100%; height:auto; object-fit:cover;">
    <p><em>CRT Powered On</em></p>
  </div>
  <div style="text-align:center;">
    <img src="../images/vertical_issue2.jpg" style="width:100%; height:auto; object-fit:cover;">
    <p><em>Display Geometry Issue</em></p>
  </div>
  <div style="text-align:center;">
    <img src="../images/hazard_zones.jpg" style="width:100%; height:auto; object-fit:cover;">
    <p><em>Display Borders Issue</em></p>
  </div>
</div>

---

## Teardown
Once I got inside, two things stood out immediately. A blown capacitor on the neckboard, which was almost certainly the cause of the black bar. And the epoxy that's supposed to hold the yoke in place had completely dried out and crumbled, letting the yoke shift and causing the tilt. The inside was also covered in dust, so I got that cleaned out before anything else.

<div style="display:flex; gap:10px; justify-content:center;">
  <div style="text-align:center;">
    <img src="../images/blown_capacitor.jpg" style="width:100%; height:auto; object-fit:cover;">
    <p><em>Faulty Capacitor</em></p>
  </div>
  <div style="text-align:center;">
    <img src="../images/vertical_issue2.jpg" style="width:100%; height:auto; object-fit:cover;">
    <p><em>Display Geometry Issue</em></p>
  </div>
  <div style="text-align:center;">
    <img src="../images/hazard_zones.jpg" style="width:100%; height:auto; object-fit:cover;">
    <p><em>Display Borders Issue</em></p>
  </div>
</div>

---

## Diagnosis
I tracked down a service manual for a similar CRT by cross-referencing the circuit board model. Going through the electrical schematic, I was able to pinpoint the specs of the blown capacitor and figure out what I needed to order.

<div align="center">
  <img src="../images/circuit_diagram.jpg" style="width:75%; height:auto;">
  <p><em>Circuit Board Schematic</em></p>
</div>

---

## The Fix
I ordered a replacement capacitor with a higher voltage rating to future-proof the repair. 
Before any work on the board, I properly discharged the CRT — these tubes store high 
voltage even after being powered off and unplugged, making this a critical safety step. 
I then desoldered the blown capacitor and soldered the new one in place.

For the tube tilt, I removed the metal brackets holding the tube assembly, and — wearing 
insulated rubber gloves — carefully rotated the tube back to level. Once aligned, I 
re-secured it with fresh epoxy.

<div align="center">
  <img src="../images/crt-brackets.jpg" style="width:75%; height:auto;">
  <p><em>Metal brackets removed to access and rotate the tube</em></p>
</div>

The two missing housing screws were sourced the old fashioned way — a trip to the 
hardware store and trial and error until I found the right fit.

---

## Reassembly & Testing
Powering it on after reassembly, the black bar was gone and the tilt was corrected. 
Progress. However, the bowing on the edges of the display was still prominent.

<div align="center">
  <img src="../images/crt-bowing.jpg" style="width:75%; height:auto;">
  <p><em>Edge bowing still visible after initial reassembly</em></p>
</div>

After further research, I found how to access the service menu — a hidden diagnostic 
menu built into the TV — and adjusted the pin amplifier setting, which controls the 
shape of the display geometry, correcting the bowing entirely.

<div align="center">
  <img src="../images/crt-fixed.jpg" style="width:75%; height:auto;">
  <p><em>Display after pin amplifier adjustment</em></p>
</div>

---

## Final Result
A fully restored, fully functional Bratz CRT. The display looks great and all three 
issues — the black bar, the tilt, and the bowing — have been resolved. Beyond the 
technical outcome, this was a valuable hands-on lesson in electronics troubleshooting, 
CRT safety, and working without a perfect roadmap.

<div align="center">
  <img src="../images/crt-final.jpg" style="width:75%; height:auto;">
  <p><em>Fully restored and running</em></p>
</div>

---
[← Back to Home](../)

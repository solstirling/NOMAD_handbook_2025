# NOMAD's Pocketing Guide

Pocketing is the process of removing unnecessary material from metal plates or tubes to reduce weight while maintaining structural integrity. It’s a powerful tool in mechanical design—especially in FRC—where weight constraints, performance, and accessibility matter.

This guide is intended to help new CAD students understand **when and how to pocket parts** effectively on a robot.

---

## When Should You Pocket a Part?

Pocketing decisions depend on a combination of the following factors:

- **Total plate area** – Larger plates offer more opportunity for meaningful weight savings.
- **Thickness** – Thicker materials (like 1/4" or 1/8" aluminum) are more worth pocketing than thinner ones.
- **Rib structure** – Can you leave behind enough ribs to keep the part rigid?
- **Estimated weight savings** – If you can save .25lbs per part, it adds up fast.
- **Application** – Is the part load-bearing or aesthetic? Critical structure or non-essential?

In 2025, **our team pocketed almost every plate on the robot**, except for polycarbonate intake plates. The decision often came down to how much weight we expected to save, and whether it was worth the minimal additional CAM/CNC time—especially with faster CNC workflows.

---

## Pocketing Reference Table

| Component                     | Pocket? (Y/N) | Reason                                                                |
|-------------------------------|---------------|-----------------------------------------------------------------------|
| Drivetrain boxtube            | **No**        | Weight down low is good for CG.                                       |           
| Bellypan / Brainpan           | **Yes**       | Large flat area, makes wire routing easier.                           |
| Low-down plates (elev frame)  | **Maybe**     | Could lower CG, but not always worth the effort.                      |
| Top elev plates               | **Yes**       | Important to save weight higher up; keep MOI and CG low.              |
| Elevator boxtubes             | **Maybe**     | Pocketing removes mounting locations; easier to use thinner box tube. |
| UTB intake plates             | **Yes**       | Partial depth pockets with thick ribs save weight effectively.        |
| End effector plates           | **Yes**       | Same reasons: save weight, reduce inertia (MOI), keep CG low.         |
| Polycarb Plates               | **No**        | Already lightweight; better to leave unpocketed for strength.         |

> ✅ Yes = Recommended to pocket  
> ❌ No = Do not pocket  
> 🤔 Maybe = Case-dependent

---

## Tips before starting

- **Finish the design before pocketing.** In Onshape, updating features after pocketing can create messy rebuilds. Finalize geometry and check for interferences first. If you are in a rush to get a part machined, be sure to double check the most important aspects of the plate (belt C2Cs, game piece compression, hole sizes, etc.)
- **Holes and edges first.** Always start with a consistent rib thickness around bolt holes and plate perimeter to maintain strength and aesthetics.
- **Use depth control.** Partial-depth pockets are faster to machine and offer more strength and material under load paths.
- **Test different methods.** If unsure, try different rib patterns and evaluate them visually and with mass properties.

---

## The Process

To be consistent as a team, we will always use the [lighten FS](https://cad.onshape.com/documents/573f7d70e4b0fddafb52148c/v/159edf03bd5c40a22bbff33c/e/5eccf6d369b0312a728d77d3) because it offers more control with holes and thicknesses.

> "biggest thing that makes pocketing look good is not the pocketing its the plate outer contour and how many holes you add..." 
>
> *Jonah*

Alot of people struggle with pocketing, either with it's aesthetics, or it's structure. In order to uphold both of these properties, the plate itself needs to be designed well. As said in the quote above, good pocketing stems from the outer countour (the edge of the plate), and the amount of holes. Here are two plates with the same function but different perimeters and hole counts:




---
## Conclusion 

Pocketing is one of the most efficient ways to reduce robot weight without compromising performance—if done thoughtfully. Use this guide to evaluate your designs and make pocketing decisions based on geometry, function, and estimated weight savings.

# FRC CAD Pocketing Guide

Pocketing is the process of removing unnecessary material from metal plates or tubes to reduce weight while maintaining structural integrity. It’s a powerful tool in mechanical design—especially in FRC—where weight constraints, performance, and accessibility matter.

This guide is intended to help new CAD students understand **when and how to pocket parts** effectively on a robot.

---

## When Should You Pocket a Part?

Pocketing decisions depend on a combination of the following factors:

- **Total plate area** – Larger plates offer more opportunity for meaningful weight savings.
- **Thickness** – Thicker materials (like 1/4" or 1/8" aluminum) are more worth pocketing than thinner ones.
- **Rib structure** – Can you leave behind enough ribs to keep the part rigid?
- **Estimated weight savings** – If you can save 50–150g per part, it adds up fast.
- **Application** – Is the part load-bearing or aesthetic? Critical structure or non-essential?

In practice, **our team pocketed almost every plate on the robot**, except for polycarbonate intake plates. The decision often came down to how much weight we expected to save, and whether it was worth the minimal additional CAM/CNC time—especially with faster CNC workflows.

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

## Practical Tips

- **Finish the design before pocketing.** In Onshape, updating features after pocketing can create messy rebuilds. Finalize geometry and mating first.
- **Think ribs first.** Leave ribs around bolt holes and edges to maintain strength.
- **Use depth control.** Partial-depth pockets are easier to machine and preserve more material under load paths.
- **Test pocketing on clones.** If unsure, make a copy of your part and test different pocketing options visually and with mass properties.

---

## Summary

Pocketing is one of the most efficient ways to reduce robot weight without compromising performance—if done thoughtfully. Use this guide to evaluate your designs and make pocketing decisions based on geometry, function, and estimated weight savings.




























# __Pocketing__

Pocketing is removing any uneccesary material from a plate, tube, or panel, and leaves the __ribs__ , which keep the essential structure strong and rigid. Whether you are trying to make the year's weight limit, or lighten up a mechanism, pocketing is a great solution. 

Before actually going over the pocketing process itself, there are a few important things to know:

## Before you pocket:

1. __Finish the design.__ Especially in Onshape, where you have multiple people working with you, pocketing too early can turn into messy workflow. When designing plates, so many aspects change in order to avoid interferences and clipping, the pocketing will just break and give you a hard time, so always finish the design first, and then pocket.

2. __Do you need to pocket it?__ In some situations, like over the bumper intakes, it may be better to switch to a lighter, flexible material such as polycarb instead of pocketed metal. In other situations, such as structural gussets and plates, it may be better to leave it unpocketed to keep all of the structure you can. View [this table](pocketingtable.md) to see which cases you should or shouldn't pocket in.
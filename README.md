# PCB-Day-2-Gerber-Viewer-and-3D-Inspection

**Software:** KiCad 9.0  
**Project:** LED Circuit PCB  
**Level:** Beginner  
**Cost:** Free — no physical PCB ordered

## 1. Objective

Learn how to inspect PCB manufacturing layers using Gerber Viewer, understand drill files, and visualize the PCB using KiCad's 3D Viewer.

## 2. Gerber Viewer

Opened Gerber Viewer in KiCad 9.0 and loaded the Gerber files generated on Day 1.

Files used:
- `Day1-F_Cu.gbr`
- `Day1-F_Mask.gbr`
- `Day1-F_Silkscreen.gbr`
- `Day1-Edge_Cuts.gbr`

**Note:** `Day1-job.gbrjob` contains Gerber job information and should not be loaded as a Gerber plot file.

## 3. Understanding PCB Layers

- **F.Cu (Front Copper):** Contains copper pads and tracks that electrically connect components.
- **F.Mask (Front Solder Mask):** Defines openings in the protective solder mask.
- **F.Silkscreen (Front Silkscreen):** Displays component labels and markings.
- **Edge.Cuts:** Defines the physical shape and boundary of the PCB.

## 4. Drill File Inspection

Loaded the following drill files:

- `Day1-PTH.drl` — Plated through-hole drill locations.
- `Day1-NPTH.drl` — Non-plated through-hole drill locations.

The NPTH view appeared empty, which may be normal if the design does not contain non-plated holes.

## 5. Gerber Layer Alignment

Loaded the Gerber layers into the same viewer and inspected the component pads, labels, and rectangular board outline.

Important checks:
- Verify copper tracks connect the intended pads.
- Check that drill locations align with component holes.
- Confirm that the `Edge.Cuts` outline is closed.
- Ensure the footprints match the actual components.

## 6. 3D PCB Inspection

Opened the PCB in KiCad's 3D Viewer and inspected:

- PCB shape and thickness
- Resistor placement
- LED placement
- Two-pin battery connector
- Component labels and outlines

The 3D Viewer helps verify component placement and the physical appearance of the board. It does not guarantee electrical correctness.

## 7. Day 2 Results

- [x] Opened Gerber Viewer.
- [x] Loaded the front copper layer.
- [x] Loaded the front solder mask layer.
- [x] Loaded the front silkscreen layer.
- [x] Loaded the Edge.Cuts layer.
- [x] Opened PTH and NPTH drill files.
- [x] Inspected the Gerber layers together.
- [x] Opened the PCB in 3D Viewer.
- [ ] Recheck copper routing in PCB Editor.
- [ ] Verify LED polarity and battery connector footprint.
- [ ] Review any remaining DRC warnings.

## 8. Important Learning Notes

- Gerber files describe PCB manufacturing layers.
- Drill files describe hole locations and types.
- `Edge.Cuts` defines the board boundary.
- A clean DRC result and a good 3D view do not guarantee electrical correctness.
- This project is for learning; no physical PCB has been ordered.

## 9. Day 3 Plan

1. Improve component placement.
2. Make PCB tracks neat and organized.
3. Improve component label positioning.
4. Verify track widths and clearances.
5. Check LED polarity and connector footprints.
6. Run DRC again.

## 10. Free Learning Resources

- [KiCad Official Website](https://www.kicad.org/)
- [KiCad Getting Started Guide](https://docs.kicad.org/9.0/en/getting_started_in_kicad/getting_started_in_kicad.html)
- [KiCad Learning Resources](https://www.kicad.org/help/learning-resources/)

## Screenshots

Add your Gerber Viewer and 3D Viewer screenshots to your GitHub repository to document your learning progress.

**Day 2 Summary:** Learned to inspect Gerber layers, understand drill files, check board outlines, and visualize a PCB in 3D using KiCad 9.0.

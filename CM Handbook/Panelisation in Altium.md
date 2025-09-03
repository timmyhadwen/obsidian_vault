21. Open Altium PCB, create Route Tool Path layer
	1. Mech 11 - Route Tool Path (Green colour)
22. Follow Altium tutorial on creating route toolpath using 2.4mm tool
![[Pasted image 20250901101052.png]]
23. Create a PCB file named 'Intelli Design ID'x'Number of Boards on Panel'. Eg: 38810x5.PCBDoc
24. Insert the base board using Place -> Embedded Board Array/Panelise
25. Draw the panel outline, so that the tooling strip is at least 10mm on each side of the board.
	1. TODO: Insert minimum panel dimensions here
26. Draw the tooling strip break away tabs, using the same drill size as the PCB tabs, so that the board can be snapped apart without tools.
	1. Think about the order strips are broken away, and if there is multiple boards on the panel think about the quickest and easiest way for them to be separated
27. Add the Route Tool Path layer on the panel (Mech 11, Green) to match step 1.1
28. Insert PanelID Box (top and bottom) on bottom tooling strip (Copy these from an existing panel)
29. Add Square fiducial marks in the middle of the tooling strips in the bottom left, bottom right and top right corners (top and bottom).  (Copy these from an existing panel) Add silkscreen showing the X and Y distance from the origin point, as well as the fiducial mark size (normally 2mm)
![[Pasted image 20250901125644.png]]
30. Add a label onto the top tooling strip (top side and bottom side) with the panel dimensions
![[Pasted image 20250901115536.png]]
31. Add a label onto the middle of the top tooling strip with panel spacing (top and bottom side)
![[Pasted image 20250901115815.png]]
32. If the board does not have a straight corner a the origin (bottom left of each board), add silkscreen lines showing the origin point. (TODO: Add example image here)
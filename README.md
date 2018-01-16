# Improvements to a Reprappro Ormerod 2 Printer.

Modifications made by a relatively inexperienced 3D printer user.

# Part 437 - Z Stop

The original part design from RepRapPro had a few flaws. It had a goose-neck to a screw, this was a weak point, and where the original part shipped to me from RepRapPro failed. 

The other weak point is that the original would snap fit around the Z bearing rod. This design led to it being designed to flex across a thin strip. This failed twice on replacements. 

My modifications to this are:
* Replace the goose neck with a thicker section. This should not interfere with other parts.
* replace the "snap fit" with a larger cylinder, and a screw/clamp based system.

This is as yet untested - once a first print has been made, fixes can be attempted.
It needs also an M3 screw + nut.

Once printed and cleaned up, push the insert into the cavity inside the sphere, then add an m3 nut in the catcher, and screw an m3 screw loosely into the nut. Screw the sides into place on the Y-axis extrusion, then push the Z-axis bearing into the part. Tighten the m3 screw to firmly hold the bearing part.

# Drag Chain

The other parts form a drag chain, with an additional link designed to hang on the Ormerod. This was to prevent the cables from the X-axis drooping far enough to foul the bed movement - a cause of a failed print.

* drag_chain_with_cut.stl -> A segment of drag chain, cut open to push cable into. Print multiples of these.
* drag_chain_hanger_link.stl -> A special segment of drag chain that mates with one of the spare extruder bays on the Ormerod.

Watching for the scaling, print these, snap them together, wrap around the X-axis cabling facing away from the Z-Axis, and then hang the chain on the X-Axis rib.

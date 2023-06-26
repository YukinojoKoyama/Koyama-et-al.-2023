ASM5

●Grain size●
ASM5_PZ_Grainsize.ctf

To exclude the influence of not well-indexed domain, an area
[0*max(ebsd.x) 0*max(ebsd.y) 0.9*max(ebsd.x) 0.2*max(ebsd.y)] (line 52 in both GrainsizeCalculation for Crossetal.2017)
was used for grain size estimation.
Grain size and grain boundary estimation were performed using GrainsizeCalculation for Crossetal.2017.

●Fabric pattern and OA●
ASM5_PZ_for_OA.ctf

To avoid poorly indexed regions, the following three regions were used.
[0*max(ebsd.x) 0*max(ebsd.y) 0.9*max(ebsd.x) 0.2*max(ebsd.y)]
[0*max(ebsd.x) 0.3*max(ebsd.y) 1*max(ebsd.x) 0.2*max(ebsd.y)]
[0*max(ebsd.x) 0.55*max(ebsd.y) 1*max(ebsd.x) 0.2*max(ebsd.y)] (line 52 in both GrainsizeCalculation for Crossetal.2017)
All regions were applied to GrainsizeCalculation for Crossetal.2017, and Rexnonborder was plotted on the Schmidt net using PlotforOA.

The plotted fabric pattern is rotated -15° around the y-axis (or z-axis on the program) and then 15° around the x-axis so that the small circle is on the z-axis (or y-axis on the program).

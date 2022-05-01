# FlowPastHemiSphereDNS

1. A set of 500 files, each for one time step with an interval Δt=0.002 (i.e. total time T=499Δt1) with the following structure (11 columns):
MST time
x y z ux uy uz ax ay az p PartID

where PartID is the particle number.

2. Velocity, acceleration, velocity derivatives and static pressure fields for each hundredth instant of time, i.e. for 1, 101, 201, 301 and 501, with the following structure (19 columns):
MSTfield
x y z ux uy uz ax ay az dx dx dx dy dz duydx duydy duydz duzdx duzdy duzdz p

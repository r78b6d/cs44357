java c
Quantitative Physiology I / Molecular and Cellular Systems; BMEN E4001x
HW2: Kinetics and Diffusion
Due Oct 09, 2024, 11:00PM (US Eastern Time)
1) Enzyme inhibition (10 points)
A key point of regulation of the glycolytic reaction is in conversion of fructose-6-P to fructose- 1,6-P by the enzyme phosphofructokinase (PFK).  ATP is a downstream product of this reaction, but also acts to inhibit PFK, slowing down generation of ATP in a negative feedback loop.

●   This question only focuses on the inhibitory site on PFK for ATP. While there is an ATP-  binding site that is essential for this reaction to take place, ignore this interaction here. The components that are important to this question are marked in red.
●   ATP acts as an allosteric, uncompetitive inhibitor of PFK.
●   Vmax for the reaction (generating F16P from F6P at saturating amounts of substrate and in the absence of inhibitor) is 2.3 μM/s. Assume PFK is present at a concentration of 10 nM
●   The standard concentrations ofF6P and ATP prior to perturbation of the system are:
[F6P]normal = 0.25 mM;          [ATP]normal  = 0.20mM
●   Binding constants ofF6P and ATP to PFK are:
KM,F6P= 0.2 mM;                   KI,ATP  = 0.1 mM
●   The concentration of ATP inside the cell is going to be a balance between ATP production through this route and downstream usage. Following a perturbation, the concentration of
ATP will approach some steady-state value that is dependent on the other parameters of the system. This could be a very complicated equation.
As a simplifying assumption here, assume the steady-state concentration of ATP is proportional to the reaction rate. Thus:
[ATP]= (330*seconds) * reaction rate.


Explore the ATP-PFK feedback loop:
1.1)



Unregulated reaction. Look at how the system responds to a change in F6P level; this   question focuses on changes in concentration or rate of generation for the components in red.  If the concentration ofF6P suddenly increases by 25% to 0.3125 mM, what is the initial change (in percent) of reaction rate, before the concentration of ATP has time to adjust? That is, assume the concentration of ATP remains at the standard 0.20 mM.

1.2)
Feedback mechanism. As a separate perturbation, assume a bolus of ATP is suddenly introduced into the cell, instantaneously bringing the level of ATP to 0.3 mM. Compared to the standard conditions (F6P at 0.25 mM, ATP at 0.20 mM), what is the change (in percent) of reaction rate?
1.3)

Regulated reaction. Now, put the two processes together. Starting with the perturbed system of part 1.1 (in which F6P increases to 0.3125 mM), allow the ATP concentration to now change and provide negative feedback. Compare the steady-state reaction rate of this feedback system with the unregulated reaction rate of part 1.1; how much does feedback offset the effects of an increase in F6P?Note: this last section involves finding the root of a rather complicated expression. Feel free to use a numerical approach, such as a graphic calculator, MATLAB, or the Solver tool in Excel to find your solution.




2) Diffusion-based transport (10 points)
Cells are able to detect chemical gradients. For example, cells can migrate towards a site of inflammation, guided by an increasing concentration of a molecule secreted from that site.
One system for studying this effect consists of three parallel, microscale channels, separated by regions of a polymer material. The cross section of this system, looking along the channels, is shown above.
The two outer channels are connected to external pumps that continually replenish these regions, thus maintaining the concentration of a bioactive chemical in these channels. Cells are placed on the bottom of the center channel.  The two polymer blocks serve to stop the bulk flow of fluid between the channels. For this problem, assume:


●   The concentration of the compound being studied, denoted as M, is held at 1 mM in the left channel and at 0 mM in the right channel, as indicated in the figure above.
●   The three channels are filled with media that can be treated as water. The properties of the polymer regions will be defined in each section below.
●   The diffusion coefficient of M in the middle channel, Dm, is 0.5 µm2/msec. The diffusion coefficient of M in the polymer regions, Dp, is 0.3 µm2/msec. The partition coefficient of M in the polym代 写Quantitative Physiology I / Molecular and Cellular Systems; BMEN E4001x HW2: Kinetics and DiffusionMatlab
代做程序编程语言er regions will be defined separately for each of the following sections.
●   The two polymer regions and the middle channel are considered non-stirred slabs.
●   Diffusion from left to right can be considered a 1-D, Cartesian problem. Consider the left edge of the left-most region of polymer as the origin, x = 0.
A) Consider a system in which the partition coefficient of M in the polymer regions is 1. Determine:
2.1    The concentration of M as a function of position, x, across the microfluidic channel. This can be a graph or a set of relations covering the range of x.
2.2    The change in concentration per distance in the center channel. That is, what is the concentration gradient that the cells see?
2.3    The flux of M across this system (left to right) per mm of channel length (measured perpendicular to the cross section, into the page).
2.4    The time it takes for a molecule of M to diffuse across the middle channel.
Use √〈x(t)2〉as a measure of how far the average particle diffuses in time t.
B)  You observe cell migration in response to this gradient, but want to carry it out again with a gradient that is half as steep as before. Moreover, the concentration of M at the left side of   the middle channel should be the same as in section A of this question. There’s not enough  time to change the geometry of the channel, but the partition coefficient of M in each polymer region can be changed, even specifying different coefficients for each of the two regions.
2.5    What should the partition coefficient of M in each polymer region (βp,1 and βp,2) be to provide this new profile?
For your own consideration: graph the concentration of M as a function ofposition.


3) Milk (10 points)
Milk is homogenized to simplify processing/distribution and provide a more uniform. product to   the consumer.  Prior to homogenization, fat will separate out into a rich layer at the top of the milk under normal storage conditions for a short time (overnight). In the homogenization process, fat globules, which start off as roughly 5-μm diameter spheres, are broken into smaller pieces, such as 1-μm diameter spheres. This makes the commercial product, which in the grocery appears to not separate.
Consider the separation process as sedimentation in a 1 g gravitational field. In this exercise, we will compare the behavior. of the fat globules to casein, a family of proteins in milk found as either individual molecules of 1.8-nm diameter or as micellar aggregates of 100-nm diameter. Assume that these protein structures can all be considered spherical objects
Assume that milk is mainly water, so density = 1 g/cm3.  Milk fat has a density of 0.9 g/cm3, and thus floats. Assume that casein proteins are of density 1.3 g/cm3 ; these will sink.
Useful constants:
kb = 1.38 x 10-23 J/K                               Earth’s gravitational field = g = 9.8 m/sec2
T = 300K for this problem.
for water: density PW=1 g/cm3, viscosity = ηW  = 1 x 10-2 poise;1 poise = 1 dyne*sec/cm2
For the four entities of 5 μm fat globules, 1 μm fat globules, 100 nm casein aggregates, and 1.8 nm casein proteins:
3.1)  Steady state sedimentation. First, look at the long-term (equilibrium) separation of each of the entities from mike. That is, calculate a characteristic sedimentation height/depth, z*, in earth’s normal gravitational field for the two sizes of fat globules and two forms of protein.
3.2)  Does it separate? Compared to an average milk carton height of 25 cm, do the numbers in section 3.1 explain what you observe for milk storage? That is, which of these four entities would separate out from milk given enough time? Assume that if |z*| > 25 cm, there is no separation for that entity and if |z*| < 25 cm, that structure separates out from solution.
3.3)  Time matters. Another factor affecting separation is how long a system would take to
reach equilibrium (no net flux). As a measure of this timescale, calculate the drift velocity for the four entities, and calculate how long it would take each to traverse the height of a milk carton (25 cm), at that velocity; don’t take diffusion into consideration here. Does this help explain the differences in observed separation behavior. of fat globules and casein proteins? Compare an observation period of one month against the time it takes to traverse the 25 cm carton for each entity.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

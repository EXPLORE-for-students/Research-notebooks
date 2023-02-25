# Sergiy Feb 7 - 14 Journal
## What I have completed during the week:
- Update the code to have the correct units
- Read and take notes on “Can Neutron stars constrain Dark Matter?”

## Section 1:
- In natural units we state that c and G are both equal to 1.
- I wasn’t sure if mass was also kept as m or if it was always measured as 1/E. The quick way to convert from m to 1/E is to multiply by (1/0.197E-15).

![image](https://user-images.githubusercontent.com/97152082/221380418-32de422a-f21b-442a-9138-cb756c14640d.png)

For some reason when rho0 was converted into natural units, there would be no result in the density-radius graph.

![WhatsApp Image 2023-02-25 at 4 29 07 PM](https://user-images.githubusercontent.com/97152082/221380444-2e05184e-4f71-4bae-9ae6-e489cf0c13df.jpeg)

Adrien had similar issues but changing rho0 didn’t solve the issue. He also gave a recommendation of converting to natural units using variables instead of doing it manually.

## Section 2:
“All currently existing evidence in favor of dark matter (as, for example, WMAP [9]) is of gravitational origin.” - We do know that dark matter does not interact with the electromagnetic force, but what about the other forces?

### Notes:
- tight constraints on the spin-independent and spin-dependent cross sections of WIMPs scattering off nuclei targets at the level of 
![image](https://user-images.githubusercontent.com/97152082/221380480-94822804-32a0-4f53-b9dc-1b38bc8e3e39.png)
- existence of dark matter with excited states, in which case WIMPs can interact also inelastically
- high baryonic density in compact stars increases the probability of WIMP scattering within the star and eventually the gravitational trapping. This is crucial in view of the tiny value of σN
- Secondly, at the late stages of their evolution, neutron stars can be rather cold objects due to lack of possible burning or heating mechanisms, and therefore heating by annihilation of the dark matter could produce an observable effect
- They are easier to observe due to their larger surface area
- For a neutron star, this requires the cross section to satisfy σN & 10−45cm2 , while for a solar mass white dwarf of radius 5000 km one should have σN & 10−39cm2 . As a result, neutron stars can probe much smaller values of the WIMP-to-nucleon cross section. 
- Focus of paper: constraints on the dark matter parameters that may arise from the neutron star cooling
- Conclusions: although a considerable number of WIMPs is accumulated by the progenitor during the evolution preceeding the formation of a neutron star, the effect of this accumulation is observable only in cases where the annihilation cross section is extremely small
- We argued that observations of neutron stars with low (of order 10 5 K or lower) surface temperature will put constraints on a large set of dark matter candidates. Due to their high density, the neutron stars accrete the dark matter at a significant rate even when the WIMP-to-nucleon cross section (elastic or inelastic) is as low as 10−45cm2 , which is two orders of magnitude lower than the current experimental limit. <- this paper was written in 2010, now we have reached the limit. It’s based on the recoil of the nucleus. 

## Questions:
- Is G=1? No, it’s in GeV or m^2 as long as it cancels out.
- In natural units, is length always m or is it 1/E? In particle physics, it’s convention to use m (even for length) despite that in other conventions it’s 1/E. Usually we convert back from natural units to non-natural units at the end.
- Why was there an issue with the graph?

## What needs to be done:
- fix code
- read dark matter paper
- accretion rates using equation 1 F (accretion rate of dark matter) R=radius of neutron star, f=1, neglect exponent i.e e=0 (it has rho, m, M, R)
- Can we get equation 2? I.e. make sure G’s units cancel
GM/R in SI has units thus to cancel it, you need to add some c’s to make sure it cancels out.
- F is a function of rho (read part IV), make it as a function of r using equations 11 12 13. Plot rho and F
- Next meeting is in two weeks

---
layout: about
title: about
permalink: /
subtitle: PhD student at Tel-Aviv University
profile:
  align: center
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>taya at govreensegal.com</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
I'm Taya, I work on various high-energy astrophysics transients, using analytical methods alongside numerical simulations. I'm specifically interested in problems in which the hydrodynamics of shock waves is coupled to emission processes, and get very excited when I can test my theory against observations. You can read more about my research below, or have a look at my [papers](https://ui.adsabs.harvard.edu/search/fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=(database%3Aastronomy%20OR%20database%3Aphysics)&q=author%3A%22Govreen-Segal%22&sort=date%20desc%2C%20bibcode%20desc&p_=0). 

I'm currently in a direct PhD program at Tel Aviv University, advised by Ehud Nakar. Before that, I did my undergraduate studies in physics and mathematics at Tel-Aviv University. 

___

# Research
A short summary of my work on various topics

## What I'm thinking about now
I'm currently thinking about various aspects of supernovae interacting with thick circumstellar media. A SN exploding into a dense wind will form a forward shock propagating into the wind, and a reverse shock propagating into the ejecta. Initially, the photon diffusion time through the wind may be longer than the dynamical time, keeping the photons trapped in a radiation-mediated shock, until the two times become comparable, and the photons can escape. This stage is known as a shock breakout. I'm interested in what happens after it, once the shocks become collisionless. My main question is, what will we observe, and what does that tell us about the local upstream. What I like about this problem is that it has a lot of different physics. Both shocks heat the matter to x-ray temperatures, but these x-rays can be reprocessed by photoabsorption in various parts of the system. The reprocessed X-rays will contribute to cooling via inverse Compton, while the cooling will affect the temperature and density in the interaction region, and can significantly change the reprocessing. In addition, the photons diffusing through the upstream can be photoabsorbed or can photoionize their way out. Perhaps, they will suffer Compton degradation, or maybe they'll heat parts of the upstream, and will not? Additional complications arise when one considers non-thermal pressure sources such as magnetic fields and cosmic rays, the electron-ion coupling in the shocks, and the effect a clumpy wind may have on the cooling efficiency. 

I'm working on several components of this vast problem, mainly analytically, and am very glad to have the magnificent and overconstrained observations of SN2023ixf to test my models against. 

___
## The Structure and Evolution of Jetted Blast Waves
This story has two beginnings. From a GRB perspective, measuring the jet geometry, and specifically, the jet core angle, has been a long-standing problem, due to its role in constraining the jet energy and GRB event rate. These, in turn, play a role in understanding the launching mechanism and the role of GRB progenitors in shaping their surroundings. The thousands of on-axis jets observed to date demonstrate how difficult it is to measure this with on-axis observations. Off-axis jets, have the advantage that their light-curve 
___

## Shocks in Expanding Media
![Illustration of the phase space for shocks in expanding media](assets/img/sketch4with arows.png)
What happens when you drive a shock into already expanding media? Will the shock eventually die out, or propagate out to infinity? This question is perhaps relevant if, following a stellar explosion, such as a supernova or neutron star merger, a central engine drives another shock into the previously launched ejecta. But even if it isn't, it still makes for an interesting problem in hydrodynamics. 
It turns out that having two velocity scales, the shock velocity and the local upstream velocity, generally means that the solution will not be self-similar, making it very difficult to solve analytically. The exception is the special case in which the velocity ratio remains constant. Such a solution only exists for steep enough density profiles and is repulsive. Shocks starting infinitely close to it will move away from this solution. It separates families of shock solutions in which the velocity ratio grows, and ones in which it decreases.

Right before submitting the paper on the Newtonian version of this problem, I had an anzats for the (non-self-similar) shock evolution. It fits the numerical simulation data perfectly, and is presented in the [paper](https://ui.adsabs.harvard.edu/abs/2021ApJ...907..113G/abstract). Why shocks evolve in this manner, and whether the flow can be fully solved for these cases, remains a mystery, which I hope someone will solve one day. 

The explanation above is for the Newtonian problem, but this line of argument is easily generalized also for relativistic shocks in expanding media [in this paper](https://ui.adsabs.harvard.edu/abs/2024MNRAS.528..313G/abstract), with the added benefit that while the spherical geometry is assumed in the solution, it should be a good approximation also for jets, since regardless of the geometry, an ultra-relativistic shock is only causally connected over a limited angular scale. 

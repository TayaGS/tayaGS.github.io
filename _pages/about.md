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

# Research

## What I'm thinking about now
I'm currently thinking about various aspects of supernovae interacting with thick circumstellar media. 

## Off-axis GRBs
jet structure and evolution, geomtry of 170817

## Shocks in expanding media - 
What happens when you drive a shock into already expanding media? Will the shock eventually die out, or propagate out to infinity? This question is perhaps relevant if following a stellar explosion, such as a supernova or neutron star merger, a central engine drives another shock into the previous ejecta. But even if it isn't, it still makes for a lovely problem in hydrodynamics. 
It turns out that having two velocity scales, the shock velocity and the local upstream velocity, generally means that the solution will not be self similar, except for in the special case in which the velocity ratio remains constant. This self-similar solution only exists for steep enough density profiles, and is repulsive. Shocks starting infinitely close to it will move away from this solution, and, in fact, it separates families of shock solutions in which the velocity ratio grows, and ones in which it decreases. 

Right before submitting the paper, I had an anzats for the (non self-similar) shock evolution. It fits the simulation data perfectly, and is presented in the [paper](https://ui.adsabs.harvard.edu/abs/2021ApJ...907..113G/abstract). Why this is how the shocks evolve, and whether the flow properties can be fully solved, remains a mystery, which I hope someone will solve one day. 

The explanation above is for the Newtonian problem, but this line of argument is easily generalized also for [relativistic shocks in expanding media](https://ui.adsabs.harvard.edu/abs/2024MNRAS.528..313G/abstract), with the added benefit that while the spherical geometry is assumed in the solution, it should be a good approximation also for jets, since regardless of the geometry, an ultra-relativistic shock is only causally connected over a limited angular scale. 

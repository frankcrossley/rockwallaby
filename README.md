# Exploratory Lab 2: Interactive Species Distribution Models for the Black-Flanked Rock Wallaby

<h2>Map Link</h2>

This map can be found at:

https://frankcrossley.github.io/rockwallaby/Wallabies.html?fbclid=IwAR0km33vCAlhls6aMJz0UMCjPznpSMLsJB8Ram-wI7NacKyYfofKUOKO98s#BlackWallab

<h2>Screenhot</h2> 

![alt text](https://raw.githubusercontent.com/frankcrossley/rockwallaby/main/Lab2_Screenshot.png "Screenshot of my interactive species distribution modelling maps")
  
<h2>Reflective Analysis</h2>

Prior to beginning this lab, I had been working with species distribution data in two courses – one focussing on GIS and modeling, with the later being a biogeography course. During my research for these courses, two sources stuck out in particular. Firstly E-Flora/E-Fauna BC, which provides an account for all known species in British Columbia, both about their characteristics and their range. Secondly, the Atlas of Living Australia provides both characteristics and known occurrences of all known species in Australia. While both of these sources are unlikely to be used in tandem, due to their significant geographic differences, they both provided me inspiration through their interactive approach to ecological education. It was this idea that I hoped to capture in this lab, yet I also wanted to provide a new element, to differ my map from the others. For this I chose to map how the biogeographic range for a given species is forecast to change over a range of climate warming scenarios. I believe this would be an invaluable tool when teaching about the impacts of climate change, particularly to younger generations, as it quite literally shows how their favourite species are likely to be impacted, hence (hopefully) stressing the importance of taking emissions seriously.

For this lab, I chose to start off with one species – the Black-Flanked Rock Wallaby – and then expand into further species if the coding process went smoothly. The end product would ideally end up encompassing every known species in the study area (Mainland Australia), yet for the purpose of this lab, this was obviously not possible given time and computing power restraints. Therefore, one species was modelled in the notoriously finnicky software “Maxent,” with the data for a range of time frames and emission scenarios shown. I chose to put a null species in the map (the Red-Necked Pademelon) as well, in order to show how the selection bar would work given the time to make this map work for a range of species. I believe the slider and buttons approach is an extremely effective approach that maintains simplicity for the map reader, allowing them to focus on the data instead of a hard-to-operate control panel. I would have liked to animate the polygons for each time period to interpolate them through time, yet this proved to be an extremely difficult task. Therefore, I think having an easy-to-use time slider makes it very clear to the user what they species range would be for any given time period. The colour scheme was chosen in order to reflect the primarily negative scenario that we are likely to face regarding biodiversity. While some would argue that the RCP 2.6 scenario could be seen as positive, it is still likely to have significant negative affects on species and therefore I think a light-shade of red is the correct one. 

I found that MapBox GLJS was once again a great tool for the base map in this assignment, as it allowed me to easily create the foundations of this assignment. While much of the code does exploit the power of MapBox, a lot of it works purely in a JavaScript/HTML/CSS combination on it’s own. Through this lab, I definitely learned a huge array of skills that enabled me to filter data from a wider file. I also realized how many ways there are to solve a problem in JavaScript, and at times significant time was expended on approaches that didn’t end up working out. Likewise, the power of such a map lies in its ability to pull in huge sources of data, yet I was unable to do this due to the time constraints when it comes to species distribution modelling. This would be where I would suggest improvements would be needed to carry this project forward, and it would most likely come in the form of a back-end model that pulls data through an API, geoprocesses it and then displays it. After doing this lab however, I do not believe that would be out of my reach, yet it would require more hours than I have at this point in the term! 


<h2>Map Critique Sessions & Outside Sources</h2>


# What Are My Chances?

A web app I was writing when the outbreak of yellow fever hit us in Brazil in 2018, with the aim of hopefully helping people better evaluate whether they had better chances of survival by taking the vaccine, or avoiding it, by comparing the chances of getting infected by the disease versus the chances of suffering from severe complications from taking the vaccine.
Basically, if the chances of severe complications were higher than the chances of being infected by the disease if not taking the vaccine, the recommendation would be to avoid the vaccine, and vice-versa.
The calculation would be based on the user's current and future—planned—locations, health status as well as other factors.
I did some comprehensive research on the recommendations, and the whole thing was to be based on brazillian, as well as international, recommendations for yellow fever vaccination.
But "life got in the way" and I didn't get to finish it in time for it to be useful... but I might at some point.

# TODO:
* Break index.html into jinja templates
* Port styling to Sass
* Write remaining pages
* Write the whole system for systematically and reliably extracting data from "reliable" sources, calculating the users chances, and delivering it to the user
* Write a login system to enable users to save, privately, their named results, as well as to enable multiple runs on the same session so that parents can check for the whole family, save the results and not get confused with the multiple results they might have generated
* Structure it so to make it easy to support other diseases/vaccines
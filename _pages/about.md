---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there, my name François Protais. I am a Ph.D student at Loria/Inria in *Nancy, France* in [Pixel Team](pixel.inria.fr). I work under the supervision of *Dmitry Sokolov*, *Nicolas Ray* and *Franck Ledoux* (from CEA), on the tidious subject of Hexaedral meshing. 

# My work and interest: Hexaedral meshing
The aim of my research is very straight forward: **Make Hexaedral meshing works**. Because, well, it doesn't. *Hexaedral meshes* are a mean to represent objects in the computer, with, as the name says, *hexaedra*. Some physicians or mathematicians really like to represents their objects this way, to run all sort of computer experiment on those. Is it because of the quality that the representation offers or they can't be bothered to change their very old code that want hexaedra? I don't know, but if the ask me to do those meshes, I oblige.  

And it happens to be that generating those meshes is a pretty goddamn hard thing to do. It has been an active research field for more than 30 years, and we are yet to have methods that give wished results reliably. I am mainly studying a promising candidate, which are **Frame-Field based methods**. These are a recents approaches which come from Computer Graphics. While they suffer from dramatic robustness issues, when they work, they work very well. My current work is to find ways to improve this robustness, to help those physicians mistreat their poor informatically generated objects.

Studying Frame-Field based methods is very interseting as it gathers very broad subjects. While based on standard **geometry processing**, it requires to **solve difficults PDE**, do some **differential geometry**, work closely in **numerical optimization** while still doing some **mixed-integer optimization** on the side. The variety is definitively the cherry on the cake for curious personalities like me.

======
# My publications 
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
======

# My Talks 

  <ul>{% for post in site.talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
  </ul>
  
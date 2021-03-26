---
layout: default
---

## Abstract
Enabling the free and equal exchange of arguments on social issues in a respectful manner is an integral part of establishing the democratic ideal. However, the current manifestation of online spaces tends to facilitate the gathering of like-minded people, leading to the polarization of opinions. Such polarization inhibits the sharing of diverse opinions and deteriorates respect for disagreeing opinions.
To tackle this issue, we present <span style="color:{{site.syscolor}}">StarryThoughts</span>, an online system that supports users to express and explore diverse perspectives on social issues. The system supports three types of exploration of the collected arguments online: navigating opinions based on the demographic identities of the posters, checking the the stereotypes users hold towards demographics in relation to given social issues, and engaging with opinions with semantically different point-of-views. 
By deploying the system to the public in co-operation with a nationwide broadcasting company, we collected 1,950 opinions with 144 free-form responses from 1,209 visitors as initial data and iterated on the design.
Results from a user study with 56 participants showed that the system enables participants to explore a wide range of opinions on social issues, be more informed on the various arguments, and be more confident about their opinions. From our findings, we provide several design considerations for building online systems for supporting users to explore diverse opinions on social issues.

------

## System

{: .sys-img}
![An overview figure of StarryThoughts.](/assets/img/winder_main.png)

[Live version of the interface is available. (In Korean)](https://www.byulbyul.kr)

StarryThoughts aims to present the diversity of opinions as well as the contexts behind the opinions. StarryThoughts visualizes the opinions as dots on a 2-D space, following the metaphor of "Starry Night". To support the users navigate the opinions, we provided following three supports.

### Predicting and verifying supporters and dissenters of the issue

From the pilot studies, we learned that one of the most common usage scenarios of the system was to discover the trend of opinions according to the demographic factors. The participants had prior expectations on the strongest supporters or dissenters of an issue in terms of demographics.

To leverage such prior expectations for engaging the users, we included a step for explicitly stating their prior expectations on the opinion distribution by demographics in the system. Then, the user could verify their expectations by filtering the opinions from the expected supporter or dissenter groups.

### Exploring the trend of opinion per demographic group



### Exploring diverse opinion with recommendation

From the pilot studies, we learned that the participants felt overwhelmed from seeing a large number of opinions at once and relied on the recommendation feature. To support a more diverse exploration of opinions, we designed a recommendation algorithm for suggesting opinions different from the one currently being read. 

------

## Results


------

## CHI 2021 Paper (Camera-ready)

[Link to the PDF][1]

## Bibtex
<pre>
TBD
</pre>

------

{: .logos}
[![Logo of KIXLAB](/assets/img/kixlab_logo.png)](https://www.kixlab.org)
[![Logo of KAIST](/assets/img/kaist_logo.png)](https://www.kaist.ac.kr)

{: .center .acknowledgement}
This work was commissioned to be presented at the [SBS D Forum 2019](http://www.sdf.or.kr/2019) with support from the SBS Future and Vision Team.

[1]:https://kixlab.github.io/website-files/2021/cscw2021-StarryThoughts-paper.pdf

# vSAN-Adaptive-Quorum-Control-in-a-stretched-cluster
Adaptive quorum control assigns more votes to the surviving site to handle a subsequent failure of the witness site. 

https://www.youtube.com/watch?v=nX0OQDYuAP8

This video explains the voting magnetism used by vSAN during a site and a subsequent witness failure. Adaptive quorum control assigns more votes to the surviving site to handle a subsequent failure of the witness site. By assigning 3 votes to the components on the surviving site, there’s still a majority. Even when an additional host on the preferred site is lost, there are still enough votes to get a majority, so the virtual machine is still functioning.

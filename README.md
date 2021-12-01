# AnalyzingLanz
This repo contains the content of 92 episodes of the German talkshow "Markus Lanz". Some explorative quantitative text analysis will follow, soon.

# Data Collection
The data was retrieved by accessing the subtitles offered by the ZDF. 
1. mediathekviewweb.de was accesed via Rselenium to get the relevant links to the show itself as well as the subtitles
2. Information on the guests in the show was retrieved directly from the ZDF homepage by using Rvest.
3. Data on who speaks when was gathered by accessing the tags inside the video, again by using Rselenium
4. After several preprocessing steps in R, and the guests were assigned to their corresponding contribution in the show.

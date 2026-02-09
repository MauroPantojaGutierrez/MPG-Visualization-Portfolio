# MPG-Visualization-Portfolio
Compendium of projects focused on the area of information visualization 

## Observable notebooks:

### Explanatory Vis
Single-chart visualization to effectively communicates some idea about the data
#### Rationale: 
I decided to give my visualization a funny approach and answer a simple question “Will an international student most likely need vitamin D supplements while studying in Norway?” Though this vitamin can be obtained through diet, the most natural way to obtain it is  from skin exposure to UVB radiation, in other words: exposure to sunlight. Every person is different, has different dietary habits, come from a wide range of places and reacts different to the environment where they find themselves in, however, I find logical to suppouse that people from sunnier countries could experience a more notorious lack of vitamin D while being in a country like Norway. That said, my project proposes a comparison between the average sunlight hours of eight countries (I’m taking mine and my flatmates  countries as my study subjects) against Norway’s to “determine” which one of us will feel the lack vitamin D first (probably).

To make the handling easier my first decision was to transform the data to a tidy data format. Next I filtered the nine countries I wanted to use. After that, I decided to group all the data according to the months and countries to calculate a monthly average for each country, also getting rid of the ‘Year’ column in the process. As an additional step I created a second dataset grouping the values according to the country to calculate the average hours of sunshine each country gets in a year.

Regarding the marks and channels, I made a bar chart, which means I worked with  line marks using a vertical position channel to represent the average hours of sunlight according to the month, I applied a color scheme so the saturation of each line would reaffirm its belonging to a lower or higher value. Additionally, there’s another line mark using a horizontal position channel to highlight the yearly average hours of sunlight. To avoid a single saturated graph I decided to apply this same marks and channels while faceting for each country, obtaining a more extended view but easier to understand in my opinion.

Thinking about task and perception, I would say that the principal possible analysis action with my visualization would be to consume, more specifically, something between present and enjoy.  I try to tell a story with the data in a more casual context that I don’t think can be considered an actual forecast of the vitamin needs of a person from a specific country but more an interesting way to present the diferences between this kind of data on diferent parts of the world. In the context of a search I see my visualization more appropiate for a lookup, given that the main information that I want to present is already indicated and on display. And as a query, I think my visualization fits more in the ‘identify’ category but, I emphasize, identifying would imply affirming the need for vitamin D supplements, when in reality it is more a matter of simply identifying the countries that normally see more sun than Norway.

Regarding the things that my visualization may leave out, I think it is worth mentioning again that my decision to calculate a monthly average per country may hide peculiarities in a specific city, which would not accurately represent the difference between the data from Norway and the data from people coming from that place.

#### Link: https://observablehq.com/d/ac71ea597bd3cd58



### Deceptive Vis
Non-interactive visualizations for good and evil
#### Rationale: 
For this programming exercise I worked with two different questions: 

- **Honest Visualization**: Do people prefer movies that are suitable for all audiences?

- **Deceptive Visualization**: Does the number of votes affect the rating of a movie?

To answer my first question I chose a simple approach filtering the movies with some certificates considered appropriate for any audience and added the certificate “R” to the mix. The process consisted of grouping the movies by decade and obtaining the average rating depending on the certificate. To visualize the data in the most honest way I decided to use a cell mark, which allowed me to put on display all the information with labels in the axis and values in the cells, while this design also feels easy to read and often seen in movie/tv-shows ratings context. Aside from positions, I also added a color channel to distinguish better between cells with lower and higher values in hopes to help the viewer to quickly identify any increase or decrease in the ratings throughout the decades . As the objective was to compare the R certificate with the All-Audience-Friendly certificates, I added another mark: a line to draw attention to this specific cells.

To answer my second question I thought that if it is sometimes possible to do more with less, then I could probably show less with less and give very few and confuse information to the viewer (if that makes sense). I decided to use a bar chart to lure the viewer into a false sense of security. First, I grouped the data by rating value and calculated the average number of votes for each rating, I put the rating values in the X axis and rearranged the order to mess with the positions. I also messed with the Y axis by reducing the number of ticks to 5 to make really difficult to say around what value each bar is located, then I changed the notation used to display the value of each tick on the Y axis so that instead of showing an exact amount, it shows a multiplication and the letter M (for millions). To difficult more the interpretation of the bars, I used an identity color channel instead of a magnitude one and reduced the opacity to make them a little harder to tell apart. To add the final touch, I moderately reduced the width of the figure and drastically increased its height, resulting in a display that was not very pleasing to the eye.

Relating to the readings on color and interaction, for the honest visualization I already used a color channel suitable for that kind of data, but I think it would be interesting to show multiple views maybe to display the information for each decade separately allowing to analyze them in different combinations. As for the deceptive visualization, I implemented the hue/saturation combination to be a nightmare for the eyes, and thinking of interaction, a more dynamic way to change the order of the X axis could be a good strategy to confuse the viewer.

#### Link: https://observablehq.com/d/cf88b25fc21d44af

# MPG-Visualization-Portfolio
Compendium of projects focused on the area of information visualization 

## Observable notebooks:

### Programming Exercise 01: Explanatory Vis
Single-chart visualization to effectively communicates some idea about the data
#### Rationale: 
I decided to give my visualization a funny approach and answer a simple question “Will an international student most likely need vitamin D supplements while studying in Norway?” Though this vitamin can be obtained through diet, the most natural way to obtain it is  from skin exposure to UVB radiation, in other words: exposure to sunlight. Every person is different, has different dietary habits, come from a wide range of places and reacts different to the environment where they find themselves in, however, I find logical to suppouse that people from sunnier countries could experience a more notorious lack of vitamin D while being in a country like Norway. That said, my project proposes a comparison between the average sunlight hours of eight countries (I’m taking mine and my flatmates  countries as my study subjects) against Norway’s to “determine” which one of us will feel the lack vitamin D first (probably).

To make the handling easier my first decision was to transform the data to a tidy data format. Next I filtered the nine countries I wanted to use. After that, I decided to group all the data according to the months and countries to calculate a monthly average for each country, also getting rid of the ‘Year’ column in the process. As an additional step I created a second dataset grouping the values according to the country to calculate the average hours of sunshine each country gets in a year.

Regarding the marks and channels, I made a bar chart, which means I worked with  line marks using a vertical position channel to represent the average hours of sunlight according to the month, I applied a color scheme so the saturation of each line would reaffirm its belonging to a lower or higher value. Additionally, there’s another line mark using a horizontal position channel to highlight the yearly average hours of sunlight. To avoid a single saturated graph I decided to apply this same marks and channels while faceting for each country, obtaining a more extended view but easier to understand in my opinion.

Thinking about task and perception, I would say that the principal possible analysis action with my visualization would be to consume, more specifically, something between present and enjoy.  I try to tell a story with the data in a more casual context that I don’t think can be considered an actual forecast of the vitamin needs of a person from a specific country but more an interesting way to present the diferences between this kind of data on diferent parts of the world. In the context of a search I see my visualization more appropiate for a lookup, given that the main information that I want to present is already indicated and on display. And as a query, I think my visualization fits more in the ‘identify’ category but, I emphasize, identifying would imply affirming the need for vitamin D supplements, when in reality it is more a matter of simply identifying the countries that normally see more sun than Norway.

Regarding the things that my visualization may leave out, I think it is worth mentioning again that my decision to calculate a monthly average per country may hide peculiarities in a specific city, which would not accurately represent the difference between the data from Norway and the data from people coming from that place.

#### Link: https://observablehq.com/d/ac71ea597bd3cd58

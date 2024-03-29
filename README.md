# Data-Viz-With-IIP

- [Data-Viz-With-IIP](#data-viz-with-iip)
  - [Week-1 Challenge](#week-1-challenge)
  - [Week-2 Challenge](#week-2-challenge)
  - [Week-3 Challenge](#week-3-challenge)
  - [Week-4 Challenge](#week-4-challenge)
  - [Week-5 Challenge](#week-5-challenge)

Anyone who is interested in Data Visualizations related to India must have seen some really cool graphics from [India in Pixels](https://twitter.com/indiainpixels).

Ashris is the guy behind the amazing work at IIP. Together with Unacademy, he has started a course on Data Visualization. Every Weekend a certain aspect of Data Viz will be taught and a certain challenge will be given for everyone to participate.

---

## Week-1 Challenge

**Dear Alien Friend**

You have made an alien friend from Mars.
They are curious about your life. The catch is - they don’t understand human text but do understand numbers, shapes, geometry, colors, symbols, and signs.
Create a data portrait that helps your alien friend understand some aspect of your life -
(ex. friendship / music taste / personality / habits / relationships / ambition)
Constrain: You have to include at least one data point that is qualitative, one that is quantitative.

or

**Best State of India**

What is your definition of a good state?
Define six characteristics of a good state. Find datasets that help you compare all the states of India on the basis of these six traits. Decide which state is the best state.
Note: You need not base your definition on any existing framework.

I decided to do the Best State of India Challenge.
For that, I used the following 6 traits:

### The Six Traits

---

1. **[Life Expectancy](https://m.rbi.org.in/Scripts/PublicationsView.aspx?id=20671)**

> Data relating to Bihar, Madhya Pradhesh and Uttar Pradesh includes Jharkhand, Chhattisgarh and Uttarkhand, respectively. For states with NA values, mean of all states is taken.

2. **[Literacy Rate](http://www.pincodeindia.net/literacy-rate.php)**

> Also called the "effective literacy rate"; the total percentage of the population of an area at a particular time aged seven years or above who can read and write with understanding. Here the denominator is the population aged seven years or more.

3. **[Unemployment Rate](https://m.rbi.org.in/Scripts/PublicationsView.aspx?id=20673)**

> Employment figures are the sum of principal status and subsidiary status.

4. **[NSDP Per Capita](https://en.wikipedia.org/wiki/List_of_Indian_states_and_union_territories_by_GDP_per_capita#cite_note-:0-2)**

> Net state domestic product (NSDP) is the state counterpart to a country's Net domestic product (NDP), which equals the gross domestic product (GDP) minus depreciation on a country's capital goods. For UTs with 0 value, a min value of 10000 has been given.

5. **[Violent Crimes (Incidence & Crime Rate)](https://ncrb.gov.in/en/crime-in-india-table-addtional-table-and-chapter-contents?field_date_value%5Bvalue%5D%5Byear%5D=2018&field_select_table_title_of_crim_value=All&items_per_page=All)**

> Crime Rate is calculated as Crime per one lakh of population.

6. **[Net State Value Added by Agriculture](https://m.rbi.org.in/Scripts/PublicationsView.aspx?id=20684)**

---

### Data can be found at the following [link](https://docs.google.com/spreadsheets/d/1aYZc-aiJk40XSal2F5SCuA2WnQoslIAHY6PRS2w41R0/edit?usp=sharing)

The Analysis part and the map is in the [Week1 Jupyter Notebook](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/Week1.ipynb).

![Map](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/Best%20State%20of%20India.png?raw=true)

---

## Week-2 Challenge

![Flag](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/Week2_Challenge.png?raw=true)

For this we had to use p5js to create the flag.

Before creating that, I looked up p5 tutorials and found out about the following:
[p5js Youtube Tutorial](https://www.youtube.com/watch?v=HerCR8bw_GE&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=1)

It took me a whole week to go through all the videos and understand the basics of p5js. Also created my first [sketch](https://editor.p5js.org/probablyvivek/sketches/mtad3eaFS)

Then I also always wanted to contribute to Open Source (had done that once before but forgot about it). So, I checked the [p5js github repo](https://github.com/processing/p5.js-website). Forked it and then contributed to Hindi Translation of the library. :joy:

[Challenge](https://editor.p5js.org/probablyvivek/full/3tsSSTj5E)

![Flag](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/MarsFlag.jpg?raw=true)

I decided to consider the following: Since we are on Mars now, the flag needs to show how humans have evolved. It should also indicate that we are here from Earth.

Rectangle 1: Prussian blue symbolizes the universe / space in which we are. It is also the color of knowledge that means the vast amount of knowledge we have and the vast amount of knowledge we can learn.

Rectangle 2: White color symbolizes peace. Humans have come to this planet peacefully.

Ellipse 1: Orange: Symbolizes Mars.

Ellipse 2: Blue bolt color: Symbolizes the planet Earth.

Ellipse 3: Dandelion (Crayola) Color: Symbolizes our core values ​​and our roots are connected to peace.

The moving atom symbolizes from what we have developed and have now reached Mars.

---
## Week-3 Challenge

Using the existing Bollywood dataset, create two p5js visualizations - one png and one gif showing what you think is an interesting insight about Bollywood.

**Png Visualiztion**: I decided to create a Movie Data Potrait for Shahrukh Khan's top 10 movies from the dataset. The code and the files can be found in [here](https://github.com/probablyvivek/p5/tree/main/Bollywood)

![Shahrukh Khan](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/Top10SRK.png?raw=true)

**Gif**: 

Well, didn't really make a gif but ended up making a generative visualization. The code and the files can be found in [here](https://github.com/probablyvivek/p5/tree/main/Interactive)

![Art](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/mySketch.png?raw=true)

The [Interactive](https://editor.p5js.org/probablyvivek/full/KGndMpahB) version can be checked here.


---
## Week-4 Challenge

![Challenge](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/Week4%20Challenge.png?raw=true)

[Code](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/howstat.ipynb) for scraping data from Howstat.

We can scrape any link of howstat using this notebook which gives us files in JSON and CSV format.

I decided to scrape data for players scoring most runs in boundary during an IPL innings and then visualize the % of runs scored in boundaries in the innings. 

Here is how the viz looks like.

![Viz](https://github.com/probablyvivek/p5/blob/main/IPL/IPL.png?raw=True)

The [Code](https://editor.p5js.org/probablyvivek/sketches/3DAYagql1) can be found here.

---
## Week-5 Challenge
This was a little different week. We learned different aspects of art and design composition and some advanced visualisation techniques like making 3D networks and data sonification.

The Challenge for the week:
![Challenge](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/Art%20Critique.png?raw=true)

Being a big time Nolan fan. I just took screenshots from some of his movies to showcase how he used Balance in his frames. Other elements can be found too but I just showed how he uses Symmetrical and Asymmetrical balance in his movies.

[Nolan's Use of Balance](https://github.com/probablyvivek/Data-Viz-With-IIP/blob/main/USE%20of%20Balance.pdf)

---

**Final Thoughts:**

> An absolutely delightful course for learning the basics of data visualization using p5 and python. Learnt a lot especially while making the data portraits and Map design. 


:smile:

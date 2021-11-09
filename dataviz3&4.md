### Introduction
I decided to critique and redesign the visual on the following link: [The cost of renting a home vs Buying a home for every state in the US](https://howmuch.net/articles/cost-renting-vs-owning-home)

I choose this visualization as to see in which state renting is more benficial rather then buying a home. I myself struggled a lot to find a home when I came to the states to start my masters and I wanted to check how are the prices for renting a place in Pittsburgh. Also, the primary benefit of renting an apartment is flexibility. Renters can have a hassel free movement to a different neighbourhood without having to worry about selling their homes. According to the analysis, it is clear that renting is much cheaper than buying a home.

Redesigning this visual would help the people understand much better about what decisions should they be taking about renting or buying when moving to these states and can help them make better decisions.

Below is the initial visualiztaion:

<iframe width="1200" height="900" src="https://cdn.howmuch.net/articles/117_chart-7e7c.jpg"></iframe>

### Critques of the visualization
I think the following points don't work in the above visualization and can be improved to give people more advanced and insightful view about which option to choose amongst renting or buying.
1. The visual shows a stacked bar chart comparing average monthly mortgage payments and monthly rent payments  to do a comparison but using a different metric which is difference between renting and buying monthly payments would make much more sense.
2. The stacked bar chart uses 2 different colors pink and blue to convey the information about mortgage payments on the left and renting on the right respectively. A much more efficient way could be the usage of the same color (maybe blue or yellow) of bar now since we have changed the metric of comparison.
3. The visual is sorted by the monthly mortgage payments but then on the right side it becomes unsorted and then it becomes hard for the viewer to judge. 

### Wireframe of the solution
I created an initital wireframe of my solution, a simple pen and paper sketch, as shown below:

![Wireframe](/Wireframe.png)

My thought processs to create this wireframe was to show a contarst between renting and buying rather than doing a comparison between the two side by side like how it was originally. So I changed the metric about the decision between renting and buying by calculating the difference between the two and plotting a bar graph where above the x-axis on the positive side are the states where renting seems a better option and below the x-axis are the states where buying is preferred.

### Testing the solution
I got feedback from 2 people on my wireframe, each of which made me realize different things that I could improve with my visual:

1. Viewer 1 indicated that it would be more useful in terms of understanding to place the more intuitive title instead of "Renting vs Buying" as the main heading at the top along with the areas that specify the renting and buying section on either side of the x-axis, as that's the first thing that gets noticed we see.
2. Viewer 2 indicated that the story that my visual was concentrating on was in which states renting is more preferred than buying and to understand it much better I should use two colors for different areas renting and buying respectively.
3. Viewer 1 also suggested that it might be interesting if I could highlight the states which were neutral and did not have much difference between renting and buying.
4. Viewer 2 gave me a suggestion of instead of using boxes of Rent and Buy on either side of the axis, use a meter which would specify buying on the left side and renting on the right side.
5. Viewer 1 indicated to help understand the context better, sort the bars on the basis of difference in amount.

Answers to some of the other questions that I asked:
1. Both users were able to identify that the plot was aimed towards the general public looking to identify states where renting is preferred than buying.
2. Both users were able to understand the meaning of the visual and the interpretation being derived from them.
 
Based on the feedback provided by the 2 users, I moved on to change my visual accordingly.

### Building my solution
Based on the feedback received, I made the following changes:
1. I categorized Renting and buying with two different colors to show a contrast ( Buying - Orange and Renting - Green)  .
2. Sorted the data based on the difference amount showing the meter level movement towards buying from left to right.
3. I changed the title to much more brief description about the story that the visualization wants to convey which "According to 2018 statistics, renting is better in majority of the states".
4. Added the legends to signify rent and buy.
5. Changed the Y axis label to much more descriptive title.

### Final Visualization
My visualization is attached below:

<div class="flourish-embed flourish-chart" data-src="visualisation/7769379"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


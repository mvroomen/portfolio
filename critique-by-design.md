| [home page](https://mvroomen.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique By Design

## Original Graph

The original graph was created for use by The Fertilizer Institute, a trade association in Washington D.C., to address the supply-side explanation for the increasing price of fertilizer in late 2021 for concerned farmers and agricultural retailers.  The US corn crop uses about 50% of the fertilizer supply, meaning that fertilizer demand is heavily correlated with corn prices.  As corn prices increase, more farmers plant corn and therefore demand more fertilizer, therefore, causing fertilizer prices to increase.  At the same time, when farmers plant more corn, they are often switching land from growing soybeans or wheat to corn, lowering the supply of soybeans/wheat, and therefore increasing their prices, which kicks off the same increase in price and higher demand for fertilizer as explained for corn.  The graph aims to provide price trend data to support this story.

![HV 59 graph](https://user-images.githubusercontent.com/123427692/216985221-0fd15825-5856-4e0d-95d4-864496dc703c.png)

The graph has several strengths and areas with room for improvement, but overall, it is an effective communication device when paired with its story.  With some improvements, it may be able to stand on its own.

Strengths:
The dual y-axes allow the graph to successfully convey both the corn price and fertilizer prices.
The features of the graph are fairly clear and easy to read
The green box highlights the focal point of the story
Color coding is used to differentiate between the various fertilizers and corn
The “static pop-up” conveys the percentage change for the important period of time
Nothing in the graph appears to be attempting to mislead the reader, nor is anything unclear in such a way that the reader is likely to come to wrong conclusions due to design.

Areas with room for improvement:
(Note: to avoid being redundant, I address my fixes below my sketch)
The colors, as well as the intense grid lines, are very intense and distract from the message of the graph by adding unnecessary busyness.
The green box, although effective, could be improved through shading the lines or that section of the graph.
Having the line labels sort of randomly on the graph can be slightly confusing and distracts from the main message of the graph.
The Y-axis on the right is lacking a label telling the reader it represents corn price.
The “thought bubble” that says “Corn and Fertilizer Prices Rise!” conveys the main idea of the graph better than the title “Fertilizer and Corn Prices: January 2018-October 15, 2021”, which just tells the reader, in the most literal sense, what they are looking at.
The “static pop-up” conveys too much information by having two sets of percentage changes.
The corn data ends prior to the fertilizer data, which can potentially confuse the reader.
Those who know enough to know why the fertilizers are labeled with (Midwest) and (Tampa), which indicate the location the pricing data is pulled from, probably don’t need that information on the graph, because they know the key “pricing” locations for these products.
The X-axis and Y-axis on the left are too busy.  They both could use fewer data points.

## Sketched Wireframe
![Sketch](https://user-images.githubusercontent.com/123427692/217418937-2ee87a59-6439-49ae-9e9e-6ca89346ef2a.jpg)

In my sketch, I attempted to fix many of the areas I identified above.  

First, I rewrote the title of the graph to convey the “big idea” the graph was intending to convey, which alters the graph’s role to “supporting evidence to the “big idea, rather than attempting to convey the big idea all on its own.  I did this by taking the information conveyed in the “thought bubble” to inspire my new title “High Corn Prices, High Fertilizer Prices Follow”.

Second, I eliminated the data that went beyond August 2021, since the corn price data was only available until then.  Now, all the lines end in the same time period and the reader isn’t left wondering why the corn line stops before the others.  This also led me to eliminate those percentage change notes from the “static pop-up”.  Similarly, I eliminated the names of the cities whose market prices were used since I think this is common knowledge.

Third, I reduced the tick marks on the X-axis and Y-axes.  Since we are concerned about trends, we don’t need precise data points.  May and November correspond roughly with when fertilizer is applied so I decided to use them as my 6-month tick markers.  Reducing the amount of tick marks reduces clutter on the graph without causing any confusion or risking that the reader will misinterpret the data.  While doing that, I added a label to the right-hand y-axis conveying the price of corn per bushel.

Fourth, I reduced the number of gridlines and changed the colors of the corn and fertilizers lines to four more complimentary colors.  For the rest of the graph, I kept it gray, including eliminating the bright green box and replacing it with more intense lines for that section of the graph and a simple gray dotted line to note when July 2020 begins.  My goal with these changes was simply to reduce how much was going on visually with the graph.

Fifth, to continue reducing how much was going on with the graph, I moved the line labels and the “static pop-up”  into a legend below the graph.  This makes the graph easier to read by not cluttering the graph itself.

Sketch Feedback:
I received helpful feedback/critiques from: two adults in their 60s, one adult in their 20s, and two adults in their 30s  (All work with graphs, none have extensive data viz backgrounds)

The main takeaways from the feedback were:
The color palette is simple and the yellow for corn is an excellent choice.
A line graph makes sense - I don’t think any other graph would work.
The title is good, but it’s not easy enough to tell that it starts in July 2020.
The “Dollars Per Ton” doesn’t match the “Corn Price Per Bushel” in form.
The legend and caption should be color coded and in a more logical order.
The two Y-axes should match better - why is $800 at $6?
“You will not be able to recreate the X-axis the way you have it easily”

## In Progress Tableau Redesign
<div class='tableauPlaceholder' id='viz1675690325588' style='position: relative'><noscript><a href='#'><img alt='Q3 2020 Sees High Corn Prices, High Fertilizer Prices Follow ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Inprogress-CritiquebyDesignGraph&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Inprogress-CritiquebyDesignGraph&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;Inprogress-CritiquebyDesignGraph&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1675690325588');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Once I had my sketch feedback, I made my first attempt at a version of the graph in Tableau that implemented the feedback I received, however, as you’ll notice, I forgot a few and made a few typos.

Simply by using Tableau, a fair amount of the suggestions sort of automatically took place.  The legend became color coded, the Y-axes roughly matched each other, and the tick marks on all axes simplified themselves.

Then, I made some additional changes to improve the graph:

First, I added “Q3 2020” to the title, to immediately indicate where the reader should look for the main part of the story.  Next, I added and color coded the caption with the information on the percentage change price between July 2020 and August 2021.

Lastly, I added the “reference bar”, which is the gray bar covering July 2020 to July 2023 to highlight the portion of time of interest.  I had originally wanted to make that section of the lines more intense, but that wasn’t an option in Tableau.

To be perfectly honest, simply figuring out how to correctly make a dual axes graph in Tableau, these were all the changes I was able to implement before our Monday class student feedback section.

In Progress Tableau Design Feedback:
I received helpful feedback/critiques and Tableau assistant from three of my classmates.  Having a class feedback session was incredibly helpful because we had a good understanding, as a group, of what Tableau was capable of.

The main takeaways from the feedback were:
The yellow for corn is an excellent choice, but the other colors are too busy and could be changed into “background colors”.
The title is helpful and informative.
The dual-axes are effective, but neither need to start at zero (they then helped me figure out how to change them correctly!)
The legend is great, but doesn’t need the “measure names” title.
The gray reference box is incredibly effective (I helped a classmate find the menu to make one!)
Think about making the lines more transparent so they don’t get lost when they cross each other.

## Final Tableau Redesign
<div class='tableauPlaceholder' id='viz1675826340324' style='position: relative'><noscript><a href='#'><img alt='Q3 2020 Sees High Corn Prices, High Fertilizer Prices Follow ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final-CritiquebyDesignGraph&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Final-CritiquebyDesignGraph&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Fi&#47;Final-CritiquebyDesignGraph&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1675826340324');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

For my final version, I was able to make some final edits on my caption, title, and axes labels, as well as implement the incredibly helpful suggestions of my classmates.

For my title and caption, I rephrased how I expressed the main ideas to make the story clearer.
Next, I reordered the legend to make sure “Corn” was at the top, followed by the three fertilizers.
Then, I changed the colors of the three fertilizers as suggested by my classmates, which really made “Corn” pop as the main character of the story.
Then, I color coded the caption to match the legend, which creates a nice uniformity to the graph.  (I did ask a few people if the word “Corn” was legible in yellow and everyone said yes, but I am still unsure.)
After that, I modified the Y-axes to start at $200 and $2.00.  (Unfortunately, no matter what I do in Tableau, I cannot get the decimal places to stay how I’ve set them once I exit Tableau Desktop).
Finally, I fixed the fertilizer price Y-axis label to “Fertilizer Price Per Ton” to match the “Corn Price Per Bushel” on the other Y-axis, which is easier to read and remember.

Overall, I’m really happy with my redesign of the graph.  Despite some limitations in my Tableau skills limiting my final product, I think the redesigned graph is easier for the reader to understand.  It is less cluttered due to the reduction in bright colors, grid lines, and excess tick marks, and my new title and caption tell the story more effectively than the text features on the original graph. 

## Additional/Alternate Redesign Ideas
### (These were not critiqued by others)

In order to experiment with more graph types, I decided to try additional graph types in Flourish.  

For both charts, I changed the unit for Corn to price per 100 bushels to better match the prices of the fertilizer since I couldn’t do a dual y-axis (as far as my exploration of Flourish suggested).

In the grid lines chart, I added a little color back to the fertilizer lines since the yellow still makes the corn “pop”.  The grid lines are a very effective way to show that the four products followed the same general trend.  Since I couldn’t easily highlight the period from July 2020 to August 2021, I left the caption off.

In the Line Chart Race, the trends really come to life!  It’s great to be able to see that the four items were fairly close together around the $270-420 range and then by the end, they had all climbed to the $588-658 range together.  After seeing this graph, I started wondering if I should have changed the corn units to per 100 bushels and used one y-axis all along.

### Grid of Line Charts

<div class="flourish-embed flourish-chart" data-src="visualisation/12680859"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Line Chart Race 

<div class="flourish-embed flourish-chart" data-src="visualisation/12680631"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

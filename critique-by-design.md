| [home page](https://zttcoder.github.io/zyw-portfolio-2026.3/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design -- Viz of Labor Market Exit Age
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._

link to the original data visualization: https://www.statista.com/chart/29570/european-average-effective-labor-market-exit-ages/

Source: Statista.com


## Step two: the critique
_Don't forget to complete the Google Form found on the assignment page.  You can summarize your thoughts here._

### Worked well:

- The color gradient clearly shows differences in retirement age across countries, making it easy to identify patterns at a glance.
- The title is engaging and clearly communicates the main question of the visualization.
- The layout and the coler pattern is nice to look at overall.

### Didn't Work well:

- Exact values for each country are not labeled, so it’s hard to know precise retirement ages.
- Also, the country names are not labelled, so for people with little European geographic knowledge it would be hard to understand.
- Some countries are small and difficult to see clearly on the map.

### My Thoughts for Redesign:

- Add labels or tooltips to show exact values for better readability.
- Use a different chart type- to make comparisons easier.
- Include additional dimensions (such as gender differences or changes over time) to provide more info.


## Step three: Sketch a solution

<img src="sketch.jpg" width="300"/>


## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Is there too much information in one single graph?

- Is it clear and readable for the intended audience?

- Is there anything you find surprising or confusing?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._

I got two interviewee to answer my questions and they gave me helpful advice. The synthesis of their answer and our discussion based on that can be found below.

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

Feedback I got: 

- Using a heatmap is an interesting choice, but displaying all countries and all years in a single table results in too much information and can be overwhelming. It would be better to focus on a specific subset of the data.
- more attention should be paid to the use of colors
- Setting the time axis horizontally seems more natural.

What I learned from the feedback:

- We should first thoroughly explore and understand the original dataset. Based on its characteristics and underlying trends, then choose appropriate visualization methods and decide what aspects of the data to highlight.

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

After completing the interviews, I decided to focus on my classmates’ suggestion to reduce the amount of data to avoid clutter and to concentrate on a specific subset. At the same time, I also wanted to experiment with different types of visualizations, since the original dataset includes multiple dimensions—country, gender, and year—which are difficult to effectively present in a single chart.


To present the characteristics and trends of the original dataset as comprehensively as possible, I used three different types of visualizations. First, I created a heatmap to show the average retirement age for each country across different years, using color spectrums to visually represent the magnitude of the values. I also focused on the top 5 and bottom 5 countries in terms of average retirement age to reduce cluttering and highlight the most significant patterns.

Next, I used a dumbbell chart based on the most recent data (2020) to illustrate the differences in retirement age between genders, as well as the variation in gender gaps across countries.

Finally, I created a traditional line chart to more clearly show how retirement age changes over time.(countries with top 5 average retirement age)

<div class='tableauPlaceholder' id='viz1775174497351' style='position: relative'><noscript><a href='#'><img alt='Gender Gaps in Retirement Age Vary Across Countries ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetiringAge&#47;Sheet4&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RetiringAge&#47;Sheet4' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetiringAge&#47;Sheet4&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1775174497351');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


<div class='tableauPlaceholder' id='viz1775102006442' style='position: relative'><noscript><a href='#'><img alt='Retirement Ages Show decreasing Trends Globally, but Significant Country Gaps Remain ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetiringAge&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RetiringAge&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetiringAge&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1775102006442');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


<div class='tableauPlaceholder' id='viz1775174412713' style='position: relative'><noscript><a href='#'><img alt='Narrowing Differences in Retirement Age Across Countries Over Time ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetiringAge&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='RetiringAge&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;RetiringAge&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1775174412713');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## References
_List any references you used here._

Data Source: https://data.world/makeovermonday/2023w16/workspace/file?filename=Effective+labour+market+exit+age.xlsx

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

I only used AI to help me rephrase and organize my comments.


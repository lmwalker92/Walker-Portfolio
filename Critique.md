# Critique by Design
The visualization that I chose to critique and redesign is titled ["Tuition Costs for Common Universities"](https://datausa.io/profile/cip/music?tuition-measure-tuition_costs=inStateMeasure#tuition_costs). The original data comes from the National Center for Education Statistics' Postsecondary Education Data System. The visualization consists of three different bar graphs about music universities in North America, with each chart showing information for the years 2013 through 2020. Here, music universities consist of both post-secondary institutions that are specifically for music, as well as universities that have reputable and/or popular music degree programs. The first graph shows the in-state tuition rates for music universities; the second graphs shows out-of-state tuition rates; the third shows the total number of graduates from each school in a particular graph.

I think the intended audience of this graph would be people who are looking towards obtaining a post-secondary degree in music. I believe that the reader can understand the information with minimal effort. While I think the visualization is helpful for its intended audience, I also think there can be different ways to visualize the data on the tuition rates and number of graduates for each university.

While the extended data set includes tuition data from a long list of universities and colleges, this graph only includes a "top 5" listing of universities (which is shown on the y-axis). However, I was not sure what the criteria was for determining which schools are considered to be "top 5;" data is provided for 2013 through 2020, and while there are some schools that seem to remain in the top five each year, others enter and exit the listing. Additionally, in the last graph (total graduates), the values on the x-axis contain monetary signs, but from looking at the raw data, I believe that those values do not need to be there.

Using Stephen Few's "Data Visualization Effectiveness Profile," I gave the following scores to the original visualizations:
- Usefulness: 9
- Completeness: 7
- Perceptibility: 6
- Truthfulness: 9
- Intuitiveness: 8
- Aesthetics: 5
- Engagement: 7

## Initial Sketches 
As a whole, I thought the original visualization was well done, but I believed that there were some things that could be improved on or added. For my redesign, I wanted to include data on the schools that were commonly listed as being in the "top 5" music universities in the original visualization, while also including other reputable and/or popular music universities and programs.

![initial sketch 1](https://user-images.githubusercontent.com/122955915/217414331-fc974ad7-f127-4616-bc82-c77ce424ebd3.jpg)

One aspect that I wanted to highlight in my redesign was the change in tuition rates over time. While the original visualization did have data from different years, the viewer has to click back-and-forth between the different years in order to see the differences. In order to better demonstrate change over time, I sketched a line chart using some of the data from some of the universities in the original visualization.

![initial sketch 2](https://user-images.githubusercontent.com/122955915/217414541-4bbdb2d4-5271-4f88-b88e-f003e32d7d5f.jpg)

Another way I thought of redesigning the visualization was to plot the number of graduates of a particular university and the tuition rate for a specific year in order to see if there was a correlation between the two variables. For the scatter plot sketch above, I chose out-of-state tuition to be the variable on the y-axis.

## Student Feedback 
- The line chart was easier to understand than the scatterplot. With all of the abbreviations of the universities above the points, it was a bit hard to understand the importance of the data/what the data was saying.
- The titles could be shorter and clearer
- Make sure that the sample size is not too large 

## Secondary sketches
The following sketches were created after getting feedback from the student. Two were sketched by hand, and one was made using Tableau. After getting feedback from the student, I decided that the line chart was more aligned with how I wanted to redesign the visualization.

![sketch version 2 (1)](https://user-images.githubusercontent.com/122955915/217416930-9943cf8e-d43c-4856-b000-e17c37e8929f.jpg)

In this sketch, I hand-drew a version of what I wanted the final visualization to look like (although this sketch does not include all of the universities that were used in the final). Rather than including the names of each university at the end of the line like in the first sketch, the lines are color coded with a legend at the bottom.

![sketch version 2 (2)](https://user-images.githubusercontent.com/122955915/217416961-d4754215-f520-4406-8503-629d0dc26d57.jpg)

This is a hand-drawn version of the total graduates redesign. Similar to the sketch before, it does not include all of the universities that were used in the final. 

![critique draft 2 PDF in state](https://user-images.githubusercontent.com/122955915/217416990-94a3f59d-0cac-47df-9821-9959acbce97a.jpg)
I used Tableau to draft a cleaner version of what the final redesign might look like. I wanted to highlight the universities that have different in-state tuition rates compared to their out-of-state rates.

## Non-student adult feedback
- In my conversation with an adult who is not a student, I had to explain the sketch of in-state tuition rates, and why I used gray for this visualization. For that visualization, I wanted to highlight the universities where the in-state tuition rate is different from the out-of-state tuition rate (i.e. public universities). This conversation led me to add a brief sub-title that made it clearer that my intent was to highlight public universities.
- The adult also suggested making the lines a little bit thicker, unless it would lead to cluttering the graph.

## Final Redesigns
Ultimately, I chose a sample size of 18 universities to include in the final visualization redesign, as the original dataset included information from a large number of four-year institutions and community colleges across North America. 
<div class='tableauPlaceholder' id='viz1675826681139' style='position: relative'><noscript><a href='#'><img alt='Out-of-state Tuition at Music Universities, 2013-2020Data shows that price of tuition for out-of-state students increased yearly in most music universities and conservatories ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;Redesignfinal-ish&#47;Out-of-state&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Redesignfinal-ish&#47;Out-of-state' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;Redesignfinal-ish&#47;Out-of-state&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> 
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1675826681139');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

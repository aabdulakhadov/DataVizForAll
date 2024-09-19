# Step One: Choose a Data Visualization
For this critique, I selected the donut chart presented on page 25 of the "Global 500 2023" [report](https://static.brandirectory.com/reports/brand-finance-global-500-2023-preview.pdf) by Brand Finance. The chart demonstrates the proportional distribution of brand value across countries, with a clear emphasis on the United States and China.

<img src="Sketch Bubble chart.jpg" width="500"/> 

# Step Two: Critique the Data Visualization
The original donut chart has several strengths and limitations:

### Strengths:
- **Effective use of donut chart:** It visually highlights the dominance of major countries (USA, China) in global brand value.
- **Clean layout:** The combination of the donut chart with a table makes it easy to understand the contributions from each country.
### Limitations:
- **Minority countries underrepresented:** Countries like South Korea and Canada are difficult to distinguish due to the small size of their slices.
- **Eye travel issue:** Users frequently need to shift between the chart and the legend/table, which can reduce the overall ease of comprehension.
- **Lack of per-brand value insight:** The chart only reflects total brand value, missing a crucial opportunity to show average brand value per brand for each country.

## Recommendations:
To better highlight insights for smaller countries, I would suggest switching to a bubble chart. This visualization would allow for three key variables:
- Number of brands (x-axis),
- Average brand value (y-axis), and
- Total brand value (size of the bubbles).

# Step Three: Sketch Out a Solution
For the redesign, I sketched a bubble chart that visualizes the relationships between the number of brands, average brand value, and total brand value by country. Each bubble represents a country, with bubble size proportional to the total brand value.

<img src="Sketch Bubble chart.jpg" width="500"/> 

# Step Four: Test the Solution
I tested my proposed bubble chart with two users and gathered the following feedback:

- **Feedback 1 (Student, mid-20s):** They found the abbreviated country names unclear and suggested using full names. They also noticed that the total brand value labels lacked formatting (such as indicating USD in billions). The title was noted to be slightly unclear.

- **Feedback 2 (Student, late-30s):** This user found the x-axis label small and difficult to read. They also suggested adjusting the y-axis scale to reduce the number of ticks and make the axis easier to interpret.

# Step five: Build your solution
The bubble chart below illustrates the Top 500 Brand values by country. As shown, the US leads with a total brand value of $3,981.2 billion. However, this is achieved with 201 brands, which accounts for more than 40% of the total number of brands. Notably, South Korea stands out with the highest average brand value among all countries depicted on the chart. By hovering over each bubble, you can view a tooltip showing precise figures, including the number of countries (y-axis), average brand values (x-axis), and the total brand value represented by the bubble size.

<div class='tableauPlaceholder' id='viz1726708392302' style='position: relative'><noscript><a href='#'><img alt='Small but Mighty: South Korea’s High-Value Brands Outshine in the Top 500 Global Brands for 2023. '                                   src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Top500Brands_17267083330930&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Top500Brands_17267083330930&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Top500Brands_17267083330930&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726708392302');                    
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

[Return to Main Portfolio](/README.md)

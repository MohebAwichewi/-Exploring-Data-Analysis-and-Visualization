# Introduction to Jupyter Notebooks: Exploring Data Analysis and Visualization-
## 1. This is a Jupyter notebook!
<p>A <em>Jupyter notebook</em> is a document that contains text cells (what you're reading right now) and code cells. What is special with a notebook is that it's <em>interactive</em>: You can change or add code cells, and then <em>run</em> a cell by first selecting it and then clicking the <em>run cell</em> button above ( <strong>▶|</strong> Run ) or hitting <code>ctrl + enter</code>. </p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/c587edce-b1c6-472a-bd26-952cc7332a25)

<p>The result will be displayed directly in the notebook. You <em>could</em> use a notebook as a simple calculator. For example, it's estimated that on average 256 children were born every minute in 2016. The code cell below calculates how many children were born on average on a day. </p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/02b41b53-8ad9-4431-b510-65eb9b506e5c)

## 2. Put any code in code cells
<p>But a code cell can contain much more than a simple one-liner! This is a notebook running python and you can put <em>any</em> python code in a code cell (but notebooks can run other languages too, like R). Below is a code cell where we define a whole new function (<code>greet</code>). To show the output of <code>greet</code> we run it last in the code cell as the last value is always printed out. </p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/ed5aeec2-17ce-4740-8d1b-e1942e6c0f29)
## 3. Jupyter notebooks ♡ data
<p>We've seen that notebooks can display basic objects such as numbers and strings. But notebooks also support the objects used in data science, which makes them great for interactive data analysis!</p>
<p>For example, below we create a <code>pandas</code> DataFrame by reading in a <code>csv</code>-file with the average global temperature for the years 1850 to 2016. If we look at the <code>head</code> of this DataFrame the notebook will render it as a nice-looking table.</p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/7be6cf94-e389-49da-a855-7dcce0b96e70)

## 4. Jupyter notebooks ♡ plots
<p>Tables are nice but — as the saying goes — <em>"a plot can show a thousand data points"</em>. Notebooks handle plots as well, but it requires a bit of magic. Here <em>magic</em> does not refer to any arcane rituals but to so-called "magic commands" that affect how the Jupyter notebook works. Magic commands start with either <code>%</code> or <code>%%</code> and the command we need to nicely display plots inline is <code>%matplotlib inline</code>. With this <em>magic</em> in place, all plots created in code cells will automatically be displayed inline. </p>
<p>Let's take a look at the global temperature for the last 150 years.</p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/93502534-b648-41d6-9af7-6f2a27baafe2)

## 5. Jupyter notebooks ♡ a lot more
<p>Tables and plots are the most common outputs when doing data analysis, but Jupyter notebooks can render many more types of outputs such as sound, animation, video, etc. Yes, almost anything that can be shown in a modern web browser. This also makes it possible to include <em>interactive widgets</em> directly in the notebook!</p>
<p>For example, this (slightly complicated) code will create an interactive map showing the locations of the three largest smartphone companies in 2016. You can move and zoom the map, and you can click the markers for more info! </p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/c52e271b-eb96-4d56-ad5b-71649b760f8f)
![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/9fbfcdcd-53e8-4067-b636-90c971da4590)


## 6. Goodbye for now!
<p>This was just a short introduction to Jupyter notebooks, an open source technology that is increasingly used for data science and analysis. I hope you enjoyed it! :)</p>

![image](https://github.com/MohebAwichewi/Introduction-to-Jupyter-Notebooks-Exploring-Data-Analysis-and-Visualization/assets/149394585/7bef7ccf-369b-4a67-8558-ea76cf5c929c)

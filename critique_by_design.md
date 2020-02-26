# Critique By Design - Forbes Coachella vs Other Music Festivals 2015 Chart
I knew that I wanted to work with data related to music or music festivals. From my research, I found many terrible charts on music festivals. I decided to choose this particular chart because the price and value of music festivals are continuous discussion topics amongst my friends and I. This chart demonstrated Coachella's high value compared to other music festivals when looking at the price one pays per artist. Although Coachella may have a seemingly steep multi-day ticket price, the amount of artists one can see is significantly more than other popular music festivals.
![Forbes_Coachella_vs_Other_Music_Festivals_2015](https://user-images.githubusercontent.com/59836288/73617812-82f84e00-45f0-11ea-9043-c2acb865631c.jpg)

# Critique by Design - Process
In terms of process, I decided to analyze the original chart and understand what data should be highlighted. There were really three points of data: multi-day ticket price, number of artists, and price per artist. Out of these three data points, the price per artist 
seemed the most important because points to the real value of each music festival.

Next, I spent time determining where I can remove some text and/or objects because I think a simple and clear chart means less is more. I immediately found text that was repetitive. For example, I could remove "multi-day ticket," which was repeated in each record icon. Furthermore, I also wanted to remove the record icon. Although it is an interesting graphic that represents music, a more simple icon can still be effective because I want the star of the chart to be the data itself. I liked the order of the records and how they represented price per artist and I knew that I wanted to continue size in some way in the updated chart. I think what also would have been helpful is to clearly state the calculations made. For example, there can be "multi-day ticket price / number of artists = price per artist" listed as part of the subheading. Moreover, the title can be more captivating if it did not just describe the data but highlight a key point that the chart is trying to make. For example, the title could be: "Despite Coachella's Rising Popularity, It's Still A High Value Festival."

After analyzing the original chart, I decided to play around with different tools to see how I would create my wireframe solution. I played around with Balsamiq but in the end decided to use Infogram because the options worked well with my dataset. I uploaded my data and took my time selecting different kinds of charts. I chose the bar chart because it was simple yet effective in displaying my data. I decided on an interactive chart because it allowed me to display three different charts, which I thought was necessary to showcase the three main points I mentioned earlier. Next, I changed the color scheme to gray out the other music festivals and chose an orange-brown to highlight Coachella. This signals to my audience that I want them to focus on comparing Coachella to the other music festivals. 

<div class="infogram-embed" data-id="52bdb560-245f-4b09-91e3-bf8dc5bafd44" data-type="interactive" data-title="Forbes Coachella Critique"></div><script>!function(e,i,n,s){var t="InfogramEmbeds",d=e.getElementsByTagName("script")[0];if(window[t]&&window[t].initialized)window[t].process&&window[t].process();else if(!e.getElementById(n)){var o=e.createElement("script");o.async=1,o.id=n,o.src="https://e.infogram.com/js/dist/embed-loader-min.js",d.parentNode.insertBefore(o,d)}}(document,0,"infogram-async");</script><div style="padding:8px 0;font-family:Arial!important;font-size:13px!important;line-height:15px!important;text-align:center;border-top:1px solid #dadada;margin:0 30px"><a href="https://infogram.com/52bdb560-245f-4b09-91e3-bf8dc5bafd44" style="color:#989898!important;text-decoration:none!important;" target="_blank">Forbes Coachella Critique</a><br><a href="https://infogram.com" style="color:#989898!important;text-decoration:none!important;" target="_blank" rel="nofollow">Infogram</a></div>

Next I spent time collecting user feedback. I shared my chart with different friend groups and classmates. I started by sharing the chart first and then asking them what they think the main point is. I figured a too long pause or unsure answers meant that I had to spend more time highlighting the key point. Most knew that Coachella was to be compared with other music festivals. They understood how the price per artist calculation was made and knew that the data was from 2015. Where I needed to improve was to emphasize that the price per artist was the most important focus. Having three charts clouded this focus. Also, the animation was interesting and amusing to some but others believed that the animation could also be a headache and the movement made it difficult to read the data. From this, I knew I had to choose one chart and make that one chart focus on price per artist.

After receiving several critiques, I mapped out some charts in Tableau. My first chart was a scatter plot. I decided on a scatter plot because I wanted to use a musical icon, similar to that of the original chart. I chose the Odesza icon, which was appealing to friends and classmates of mine because they could instantly tell that this chart would have data related to music. I chose a brown color scheme for the other music festivals where the darker the shade, the higher the price per artist. I used size of the icon to represent the other data point, which was multi-day ticket price. I made Coachella blue to make sure that it contrasted the other music festivals well. I only had Coachella labeled and showing its price per artist. I added an average price per artist line to further demonstrate how Coachella was a better value festival compared to the average. I shared this chart with the same groups and they agreed that this was a step up from the wireframe and my message was more clear. However, there was some misunderstanding with the color scheme and size of icon. There was also difficulty in understanding which icon represented which festival.

![Music Festival_Dollar Per Artist_2015](https://user-images.githubusercontent.com/59836288/73623427-eb542900-460a-11ea-95f1-4102947952a7.png)

Taking the critiques from my first solution, I decided to try one more Tableau chart. The next one I made was a map chart. This helps to add more detail and context for the chart by displaying location. I used color to arrange festivals by location. For example, green represents the west coast. I called more attention to Coachella by choosing a different shade of green and adding a different data label, which has text in the darker green and has price per artist and number of artists labeled. The price per artist field is also demonstrated with size of the data point. The higher the price per artist, the larger the data point. Here, the audience can clearly compare different festivals because they are all labeled. The audience has the added benefit of comparing festivals per region. When I showed this updated chart to the same groups for critique, they noted that this chart was the most simple and clear compared to the previous charts because it fixed the issues in the previous charts.

![Music Festival_Dollar Per Artist_2015_Map_Only](https://user-images.githubusercontent.com/59836288/73623462-02931680-460b-11ea-80e0-35cb64395861.png)
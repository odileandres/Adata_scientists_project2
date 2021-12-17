---
layout: page
title: Society vs Media
subtitle: Men and women, equals in the eyes of the media?
cover-img: /images/Odile2.png
---
<html>
 <body>
   <p>
   <img class="center" src="/images/6ibbh0oB4OGAGZm4PSuBh9.jpg">
   </p>

   <p align="justify">
    Ever since 2007, <i>#MeToo</i> has been trending on social media, especially after the Weinstein gate in 2017. Since then, the debate around inequalities between men and women has been a burning subject. Organized sexual exploitation of young women, like the gate of Jeffrey Epstein, inequalities, trivialized sexism, sexual harassment, consent, all have been on the headline of the journals and have triggered massive demonstrations all over the world. 
   And the media are not innocent in this social discrimination.
   Indeed, according to research pursued by the  <a href="https://beijing20.unwomen.org/en/in-focus/media">UNWomen</a> over more than 100 countries, sexism in the media nowadays is striking. In terms of managing positions, men still represent 73% of the top media management positions, according to another study gathering 522 news media organizations. Moreover, about 46% of news stories spread gender stereotypes and only 6% promote gender equality. 
   </p>
 <br>
   <h2>Our goal: </h2>
   <p align="justify">
   In our analysis, we want to see whether the feminist movements from the last years had any significant impact on the representation of women in the media. 
   </p>
   <p align="justify">
   <b> <i> In other words, are women more represented nowadays than before 2015, are they represented in all the fields at the same level of men and is there still a discrimination based on age against women?</i> </b>
   </p>
 <br>
   <h1> Inequal representation in the media in terms of coverage </h1>
   <br>
   <hr style="color:gray;background-color:gray;width:50%">
   <quote>
    <p style="margin: 0px;">
     <i>"The media reflects what the people say, the people reflect what the media says. Will we never tire of this mind-numbing game of mirrors?"</i>
    </p>
    <p style="margin: 0px; text-align: right;">
      - Amin Maalouf
    </p>
   </quote>
   <hr style="color:gray;background-color:gray;width:50%">
   <br>


   <p align="justify">
   According to Amin Maalouf, if the attitude of the people has changes towards women, it must be felt in the medias. We are then going to observe the women representation in the media over the time, starting with the quote distribution over men and women.
   </p>
<br>
   <h3> Which percentage of the quotes are women's and which percentage are men's? </h3>
  
   <section style = "magin-left: -25%; magin-right: -25%;">
    <article1>
      <p>
       <figure>
        <img style="float: right;" src="/images/Percentage_global_gender.png">
        <figcaption>Percentage of representation in the media in terms of number of occurrences, for men and women per year.</figcaption>
       </figure>
      </p>
    </article1>
    
    <article2>
      <p align="justify" style="margin: 0px;">
      With a simple look of the data, we can see very clearly that even though feminist events have occurred, the difference in terms of repartition of the representation is still huge. Indeed, in our timelapse, the repartition of occurrences of speak between women and men stays on a base of 20% against 80%.
     However, the one-sided proportion z-test between 2015 and 2020 (p-value = 4.814710546166949e-96) seems to indicate that there is indeed an increase in the coverage of the women over the five years of our dataset.
     </p >
    </article2>
  </section>
	 
<br>

  <p align="justify">
   But how is this difference in terms of number of occurrences between men and women explained? Does this mean that <b>each man is on average more quoted than women</b> or <b>more men are quoted</b>?
  </p>
<br>
  <h3> How many quotations per individual? </h3>
  <h4> Major part of the population </h4>
  <p>
  <img class="center" src="/images/without_outliers.png" width=700px>
  </p>
  <p align="justify">
  Our graph doesn't show a strict difference between the median of the number of quotations per men and per women. However, the results of our one-sided Welch's t-test on the mean seem to say that there is a difference in occurrences between men and women in our data (before performing the t-test, we removed the outliers of the data by using the z-score criterion) :
  </p>
<br>
  <p></p>
  
  <table align="center" border="1">
     <tr>
       <th>Year</th>
       <th>Statistic</th>
       <th>Pvalue</th>
     </tr>
       <th>2015</th>
       <td>19.569733843712896</td>
       <td>1.8691937970370853e-85</td>
     <tr>
       <th>2016</th>
       <td>9.024466513426889</td>
       <td>9.210044610668905e-20</td>
     </tr>
       <th>2017</th>
       <td>22.425390108058973</td>
       <td>1.6051051507580176e-111</td>
     <tr>
       <th>2018</th>
       <td>21.09033178067998</td>
       <td>6.335574661837446e-99</td>
     </tr>
       <th>2019</th>
       <td>9.94078438864509</td>
       <td>1.410909288072331e-23</td>
     <tr>
       <th>2020</th>
       <td>7.716828059587249</td>
       <td>6.048150213898528e-15</td>
     </tr>
  </table>
  
<br>
<p align="justify">
  We can conclude from our results that, on average, a man is more often quoted than a woman. 
  </p>
<br>
  <h4> 100 more represented speakers </h4>

<br>

  <table align="center" border="1">
    <tr>
      <th>Year</th>
      <th>2015</th>
      <th>2016</th>
      <th>2017</th>
      <th>2018</th>
      <th>2019</th>
      <th>2020</th>
    </tr>
      <th>Number women</th>
      <td>12</td>
      <td>11</td>
      <td>15</td>
      <td>17</td>
      <td>19</td>
      <td>18</td>
    <tr>
     <th>Number men</th>
      <td>88</td>
      <td>89</td>
      <td>85</td>
      <td>83</td>
      <td>81</td>
      <td>82</td>
    </tr>
      <th>Proportion of women occurrences</th>
      <td>11%</td>
      <td>14%</td>
      <td>14%</td>
      <td>13%</td>
      <td>17%</td>
      <td>14%</td>
  </table>
  
  <br>

  <p align="justify">
  The number of women in the top 100 most quoted persons in our dataset doesn't seem to increase a lot over the last five years. 
  </p>
  <br>
<head>
    <title>QNimate Slider</title>
     <link href="/assets/css/beautifuljekyll.css" >
</head>
  
   <!-- Slideshow container -->
   <div class="slideshow-container">

   <!-- Full-width images with number and caption text -->
   <div class="mySlides fade">
       <div class="numbertext">1 / 6</div>
       <img src="/images/2015.PNG" style="width:100%">
       <div class="text">2015</div>
   </div>

   <div class="mySlides fade">
       <div class="numbertext">2 / 6</div>
       <img src="/images/2016.PNG" style="width:100%">
       <div class="text">2016</div>
   </div>

   <div class="mySlides fade">
       <div class="numbertext">3 / 6</div>
       <img src="/images/2017.PNG" style="width:100%">
       <div class="text">2017</div>
   </div>

   <div class="mySlides fade">
       <div class="numbertext">4 / 6</div>
       <img src="/images/2018.PNG" style="width:100%">
       <div class="text">2018</div>
   </div>

   <div class="mySlides fade">
       <div class="numbertext">5 / 6</div>
       <img src="/images/2019.PNG" style="width:100%">
       <div class="text">2019</div>
   </div>

   <div class="mySlides fade">
       <div class="numbertext">6 / 6</div>
       <img src="/images/2020.PNG" style="width:100%">
       <div class="text">2020</div>
   </div>

     <!-- Next and previous buttons -->
     <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
     <a class="next" onclick="plusSlides(1)">&#10095;</a>
   </div>
   <br>

   <!-- The dots/circles -->
   <div style="text-align:center">
     <span class="dot" onclick="currentSlide(1)"></span>
     <span class="dot" onclick="currentSlide(2)"></span>
     <span class="dot" onclick="currentSlide(3)"></span>
     <span class="dot" onclick="currentSlide(4)"></span>
     <span class="dot" onclick="currentSlide(5)"></span>
     <span class="dot" onclick="currentSlide(6)"></span>
   </div>                                                                                          
  <br>
  <p align="justify">
  Among the top 3 most quoted people in our dataset over the years, only two of them are women, Hillary Clinton and Nancy Pelosi. They are both politicians. 
  On the other hand, in this top 3, some of the men are company directors. We even find a football trainer. Which leads to the question: are men and women equally quoted on all topics or is there a gender-based discrimination on the topics? 
  </p>                                                                                       
                                                                                       
<br>                                                                                    
  <h3> How many different men are quoted in the dataset? </h3>

<br>
	 
<section style = "magin-left: -25%; magin-right: -25%;">
    <article1>
      <p>
       <figure>
        <img style="float: right;" src="/images/Percentage_global_peok.png">
        <figcaption>Percentage of representation in the media in terms of number of quotes, for men and women per year.</figcaption>
       </figure>
      </p>
    </article1>
    
    <article2>
      <p align="justify" style="margin: 0px;">
      According to our graph, men represent 80% of the quoted person whereas women represent only 20%. This repartition doesn't change over time.
  We can conclude that the difference in terms of number of men against women is the key to explain the first graph we obtained.
     </p >
    </article2>
  </section>
  
<br>
  
  <h3> Are these people different in terms of age?</h3>
	 
<br>
  <p>
  <img class="center" src="/images/age_repartition_hist.png" width=700px>
  </p>
<br>
  <p align="justify">
  According to our graph, in terms of percentage, women are more represented when they are young than when they are old, and it is kind of the opposite for men. 
  The one-sided t-test (p-value = 3,15e-46) proves that there is a statistically significant difference between the mean of the age of alive men and women. 
  </p>

  <p align="justify">
  The curious thing about the dead people that are quoted is that the repartition men /women is close to the same as today, the men are quoted approximately three to four times more than women!
  </p>
<br> 
  <h3> Conclusion</h3>
  <p align="justify">
  Our graphs and tests seem to indicate that women are less quoted in the media, and when a woman is quoted, she is on average less quoted than a man. Moreover, even though we have a statistically significant augmentation in the proportion of occurrences of women in our dataset, this augmentation is really small.  
  We can then conclude that even though many feminist events have occurred in the last five years, we don't clearly see the effect of these events now. 
  Indeed, women are still in a state of withdrawal compared to men. They are less present on the public scene, and when they are, the media coverage is smaller. But maybe it will happen with a delay?
  </p>
<br>
<br>
  <h1> Inequal representation in the media in terms of profession </h1>
	 
<br>

 <table align="center" style="margin-left: -25%; margin-right: -25%; background-color: white;">
    <tr>
      <td><img src="/images/occ_female_2015.png" style="height: 300px"></td>
      <td><img src="/images/occ_male_2015.png" style="height:300px"></td>
</tr>
      <td><img src="/images/occ_female_2020.png" style="height:300px"></td>
      <td><img src="/images/occ_male_2020.png" style="height:300px"></td>
 </table>

<br> 
	
<ul>
 <li> Sports: athletes </li>
 <li> Arts: painter, musicians, compositors, writers, actors, models... </li>
 <li> Politics: minister, president, head of government... </li>
 <li> Science and technology: physicien, computer scientists, health professional, researcher, engineer, technician... </li>
 <li> Religion: clergy... </li>
 <li> Armed forces: soldiers... </li>
 <li> Civil service: diplomat, public employee, activist... </li>
 <li> Legal professionals: jurist, lawyers... </li>
 <li> Manual work: artisan... </li>
 <li> Education & studies: teacher, academic professional... </li>
 <li> Business: entrepreneur, manager, executive... </li>
</ul>
<p align="justify">
 According to our graph, the three most represented occupation fields are sports, arts and politics. 
	
 In 2015, most of the quoted women work in the field of:
<ol> 
	<li>Art</li>
	<li>Politique</li>
 <li>Sport</li>
</ol>
 In 2015, most of the quoted men work in the field of: 
 <ol> 
	<li>Sport</li>
	<li>Politique</li>
 <li>Art</li>
</ol>
	 </p>
<p align="justify">
Between 2015 and 2020, the proportion of quoted women in politics has increased, and the same proportion in arts has decreased. The same pattern can be observed for men, the proportion of men in politics increases, whereas the proportion in sports decreases. 
	<ul>
		<li> Because of COVID, sport and art events have been canceled, so the mediatic coverage focus on someting else, like, for example the pandemic or the management of the crisis </li>
		<li> The election of the new president was taking place</li>
	</ul>
We could also suppose that more space was available for women in politic. 
</p>
<br>	
  <h3> Women in sport: </h3>
  <p align="justify"> 
  According to the Olympic CIO report on <a href="https://olympics.com/cio/news/le-nombre-de-femmes-et-de-jeunes-membres-des-commissions-du-cio-atteint-un-niveau-record">Tokyo2021</a> , men and women are equally represented. Women represent 49% of the athletes against 34% in 1996. Moreover, in 2016, more than half of the american team was feminine.
  We could then conclude that media chooses to represent more regularly men than women. 
  </p >
  
  <br>
  
  <section style = "magin-left: -25%; magin-right: -25%;">
    <article1>
      <p>
       <figure>
        <img style="float: right;" src="/images/percentage_per_occ.png">
        <figcaption></figcaption>
       </figure>
      </p>
    </article1>
    
    <article2>
      <p align="justify" style="margin: 0px;">
      On this graph we can see that on the topics that are more traditionally reserved to men, like the army, sciences or manual work, men represent the great majority, whereas on topics like arts, civil service or education, women are more represented.
Either women are less represented in the army or manual work field (the dataset doesn't give us any information about that) or there is a gender-based discrimination.
     </p >
    </article2>
  </section>
  
<br>
<br>
<br>
<br>
<br>
<p align="justify"> 
<img class="center" src="/images/heatmap.png" width = "700">
</p>
<p align="justify">
Then, we made heat-maps to visualise the occupations according to the age for women and men. On these graphs, the brighter it is, the more speakers there are. Therefore, as we can see on women's graphs, there is a lighter area for younger artistic women and for older political women. On men's graphs, we can see a light area on younger sportive men and on older political men. These findings confirm the results that we got previously, i.e. the top 3 occupations for men and women and the age distributions.
As a conclusion, we can say that : 
<ul>
	<li> Younger women are more quoted that older women </li>
	<li> Women in arts and politics are more represented than women in other occupation fields. </li>
	<li> Older men are more represented, most of them are politicians.</li>
</ul>	
Therefore, women and men are not equally represented by age and by occupations.
</p>	
<br>
 <h1> Inequal representation in the media in terms of political orientation </h1>
 <br>
 <hr style="color:gray;background-color:gray;width:50%">
 <quote class="center">
  <p style="margin: 0px;">
   <i>"No one respects women more than I do."</i>
  </p>
  <p style="margin: 0px; text-align: right;">
      - Donald Trump
  </p>
 </quote>
 <hr style="color:gray;background-color:gray;width:50%">


 <p align="justify">
	Indeed, after finding this quote from Donald Trump, we asked ourselves if the political orientation of the speakers correlates with women's representation in the media. Therefore, we sorted all the existing parties in our data set by the women's percentage, starting with the party with the biggest women proportion. Thus, we can see on these graphs the "10 best parties" according to women's proportion. 
We can see that the parties that have the most women among their members are mostly democratic and social parties opposed to the conservative and republican parties, that contain the least women. 
Therefore, we can see a link between the political orientation and women's representation.
 </p>
 <p>
 <img class="center" src="/images/politic_ten_bigger_group.png">
 </p>
<br>
 <h1>Emotionnal context of the quotes</h1> 
 <img class="center" src="/images/pie_sentiment.png" width = "500">

<br>
 <p align="justify"> 
 We want to find here the sentiment with which a person is quoted, or the feeling that the author of the article gives when citing a person. Thus, we use <a href="https://github.com/cjhutto/vaderSentiment">VADER</a>, <i>a lexicon and rule-based sentiment analysis tool<\i> capable of classifying text in three sentiment categories: a negative, a neutral and a positive one.
The following pie graphics show that throughout the years, the sentiment of the context in which people are quoted in the media stays the same. Around 60 % of the quotes are cited in a positive way, 25% in a negative way, and 15% in a neutral way. Furthermore, these percentages of sentimental contexts are globally the same for women and men.
	
	Finally, we can conclude that it seems that women are not quoted more or less negatively or positively than men. Thus, it may not play an important role in women's representation  in the media
</p>
  
 </body>
</html>

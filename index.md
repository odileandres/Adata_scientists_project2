---
layout: page
title: Society Vs media
subtitle: Men and women, equals in the eyes of the media?
cover-img: /images/Odile2.png
---
<html>
 <body>
   <img class="center" src="/images/6ibbh0oB4OGAGZm4PSuBh9.jpg">

   <p align="justify">
    Ever since 2007, <i>#MeToo</i> has been trending on social media, especially after the Weinstein gate in 2017. Since then, the debate around inequalities between men and women has been a burning subject. Organized sexual exploitation of young women, like the gate of Jeffrey Epstein, inequalities, trivialized sexism, sexual harassment, consent, all have been on the headline of the journals and have triggered massive demonstrations all over the world. 
   And the media are not innocent in this social discrimination.
   Indeed, according to research pursued by the  <a href="https://beijing20.unwomen.org/en/in-focus/media">UNWomen</a> over more than 100 countries, sexism in the media nowadays is striking. In terms of managing positions, men still represent 73% of the top media management position, according to another study gathering 522 news media organizations. Moreover, about 46% of news stories spread gender stereotypes and only 6% promote gender equality. 
   </p>
 
   <h2> Goal: </h2>
   <p align="justify">
   In our analysis, we want to see whether the feminist movements from the last years had any significal impact on the representation of women in the media. 
   </p>
   <p align="justify">
   <b> <i> In other words, are women more represented nowadays than before 2015, are they represented in all the fields at the same level of men and is there still a discrimination based on age against women?</i> </b>
   </p>
 
   <h1> Inequal representation in the media in terms of coverage </h1>
  
   <quote>
   <p>
   <i>"The media reflects what the people say, the people reflect what the media says. Will we never tire of this mind-numbing game of mirrors?"</i>
   Amin Maalouf
   </p>
   </quote>

   <p align="justify">
   According to Amin Maalouf, if the attitude of the people has changes towards women, it must be felt in the medias. We are then going to observe the women representation in the media over the time, starting with the quote distribution over men and women.
   </p>

   <h3> Which percentage of the quotes are women's and which percentage men's? </h3>

   <img style="float: right;" src="/images/Percentage_global_gender.png">

   <p align="justify">
   With a simple look of the data, we can see very clearly that even though feminist events have occurred, the difference in terms of repartition of the representation is still huge. Indeed, in our timelapse, the repartition of occurrences of speak between women and man stays on a base of 20% against 80%.
However, the one-sided proportion z-test between 2015 and 2020 (p value = 4.814710546166949e-96) seems to indicate that there is indeed an increase in the coverage of the women over the five years of our dataset.
  </p >

  <p align="justify">
   But how is this difference in terms of number of occurence between men and women explained? Does this mean that <b>each man is on average more quoted than women</b> or <b>more men are quoted</b>?
  </p>

  <h3> How many quotation per individual? </h3>
  <h4> Major part of the population </h4>
  <img style="float: right;" src="/images/without_outliers.png">
  <p align="justify">
  Our graph doesn't show a strict difference between the median of the number of quotation per men and per women. However, the results of our one-sided ttest on the mean seem to say that there is a difference in occurence between men and women in our data (before performing the ttest, we removed the outliers of the data before the ttest by using the z-score criteria.):
  </p>

  <table align="center" border="1">
     <tr>
       <th>Year</th>
       <th>Statistic</th>
       <th>Pvalue</th>
     </tr>
       <th>2015</th>
       <td>16.08176125715461</td>
       <td>3.6750044860932176e-58</td>
     <tr>
       <th>2016</th>
       <td>8.350871052699866</td>
       <td>6.818369664447138e-17</td>
     </tr>
       <th>2017</th>
       <td>17.093578892657032</td>
       <td>1.8036016596622786e-65</td>
     <tr>
       <th>2018</th>
       <td>15.615830479171223</td>
       <td>6.0237859790679365e-55</td>
     </tr>
       <th>2019</th>
       <td>8.38377359026447</td>
       <td>5.154347860572652e-17</td>
     <tr>
       <th>2020</th>
       <td>6.436874220134217</td>
       <td>1.2243967841933978e-10</td>
     </tr>
  </table>


  <h4> 100 more represented speakers </h4>

  <head>
    <title>100 more represented speakers</title>
  </head>

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

  </table>

  <p align="justify">
  The number of women in the 100 more quoted person in our datset  doesn't seem to increase a lot over the last five years. 
  </p>
  
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
                                                                                         
                                                                                       
                                                                                         
  <h3> How many different men are quoted in the dataset? </h3>
  <img style="float: right;" src="/images/Percentage_global_peok.png">

  <p align="justify">
  According to our graph, men represent 80% of the quoted person whereas women represent only 20%. This repartition doesn't change over time.
  We can conclude that the difference in terms of number of men against women is the key to explain the first graph we obtain.
  </p>

  <h3> Are these people different in term of age?</h3>
  <img style="float: right;" src="/images/age_repartition_hist.png">

  <p align="justify">
  According to our graph, in terms of percentage, women are more represented when they are young than when they are old, and it is kind of the opposite for men. 
  There is indeed a statistically significant difference between the mean of the age of alive men and women(pvalue=  ) .
  </p>

  <p align="justify">
  The curious thing about the dead people that are quoted is that the repartition men /women is close to the same as today, the men are quoted approximately three to four times more than women!
  </p>

  <h3> Conclusion</h3>
  <p align="justify">
  We can then conclude that even though many feminist events have occurred in the last five years, we don't see the effect of these events now. 
  Indeed, over five years, the women are in a state of withdrawal compared to men. They are less present on the public scene, and when they are, the media coverage is smaller. But maybe it will happen with a delay?
  </p>

  <h2> Inequal representation in the media in terms of subject </h2>

  <div class="clearfix" align="center">
    <div class="img-container">
    <img src="/images/occ_female_2015.png" style="height: 300px">
    </div>
    <div class="img-container" style="float: right;">
    <img src="/images/occ_male_2015.png" style="height:300px">
    </div>
  </div>

  <div class="clearfix">
    <div class="img-container">
    <img src="/images/occ_female_2020.png" style="height:300px">
    </div>
    <div class="img-container" style="float: right;">
    <img src="/images/occ_male_2020.png" style="height:300px">
    </div>
  </div>

  <p align="justify">
  According to our graph, men and women are not quoted for the same subjects. Indeed, men are more represented in the field of sport, whereas art is dominant in women's topic. 
  <\p >
 
  <h3> Women in sport: </h3>
  <p align="justify"> 
  According to the Olympic CIO report on <a href="https://olympics.com/cio/news/le-nombre-de-femmes-et-de-jeunes-membres-des-commissions-du-cio-atteint-un-niveau-record">Tokyo2021<\a> , men and women are equally represented. Women represent 49% of the athletes against 34% in 1996. Moreover, in 2016, more than the half of the amercian theme was feminin.
  We could then conclude that media choose to represent more regularly men than women. 
  <\p >
 
 <h3> Men in arts:</h3>
 <p align="justify"> 
  According to our graph, the proportion of men quoted on the subject of art is smaller than the proportion of women. However, according to an article from T <a href="https://www.theguardian.com/culture/2018/apr/16/arts-industry-report-asks-where-are-all-the-working-class-people">The Guardian</a>, white-men are the best paid people in 
 <\p > 

 <h2> Inequal representation in the media in terms of political orientation </h2>
 <quote> 
 <p> <i>"No one respects women more than I do."</i> 
 Donald Trump </p>
 </quote>

 <p> We chose to only work on the ten </p>
<img style="float: right;" src="/images/politic_ten_bigger_group.png">
 
 </body>
</html>

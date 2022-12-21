---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 80%;"
    src="images/social-media-politics.jpg" 
    alt="tilte image">


<!--- <h1 style="text-align: center;">US Media polarization on YouTube</h1> -->

## Introduction

In 2017, with the arrival in power of Donald Trump as president of the United States, the American political world quickly split between the pro and anti-Trump. According to a [study][1] lead by Jesse M. Shapiro, Brown University, this polarization began in the late 1990s and early 2000s and has been only increasing since, promoted by the detrimental properties of the US voting system that incentivize people to become radical. This polarization is also reflected online: according to a [study][2] on Facebook lead by to Brazilian researcher, the polarization one year after the 2017 election can be pictured on the figure below. Can the same effect be measured on YouTube communities ? In this data story, we will analyze the profiles of political communities on YouTube.

## YouTube is more ubiquitous than you think

Donner des data sur YouTube:
- autant de vues sur YT que de recherches sur Google
- proportion de gens qui regardent YT
- YT is used more and more to get news (even more for young generations) and unlike traditional medias, information is much less controlled
- Algorithm that promotes content that works and that might enclose people in filter bubbles




## Research Question

Talk about dataset
 
From milestone 2:

*   Can we identify communities inside the main US News&Politics channels ? Is there a clear left-right polarization or is the polarization independent of classical political party confrontation ?
*   What is the distribution of users polarization? Is it Gaussian? How many very extreme users do we see? For this purpose, we will assign a p-score (polarization or political score) to users
*   Based on the communities identified, can we describe political orientation of audience of non-News&Politics channels ? Study a few particular «neutral» channels (ex : Education, Gaming, Comedy Channels ...) or marginal channels (Flat Earth Society) and analyze their audience and their links with news channels
*   How are main political events treated by channels in different communities ? Study various events by filtering by tags, descriptions or video titles that contains key words, for example "US Election", "Impeachment", "Hunter Biden", "Capitol".



<!--- <img src="images/fb_us_pol.png" alt="fb_us_pol" width="700" style="display: block; margin-left: auto;margin-right: auto"/> -->

<!--- *Complete disconnexion of political landscape. Pablo Ortellado and Marcio Moretto Ribeiro, CC BY* -->

* * *
## 

The way of consuming the news has not stopped evolving over time. With the invention of the printing press, the world of information has been considerably changed. Then the news, transmitted more and more quickly with the development of the radio, the information has then changed its face to become more widespread and entertaining with the arrival of television in households. Finally, since the creation of the Internet, much information is transmitted through this channel. Today, about 40% of Americans get news online. It is even the number one source of information for the 18-45 age group. With the development of social networks, more and more people are getting information online and this also raises more and more questions.

<a href="https://www.statista.com/statistics/717651/most-popular-news-platforms/" rel="nofollow"><img src="https://www.statista.com/graphic/1/717651/most-popular-news-platforms.jpg" alt="Statistic: Most popular platforms for daily news consumption in the United States as of February 2022, by age group | Statista" style="width: 100%; height: auto !important; max-width:1000px;-ms-interpolation-mode: bicubic;"/></a><br />Find more statistics at  <a href="https://www.statista.com" rel="nofollow">Statista</a>

In the social media family, after Facebbok, YouTube is the second website where people get most of their news. In 2020, almost one in four people (23%) regulary get news on YouTube.


https://www.pewresearch.org/journalism/2021/01/12/news-use-across-social-media-platforms-in-2020/pj_2021-01-12_news-social-media_0-02/

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 100%;"
    src="images/sources_of_news.png" 
    alt="Sources of news on social media">



{% include /figures/overall_categories_evolution.html %}

{% include /figures/2019_category_evolution.html %}

## Importance of news & Politics Channels on Youtube

{% include /figures/news_pol_3pie_overview.html max-width="600px" %}
* * *
## Polatization

{% include /figures/heatmap_comunity_w_hover.html %}



```python
1 + 1 # Adding two numbers
```

## Polatization

{% include /figures/heatmap_comunity_w_hover.html %}


* * *
## Polarization of Youtube users

{% include /figures/p-score.html %}



[1]: https://www.nber.org/papers/w2666
[2]: https://theconversation.com/mapping-brazils-political-polarization-online-96434

---
Title: Laddningstid
Description: En analys av läddningstid
# hidden: true
---


Loading time analysis
=======================

Loading speed is the focus of this analysis. It investigates the loading time and PageSpeed Insights score of three websites that I often use.


Urval
-----------------------

These 3 sites are the most common in my browsing history. These are korean google-alike website naver, duckduckgo (search engine) and hackernoon (an open community for technologists).

Metod
-----------------------

I run a scan of my browsing history in browser and selected three websites that I daily visit. I then copied the links into Firefox developer edition, opened additional views of these sites in the same browser. In a spreadsheet (google docs) a table for the page locations, their PageSpeed Insights scores and loading speed in DevTools is created. I then run all these pages through these tools and record the scores.

Resultat
-----------------------
<br>

See the collected data spreadsheet 

<iframe title="My google doc" height="200px" width="100%" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR3MzkDE9V6muqJd2MbMZl3ydue_UsbJzO7CyKmGGAKsH7rgTxlOu5cX22EdLJu3qyBvhyZ-7w5Bpxz/pubhtml?widget=true&amp;headers=false"></iframe>

Duckduckgo
-----------------------
<br>

<img src="../assets/img/duckduck.png" alt="" width="700" height="300">

<br>

Improvement suggestions:
<ul>
<li>Remove unused Javascript</li>
</ul>

Hackernoon
-----------------------

<br>
<img src="../assets/img/hackers.png" alt="" width="700" height="300">
<br>

Improvement suggestions:
<ul>
<li>Remove unused Javascript</li>
<li>Use images of the correct size</li>
<li>Use videoformat for animations</li>
</ul>


Naver
-----------------------

<br>
<br>
<img src="../assets/img/naver.png" alt="" width="700" height="300">
<br>

Improvement suggestions:
<ul>
<li>Send images in modern image format (webP and avif)</li>
<li>Reduce server response time</li>
<li>Encode images efficiently</li>
<li>Remove resources that block rendering</li>
</ul>


Analys
-----------------------

According to the results, it seems to be that content-heavy sites (by number of resources loaded) take longer time to load as expected. However when viewing the PageInsight suggestions for improvement reducing the content is however not suggested. The suggestions seem to touch upon some aspects - the page code (suggestions to remove unused code, using images of correct size for example), server response time and the order in which items render (eliminate render blocking resources or defer offscreen images). I suggest that those below are the three main strategies for improving site loading speed:
<ul>
<li>Optimize content</li>
<li>Optimize code</li>
<li>Control the rendering of the page</li>
</ul>
<br>
<b>Duckduckgo.com</b> has the best PageInsights scores (both on desktop and on mobile) and it also delivers high loading speeds and is pronounced the winner of this test.
<br>

My general experience of the sites (in regards to loading times) seems to correlate to the values derived in this test. The two pages that I identify as slowest have wildly ranging values in loading time - 2.55s and 8.25s. And the page that I deem to be the fastest is in fact the fastest. On average I find all of the sites except Hackernoon which is content-heavy as it uses several images, json files etc on the home page, relatively fast. Hackernoon is thus perceived as below average slow. 


Referenser
-----------------------

Webbsidor:

https://developers.google.com/speed/pagespeed/insights/ [2021-12-05]

https://www.mozilla.org/sv-SE/firefox/developer/ [2021-11-28]

https://developers.google.com/speed/docs/insights/v5/get-started [2021-12-05]



Övrigt
-----------------------

Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten.
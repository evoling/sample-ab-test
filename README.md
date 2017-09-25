# Simple A/B testing for linguistic experiments

In online experiments we often want to dispatch participants randomly to different versions of an test or questionnaire. One simple way to achieve this is to make two different versions of the experiment using Google Forms or something similar, and then use a start page website which randomly selects which of the two to send each person to. Making the start page is very simple: it requires copying and customising a snippet of html code with a tiny bit of javascript.

A free and simple way to make and host the website is with [Github Pages](https://pages.github.com/). It only takes a few minutes. The steps are as follows:

- Make a GitHub account on https://github.com
- Follow the instructions for making a GitHub Pages website on https://pages.github.com/
- Copy and customise the html code from the [index.html](./index.html) file in this repository to the index.html file you created in your new repository. You need to replace the urls in this file with the urls for your different versions of the experiment. You will also want to put in some appropriate introductory text to be displayed to the user.

If my username is **evolang** and my repository is called **sample-ab-test**, then the repository url will be https://github.com/evoling/sample-ab-test/ and the automatically generated webpage will be https://evoling.github.io/sample-ab-test/.

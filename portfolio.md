# Portfolio
* Tech Projects:
  * [Binarized Neural Networks](#binarized-neural-networks)
* Tech Projects on the Web:
  * [Fantasy Twitter](#fantasy-twitter)
  * [Candivote](#candivote)
  * [TI-Nspire Program Repository](#ti-nspire-program-repository)
* Graphic Design Work:
  * [IAPA DUG logo for Brown University](#iapa-dug-logo-for-brown-university)

----
# Tech Projects
* [Binarized Neural Networks](#binarized-neural-networks)

## _Binarized Neural Networks_
* Tech Stack: TensorFlow, TFLite, Keras, Larq, Python, Google Colab
* Colab Notebook: https://colab.research.google.com/drive/134v2cLDpJmyAAC5no365x9ibZGZXgEDn?usp=sharing

This was an original final project for CS 1470 where I worked with [arvindsridhar1](https://github.com/arvindsridhar1) to design an experiment comparing the accuracy and memory usage of binarized neural networks (BNNs) versus their full-precision counterparts. I wrote all of the code in the Colab notebook to carry out our experimental design. In doing so, I became better at best practices of using TensorFlow and Keras for creating neural networks. I used the TFLite Analyzer to compare serialized model file size to assess memory usage. I also deepened my understanding of BNNs (networks where all the weights and activations are either 1 or -1) by using the Larq library to implement them.

<br />

![A project poster detailing the design and results of our experiment comparing BNNs to standard, full-precision networks](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/767/219/datas/original.jpg)

----
# Tech Projects on the Web
* [Fantasy Twitter](#fantasy-twitter)
* [Candivote](#candivote)
* [TI-Nspire Program Repository](#ti-nspire-program-repository)

## _Fantasy Twitter_
* Tech Stack: Firebase (Realtime Database & Hosting), React, Python, Heroku, Twitter API v2
* Website link: https://fantasy-twitter.web.app
* GitHub repo: https://github.com/N-Masi/fantasy-twitter

Fantasy Twitter is Twitter turned into a fantasy sport. Users create accounts that are managed and kept secure with Firebase, and from there they can compete against other users in weekly matchups to have their teams get the most points. Teams are collections of Twitter accounts, where engagement on accounts' tweets that week (e.g., likes, replies, retweets) earns points. A Python script running on Heroku gets live data from the Twitter API every night to calculate scores and then updates a Firebase Realtime Database. Users can sign in to their accounts on the Firebase hosted website to check how their teams are doing; the React frontend displays data from the Realtime Database.

This project was first worked on as an original group final project for CS 320 alongside four other developers (Jeffrey Dai, Ben Duong, India Gold-Coren, and Grace Dorantes). After I came up with and brought the project idea to the group, we worked together to build it guided by stakeholder feedback. Through this I learned how to work as a part of a team of developers using GitHub for version control, Trello for task assignment and division of labor, and agile practices where we worked in sprints and built functionality around user stories. My contributions to the project were: updating our database with info from Twitter API calls via a Python script, displaying the appropriate data on the frontend for a signed in user, refactoring React class components into functional components, and creating the game design and algorithms. Since the conclusion of the class I have continued to develop the website by myself where I deployed the Python script to Heroku, improved the frontend UI, and fleshed out the backend to take it from a class project to a functioning website.

## _Candivote_
* Tech Stack: React, Cloud Firestore
* Website link: https://dev.candivote.org/dashboard
* GitHub repo: private :(

Candivote is a platform for improving local politics by helping inform constituents on candidates' policies before voting. My contributions were primarily frontend, where I developed the whole dashboard using React and Material UI Kit to display live politician data from our Firestore database. Backend help from [luciengaitskell](https://github.com/luciengaitskell).

## _TI-Nspire Program Repository_
* Tech Stack: TI-Basic, HTML, GitHub Pages
* Website link: https://n-masi.github.io/
* GitHub repo: https://github.com/N-Masi/N-Masi.github.io

This website hosts a repository of programs that I made for the TI-Nspire series of calculators. Programs are meant to help students extend the functionality of their calculators in the domains of statistics, geometry, and physics. The website contains instructions for getting the programs onto one's calculator to help the 100's of students who have visited the site.

----
# Graphic Design Work
* [IAPA DUG logo for Brown University](#iapa-dug-logo-for-brown-university)

## _IAPA DUG logo for Brown University_
<img src="https://ci4.googleusercontent.com/proxy/A7z_qdyYRAU2W1c5sLi2HkJGlrXAnB8JgjzKpLdIVwItiGM7JGz5S4731hTekc6LJBvcdb0RVwj2O40BRUv6gRJWIGPEbXA_glTTcQpHJALV7e52uMwDXo07I1VKydf9EqTR7JR5MPWoScozU-axDI5Ck2TYXw=s0-d-e1-ft#https://mcusercontent.com/81743a55a6757cf1787ec536c/images/be0db7b6-c5a2-44ae-91b9-4a537ad29f44.png" alt="IAPA in bold red letters, stylized with I and A on top and P and A on bottom forming a trapezoid" width="200" height="250" />
USE: Branding of the Departmental Undergraduate Group for the International and Public Affairs major at Brown University.

DESIGN NOTES: Inspired by the logos of the Institute's previous and now deprecated majors.

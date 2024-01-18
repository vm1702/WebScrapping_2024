# Ciné Zodiaque  

## WebScrapping Project 2024 - HIEN Victor - LUTTENBACHER Léa - MENU Victor

Hello and welcome to this repository, which aims to present our WebScrapping project: Ciné Zodiaque.  

  Nous vous invitons également à regarder notre vidéo pour voir notre site !  
  
To help you understand this rendering, here are the various indications to follow:

## Context and project
#### Context
Since the early 2000s, the company has been part of a major digital transformation in many sectors. The video-entertainment world is far from being excluded, and the art of cinema has been able to adapt and evolve to meet the new challenges it brings. The result today is the presence of cinema on numerous media and platforms, whether still physically in cinemas or on streaming platforms such as Netflix or Disney+.  
However, despite all its innovations and additions for a better user experience, one problem persists, and has surely already been experienced by each and every one of us: choosing a film. Although the personalization and suggestions offered by streaming sites are relevant, it's complicated to find out about a neutral, global base of films that brings together all the different criteria.  
Review and rating sites already exist, and offer a rating and classification system, but these scores are biased and often unrepresentative, being often too specific and site-specific. What's more, most of the criteria are still very generic, and not well adapted to certain specific consumer expectations, particularly with regard to RSE.  
With regard to these criteria, we have chosen to focus on two RSE issues, in line with our values, and which meet two needs:  
-The cross-cultural dimension of cinema: All too often, cinema tends to be limited to Hollywood films on streaming platforms, reducing the range of choices available to the user. Offering a cross-cultural solution would therefore be a good idea.  
-Civic and ethical commitment to VSS (Sexist and Sexual Violence): With the many controversies, scandals and court cases that have been taking place over the years, the press has brought to light a problem that is too often hushed up within the film industry: the subject of SGBV in the production world. As a result, many people wish to blacklist and not support films produced by people accused of VSS, but are not aware of this on streaming platforms, which is a need.

#### Project introduction
To address these issues, we decided to create our own movies recommendation site, called Ciné ZoDIAque.  
Ciné ZooDIAque is a site offering an interface listing numerous movies and their main characteristics: Name, Year of release, Genre, Duration, Synopsis, Director, Crew, DIstributor, VSS and Rating (Note_Z who is the mean between the score from differents sites and Note_U who is the mean between the score from differents user feedbacks).  
This information will be scrapped from various film recommendation/selection sites, offering ratings for the films.  
In order to respect the cross-cultural dimension criterion and thus avoid bias, we want to offer an international variety of films, broadening the range of films and opening up to different cultures around the world. To achieve this, our notes will be retrieved from different sites of different origins.  
Then, in order to respect our criteria regarding VSS, we've decided not only to offer a tool for viewing people accused of VSS (and the link to the source), but also to add the possibility of filtering films according to VSS to blacklist films made by people accused of VSS.  
More technically, our site will offer a general interface, a search engine and a film filtering capability.  

## Scrapping
This section is dedicated to the scrapping phase and contains all the information on this subject, the methodology used, the sites scrapped and the difficulties encountered during the scrapping process.  
We invite you to read it in the document "WebScrapping_CineZoDIAque_HIEN_LUTTENBACHER_MENU.html" (and "WebScrapping_CineZoDIAque_HIEN_LUTTENBACHER_MENU.ipynb" for its code version).  
All the information is detailed inside, and will help you understand how we arrived at our final dataset.

## Website
In order to visualize our solution, we decided to create a website (html css javascript) to showcase our Ciné Zodiaque.  
If you'd like to discover it, we invite you to open the "index.html" file, which will take you to the home page.  
The site consists of a "Home" page with general information, a "VSS" page with a list of people accused of VSS and a link to the ESILV SAFE association, and a "Movies" page with all the films and their information, allowing you to search, filter and sort.  
We hope you'll enjoy the site.

## Other
Finally, you'll also find all the csvs grouping the information for each site, the merged csvs (df_movies and df_movies_f) and the vss csv.

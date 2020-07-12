---
layout: page
title: About
permalink: /about/
---

## The rise and fall of personal publication repositories 
The World Wide Web (WWW) system was invented in the early nineties by Tim Berners Lee in order to facilitate the timely distribution of research papers. Presumably, if this vision went through, the WWW would have become an open access digital library of scientific work. Twenty years later, the WWW has mostly transformed into just another advertising and social medium. 

Notably, scholars nowdays do not have to maintain a publications repository, because Google Scholar (and several similar services) mine publishers' meta-data and create personal profile pages. Moreover, there are social media systems for scholars, who can now post, comment, and like publications, like they do for cat videos. Presumably, most scholars consider the qualities of their work similar to dog (trying to be politically correct with regard to cat-dog rights, here) photos.

At the same time, the quantitative aspect of research papers (citations) has become central. In this way, a research paper is now less about the meaning of its content to readers and more about the likes (or links) towards it, regardless of the referral and the source context. In other words, you do not have to read and understand a paper, since an algorithm has allready classified its merit. 

In the light of the above isses, I have realized that the evaluation of research papers and scholars might be even easier than comparing citations. I have found that most scholars follow one or more of the following practices: 1) upload papers in social media for extra likes, 2) do nothing and reside on the infrastructure and policies of their institute or even worse that of a data miner, 3) create manually a list of papers, which becomes dated as soon as they get tenure (and is more recent only by their profile photo). I consider, the last category to be the most honest, while the former ones are not even worth criticizing. 

Finally, you can read a longer analysis of the motivation and broader context of [keeping some ownership of your work achievements](https://scholar.epidro.me/chorianopoulos_2020). In the following section, you will find some indicative links for taking back the ownership of the maintenance of your pubications. 

## Dependencies and workflow
1. The bibliography BibTeX file is a concatenation (consider git submodule!) of the respective files from [my vita repo](https://vita.epidro.me).
2. [jekyll minima](https://github.com/jekyll/minima) theme provides a minimal layout, which you can adapt or change with another jekyll theme
3. [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar) plugin converts the bibliography into basic HTML.
4. [netlify](https://www.netlify.com) builds and deploys the final site.

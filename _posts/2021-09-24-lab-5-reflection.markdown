---
layout: post
title:  "Lab 5 Reflection"
date:   2021-09-24 20:47:53 -0500
categories: lab 5
author: Jacob Newland
---

## Hello everyone!

In this grocery store example, I had to make several assumptions.  Firstly, I assumed that every item had only one manufacturer.  This could turn out not to be true in the case of produce, where say Idaho potatoes from different farms could be mixed together into one basket, but I thought a responsible grocery store would keep track of this in case of recalls.  I also assumed every item had only one name.  This could also turn out to not be true in the case of eggplants/aubergines, but I assumed the tag on the shelf would choose only one of these names instead of both.  I also made the assumption that the grocery store only had one owner instead of several partners splitting ownership.  I assumed only one of the owners would be in charge of listing items.  Below, you can see my entity-relationship diagram
![entity-relationship diagram](/assets/Lab-5-ER-Diagram.png) and my
![SQL Schema.](/assets/Lab-5-SQL-Schema.png)  I'm pretty happy with my data representation, however, I'd prefer to have fewer keys involved.  I thought the customer deserved to have all three columns as primary keys because two people with the same name could live at the same address, such as a father and son named father's name junior, or a married couple with the same first name and last name.  This could fall apart with either of these two scenarios, however, if they share a phone number and each independently sign up as customers, though the chances of this seem slim.  I also made item name, item manufactuer, and price primary keys.  Item price is needed for the order entity, and the other two are necessary for identifying the product.  All of these entities would be easier if they were each assigned an ID number, which would be a much smarter way to implement this.  

<!-- I used this site, http://sgeos.github.io/github/jekyll/2016/08/30/adding_images_and_downloads_to_a_github_pages_jekyll_blog.html and this site, https://www.amitmerchant.com/make-image-clickable-jekyll/, to try to figure out how to add images successfully.  I'm not sure why they still don't work :(  ) -->

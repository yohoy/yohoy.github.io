---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
bigimg: /img/indexbg.jpg
---

# Nutrition and Ecology, are they mutually exclusive?
Nutrition can be a conversial subject.
While taste is relative, the ecological impact of each aliment is not.
This project aims to shed some light to the relationship between nutritional value and ecological impact.
Do we need to compromise between eating healthy and protecting the environment?
To respond to our question, we worked with the [Open Food Facts](https://fr.openfoodfacts.org/ "Open Food Facts Web Page") dataset, which lists food products from all over the world, along with many interesting fields such as their manufacturing places, macronutrients or even packaging.

---

## Nutrition Score
How do we know how "healthy" an aliment is?
There are so many (mis)conceptions about health and food, that it is probably impossible to come up with a single universal response.
Instead of coming up with a personal (hence biased) scale of food healthiness, we decided to look at the french government and their [Nutri-Score](/nutri_score) system.
This ranking system uses simple food characteristics such as their energy, fat, sugar and sodium in order to assess how healthy an aliment is, by attributing it a certain amount of points.
The more points one product has, the least healthy it is considered.
To simplify things even further, the computed points are associated with a letter ranging from A to E, where A represents the best nutritional scores and E represents the worst.
(For more details about the nutri-score, do not hesitate to check out our dedicated [page](/nutri_score).)

We computed the nutri-score for as many products as we could, and we now present the results!

### Nutri-Score Visualisation
Let's take a look at the percentage of grades for different food categories:
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plot.ly/~yohoy/1.embed"></iframe>

We can see that the `Fruits & Vegetables` group has great grades (you can see by hovering over its pie chart that almost 80% of its values are either A's or B's), whereas the `Beverages` group has the worst percentage of E's - which makes sense given the amount of sugar usually found in any beverage other than water. 
We also notice that the `Snacks` group

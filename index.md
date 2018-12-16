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

We computed the nutri-score for as many products as we could (more than half a million), and we now present the results!

### Nutri-Score Visualisation
First, we show the number of elements found for each grade:
<div>
    <a href="https://plot.ly/~yohoy/10/?share_key=rZZXXmaX2NIrtn0YXOrrQr" target="_blank" title="Plot 10" style="display: block; text-align: center;"><img src="https://plot.ly/~yohoy/10.png?share_key=rZZXXmaX2NIrtn0YXOrrQr" alt="Plot 10" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="yohoy:10" sharekey-plotly="rZZXXmaX2NIrtn0YXOrrQr" src="https://plot.ly/embed.js" async></script>
</div>

We see that the most represented grade is D. But more importantly, each grade is significantly represented, therefore we can continue our analysis without worrying about having too much bias in the grades distribution.

Let's now take a look at the percentage of grades for different food categories. You can hover over the pie charts below to find the percentage and number of values in each of the slices.
<iframe width="750" height="650" frameborder="0" scrolling="no" src="//plot.ly/~yohoy/1.embed"></iframe>

We can see that the `Fruits & Vegetables` group has great grades (you can see by hovering over its pie chart that almost 75% of its values are either A's or B's), whereas the `Snacks` group has the worst grades - more than 90% are either E or D. 
We also notice that the `Beverages` and `Fat & Sauces` groups have a significant amount of E's, which makes sense because of all the sugar one is used to find in most sodas or in populas condiment sauces.
Regarding the `Composite` category, we see it is reasonably distributed between the grades, with the exception of E's (not even 1%).
This is due to the difficulty to create a calorical composite meal without any proteins, fibers, fruits, veggies or nuts...



All these observations confort us in the relevance of the Nutri-Score.

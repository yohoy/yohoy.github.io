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

Great! Now we can start exploring the data!

### Nutri-Score Visualisation
Below you can see the distribution of scores in our dataset.
![Scores Distribution](/img/scores_distribution.png)

**todo** add letters ranking and comment the plots

We decided to take a look at the mean score of different food categories such as beverages or snacks in order to get a feeling of their respective "health tendencies".

![Category Scores](/img/mean_category.png)

**todo** comment the plots

<div>
    <a href="https://plot.ly/~yohoy/1/?share_key=as8dcdEPaYUDvVX4spupis" target="_blank" title="Plot 1" style="display: block; text-align: center;"><img src="https://plot.ly/~yohoy/1.png?share_key=as8dcdEPaYUDvVX4spupis" alt="Plot 1" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="yohoy:1" sharekey-plotly="as8dcdEPaYUDvVX4spupis" src="https://plot.ly/embed.js" async></script>
</div>


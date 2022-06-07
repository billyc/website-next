---
title: "Berlin, Germany"
thumbnail: /gallery/berlin_thumb.jpg
layout: scenario

image1:
  image: /gallery/berlin_1.jpg
  caption: "Traffic and Public Transit in Berlin"
  source: "BVG and PTV"

---

Berlin, the capital of Germany, has more than 3 million inhabitants. Together with the people living in the surrounding Brandenburg area, a total population of nearly 6 million people is accounted for in this scenario, which covers an area of 150 x 250 kilometers.

{% include image.html image=page.image1 %}

A first approach for a model of Berlin was started in 2006. The road network used was originally developed by the planning department of the city of Berlin. It consists of more than 10,000 nodes and almost 30,000 links. As the scenario has its focus on the urban area of Berlin, this part of the region is represented with a much higher level of detail and accuracy than Brandenburg. The travel demand was based on intermediary output generated by the so called "Kutter-Model" for Berlin (also known as "Berliner Personenverkehrs-Modell"), an agent-based demand generation model. To speed up computational performance, only a 10% sample of car drivers was simulated, resulting in over 160,000 simulated agents. Due to problems with the input data, the scenario was only in use for a short time.

In 2010, a new scenario for Berlin and its surroundings was created on behalf of the Berlin transit company BVG, together with PTV. This new model is based on extensive survey data for creating a good replication of the travel behaviour in the Berlin area. It also includes the complete public transit services (hundreds of bus lines, dozends of tram lines, trains, subways and even a few ferries). Based on that model, a forecasting model for 2015 was created.
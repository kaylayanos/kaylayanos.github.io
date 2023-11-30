---
layout: essay
type: essay
title: "Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - Design Patterns
  - Software Engineering
---

## The Garden
Design patterns are an essential part of any application. We can think of the application as a whole as a garden with many different plants that represent the different components. Now, the question is, how do you take care of all the different plants, each with different needs? We need a master gardener. In the analogy, the master gardener can be represented as the design pattern. Design patterns are general solutions to common problems that occur during software development. They are more of guidelines or templates to make the application more scalable and maintainable. 

### MVVM
The pattern that I am most exposed to is MVVM which is Model-View-Viewmodel design pattern. In the garden analogy, we can think of the MVVM as the master gardener. The MVVM pattern divides the responsibilities into layers, the model, which can be represented as the soil, the view model, which can be represented by the plants, and the view, which can be represented by the working application. 

### Soil
Just like how before you plant anything, you need to prepare the soil, the model is the layer that prepares the data for the application. It is the place where you store the data and the logic that manipulates the data. The model is the layer that is most exposed to the database. In the context of gardening, the model is the ground that supports the growth of the plants, which the working application.

### Master Gardener
The master gardener is the view model. The view model is the layer that connects the model and the view. It is the layer that is responsible for the communication between the model and the view. It is also the layer that is responsible for the logic of the application. In the context of gardening, the view model is the master gardener that takes care of the plants and the soil.

### Flourishing Plants
The flourishing plants are the view. The view is the layer that is responsible for the user interface. It is the layer that the user interacts with. The plant's only concern is flourishing and not worrying about the intricacies of the soil, just like how in meteor, the user interface pages are typically lightweight and its main focus is displaying the information. In the context of gardening, the view is the flourishing plants that the user sees.
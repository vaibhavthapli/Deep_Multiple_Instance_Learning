# Deep_Multiple_Instance_Learning
<h2>Introduction</h2>
<h3>What is Multiple Instance Learning (MIL)?</h3>
<p>Usually, with supervised learning algorithms, the learner receives labels for a set of instances. In the case of MIL, the learner receives labels for a set of bags, each of which contains a set of instances. The bag is labeled positive if it contains at least one positive instance, and negative if it does not contain any.</p>

<h3>Here’s a breakdown:</h3>
<ul>
  <li>
Instance-Level: In traditional supervised learning, each instance in the dataset is labeled. The model learns by associating input features with corresponding labels.
  </li>
  <li>
Bag-Level: In MIL, the data is organized into bags, and each bag contains multiple instances. However, the labels are provided only for the bags, not the individual instances.
  </li>
</ul>
      <ul><li>A positive bag is labeled positive if at least one instance within the bag is positive.</li>
          <li>A negative bag is labeled negative if all instances within the bag are negative.</li>
      </ul>  
The challenge in MIL is that the model needs to infer the labels of individual instances within the bags based on the bag-level labels, which makes it a more complex problem compared to traditional supervised learning.
<img src=>
<img src=>

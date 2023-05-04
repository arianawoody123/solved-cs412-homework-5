Download Link: https://assignmentchef.com/product/solved-cs412-homework-5
<br>
Suppose we want to predict whether a restaurant is popular based on its price, delivery, and cuisine, and we collected the training data as shown in table 1. Answer the following questions.

Table 1: Training dataset (P – popular, NP – not popular)

<table width="309">

 <tbody>

  <tr>

   <td width="40">ID</td>

   <td width="77">Cuisine</td>

   <td width="49">Price</td>

   <td width="69">Delivery</td>

   <td width="75">Popularity</td>

  </tr>

  <tr>

   <td width="40">1</td>

   <td width="77">Thai</td>

   <td width="49">$$</td>

   <td width="69">Yes</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">2</td>

   <td width="77">Korean</td>

   <td width="49">$$$</td>

   <td width="69">No</td>

   <td width="75">NP</td>

  </tr>

  <tr>

   <td width="40">3</td>

   <td width="77">Thai</td>

   <td width="49">$$</td>

   <td width="69">Yes</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">4</td>

   <td width="77">American</td>

   <td width="49">$</td>

   <td width="69">Yes</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">5</td>

   <td width="77">American</td>

   <td width="49">$</td>

   <td width="69">No</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">6</td>

   <td width="77">Korean</td>

   <td width="49">$$</td>

   <td width="69">No</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">7</td>

   <td width="77">Thai</td>

   <td width="49">$</td>

   <td width="69">Yes</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">8</td>

   <td width="77">Korean</td>

   <td width="49">$$</td>

   <td width="69">Yes</td>

   <td width="75">P</td>

  </tr>

  <tr>

   <td width="40">9</td>

   <td width="77">American</td>

   <td width="49">$$$</td>

   <td width="69">No</td>

   <td width="75">NP</td>

  </tr>

  <tr>

   <td width="40">10</td>

   <td width="77">American</td>

   <td width="49">$</td>

   <td width="69">Yes</td>

   <td width="75">NP</td>

  </tr>

 </tbody>

</table>

1a. Based on the training data, we want to construct a Naive Bayes classifier. (No smoothing is required.) Please estimate the following terms: 1a(i). [4] Pr(Popularity = ‘P’)

1a(ii). [4] Pr(Popularity = ‘NP’)

1a(iii). [4] Pr(Price = ‘$’, Delivery = ‘Yes’ , Cuisine = ‘Korean’ | Popularity = ‘P’)

1a(iv). [4] Pr(Price = ‘$’, Delivery = ‘Yes’ , Cuisine = ‘Korean’ | Popularity = ‘NP’)

1b.[6] Suppose a restaurant has the values: Price = ‘$’, Delivery = ‘Yes’ , Cuisine = ‘Korean’. Based on the calculation in part (1a.), is this restaurant classified as popular?

1c. [4] Design an ensemble method for Naive Bayes to further improve the accuracy and briefly describe the steps.

1d. [4] Describe the metrics that can effectively evaluate the classification of data with rare positive examples.

<h2>2       Question 2</h2>

We have eight training points, which are plotted in figure 1.

<table width="515">

 <tbody>

  <tr>

   <td width="158">


    <table width="104">

     <tbody>

      <tr>

       <td width="42">x1</td>

       <td width="35">x2</td>

       <td width="27">y</td>

      </tr>

      <tr>

       <td width="42">1</td>

       <td width="35">0.5</td>

       <td width="27">+1</td>

      </tr>

      <tr>

       <td width="42">2</td>

       <td width="35">1.2</td>

       <td width="27">+1</td>

      </tr>

      <tr>

       <td width="42">2.5</td>

       <td width="35">2</td>

       <td width="27">+1</td>

      </tr>

      <tr>

       <td width="42">3</td>

       <td width="35">2</td>

       <td width="27">+1</td>

      </tr>

      <tr>

       <td width="42">1.5</td>

       <td width="35">2</td>

       <td width="27">-1</td>

      </tr>

      <tr>

       <td width="42">2.3</td>

       <td width="35">3</td>

       <td width="27">-1</td>

      </tr>

      <tr>

       <td width="42">1.2</td>

       <td width="35">1.9</td>

       <td width="27">-1</td>

      </tr>

      <tr>

       <td width="42">0.8</td>

       <td width="35">1</td>

       <td width="27">-1</td>

      </tr>

     </tbody>

    </table></td>

   <td width="357"></td>

  </tr>

 </tbody>

</table>

Table 2: Dataset                                               Figure 1: 2-D scatterplot of the Dataset

Also, we have four test points with their true labels. Please answer following questions.

Table 3: Test Dataset

<table width="104">

 <tbody>

  <tr>

   <td width="42">x1</td>

   <td width="35">x2</td>

   <td width="27">y</td>

  </tr>

  <tr>

   <td width="42">2.7</td>

   <td width="35">2.7</td>

   <td width="27">+1</td>

  </tr>

  <tr>

   <td width="42">2.5</td>

   <td width="35">1</td>

   <td width="27">+1</td>

  </tr>

  <tr>

   <td width="42">1.5</td>

   <td width="35">2.5</td>

   <td width="27">-1</td>

  </tr>

  <tr>

   <td width="42">1.2</td>

   <td width="35">1</td>

   <td width="27">-1</td>

  </tr>

 </tbody>

</table>

2a.[10] Perform k-nearest neighbor classification with K = 1. What’s the testing error? (Please use Euclidean distance. Show your reasoning.)

2b. [10] Do the same thing as question 2a with K = 2.

2c. [10] A linear classifier <em>f</em>(<em>x</em>) = <em>a </em>∗ <em>x</em><sub>1 </sub>+ <em>b </em>∗ <em>x</em><sub>2 </sub>+ <em>c </em>works as follows: if <em>f</em>(<em>x</em>) <em>&gt;</em>= 0 , predict <em>x </em>as +1; otherwise, predict <em>x </em>as −1. Design a reasonable linear classifier(i.e. choose proper a, b, c). What’s the training error? What about the testing error? Show your reasoning(Your design doesn’t need to be optimal).

2d. [10] Compare KNN and linear classification method(e.g. SVM). You may draw conclusions based on your experience with question 2a-2c.

<h2>3       Question 3</h2>

Suppose we want to cluster the following 13 points:

<table width="519">

 <tbody>

  <tr>

   <td width="164">


    <table width="112">

     <tbody>

      <tr>

       <td width="58">index</td>

       <td width="31">x1</td>

       <td width="23">x2</td>

      </tr>

      <tr>

       <td width="58">1</td>

       <td width="31">1</td>

       <td width="23">3</td>

      </tr>

      <tr>

       <td width="58">2</td>

       <td width="31">1</td>

       <td width="23">2</td>

      </tr>

      <tr>

       <td width="58">3</td>

       <td width="31">2</td>

       <td width="23">1</td>

      </tr>

      <tr>

       <td width="58">4</td>

       <td width="31">2</td>

       <td width="23">2</td>

      </tr>

      <tr>

       <td width="58">5</td>

       <td width="31">2</td>

       <td width="23">3</td>

      </tr>

      <tr>

       <td width="58">6</td>

       <td width="31">3</td>

       <td width="23">2</td>

      </tr>

      <tr>

       <td width="58">7</td>

       <td width="31">5</td>

       <td width="23">3</td>

      </tr>

      <tr>

       <td width="58">8</td>

       <td width="31">4</td>

       <td width="23">3</td>

      </tr>

      <tr>

       <td width="58">9</td>

       <td width="31">4</td>

       <td width="23">5</td>

      </tr>

      <tr>

       <td width="58">10</td>

       <td width="31">5</td>

       <td width="23">4</td>

      </tr>

      <tr>

       <td width="58">11</td>

       <td width="31">5</td>

       <td width="23">5</td>

      </tr>

      <tr>

       <td width="58">12</td>

       <td width="31">6</td>

       <td width="23">4</td>

      </tr>

      <tr>

       <td width="58">13</td>

       <td width="31">6</td>

       <td width="23">5</td>

      </tr>

     </tbody>

    </table></td>

   <td width="355"></td>

  </tr>

 </tbody>

</table>

Table 4: Dataset                                               Figure 2: 2-D scatterplot of the Dataset

3a. [10] Cluster above points using K-means algorithm with k = 2. Please use (0, 3) and (6, 4) as the initial center points for the two clusters. Show your reasoning.

3b. [10] Now we want to use DBSCAN, a density-based algorithm, with MinPts = 2, and Eps = 1.5. Outline your clustering process.

3c. [10] Please perform AGNES, a hierarchical clustering algorithm on above points. Please use single link method and adopt Euclidean distance as the dissimilarity measure.
Download Link: https://assignmentchef.com/product/solved-cs145-homework-4
<br>
<ol>

 <li>Clustering Evaluation.</li>

</ol>

<table width="482">

 <tbody>

  <tr>

   <td width="64">ID</td>

   <td width="125">Conference Name</td>

   <td width="132">Ground Truth Label</td>

   <td width="160">Algorithm output Label</td>

  </tr>

  <tr>

   <td width="64">  1</td>

   <td width="125">IJCAI</td>

   <td width="132">3</td>

   <td width="160">2</td>

  </tr>

  <tr>

   <td width="64">2</td>

   <td width="125">AAAI</td>

   <td width="132">3</td>

   <td width="160">2</td>

  </tr>

  <tr>

   <td width="64">3</td>

   <td width="125">ICDE</td>

   <td width="132">1</td>

   <td width="160">3</td>

  </tr>

  <tr>

   <td width="64">4</td>

   <td width="125">VLDB</td>

   <td width="132">1</td>

   <td width="160">3</td>

  </tr>

  <tr>

   <td width="64">5</td>

   <td width="125">SIGMOD</td>

   <td width="132">1</td>

   <td width="160">3</td>

  </tr>

  <tr>

   <td width="64">6</td>

   <td width="125">SIGIR</td>

   <td width="132">4</td>

   <td width="160">4</td>

  </tr>

  <tr>

   <td width="64">7</td>

   <td width="125">ICML</td>

   <td width="132">3</td>

   <td width="160">2</td>

  </tr>

  <tr>

   <td width="64">8</td>

   <td width="125">NIPS</td>

   <td width="132">3</td>

   <td width="160">2</td>

  </tr>

  <tr>

   <td width="64">9</td>

   <td width="125">CIKM</td>

   <td width="132">4</td>

   <td width="160">3</td>

  </tr>

  <tr>

   <td width="64">10</td>

   <td width="125">KDD</td>

   <td width="132">2</td>

   <td width="160">1</td>

  </tr>

  <tr>

   <td width="64">11</td>

   <td width="125">WWW</td>

   <td width="132">4</td>

   <td width="160">4</td>

  </tr>

  <tr>

   <td width="64">12</td>

   <td width="125">PAKDD</td>

   <td width="132">2</td>

   <td width="160">1</td>

  </tr>

  <tr>

   <td width="64">13</td>

   <td width="125">PODS</td>

   <td width="132">1</td>

   <td width="160">3</td>

  </tr>

  <tr>

   <td width="64">14</td>

   <td width="125">ICDM</td>

   <td width="132">2</td>

   <td width="160">1</td>

  </tr>

  <tr>

   <td width="64">15</td>

   <td width="125">ECML</td>

   <td width="132">3</td>

   <td width="160">2</td>

  </tr>

  <tr>

   <td width="64">16</td>

   <td width="125">PKDD</td>

   <td width="132">2</td>

   <td width="160">1</td>

  </tr>

  <tr>

   <td width="64">17</td>

   <td width="125">EDBT</td>

   <td width="132">1</td>

   <td width="160">2</td>

  </tr>

  <tr>

   <td width="64">18</td>

   <td width="125">SDM</td>

   <td width="132">2</td>

   <td width="160">1</td>

  </tr>

  <tr>

   <td width="64">19</td>

   <td width="125">ECIR</td>

   <td width="132">4</td>

   <td width="160">4</td>

  </tr>

  <tr>

   <td width="64">20</td>

   <td width="125">WSDM</td>

   <td width="132">4</td>

   <td width="160">4</td>

  </tr>

 </tbody>

</table>




Suppose we want to cluster 20 above conferences into four areas, with ground truth label and algorithm output label shown in third and fourth column. Please evaluate the quality of the clustering algorithm according to purity, precision, recall, F-measure, and normalized mutual information, respectively.







<ol start="2">

 <li>K-means</li>

</ol>

<ul>

 <li>Fill in the missing lines in KMeans.py and run the algorithm against three datasets (dataset1.txt, dataset2.txt, and dataset3.txt), respectively. Please view the file README.txt for coding requirements.</li>

 <li>Plot the clustering results for the three datasets using a scatter plot, with different colors representing different clusters. Evaluate the algorithm using (1) purity and (2) normalized mutual information for each dataset.</li>

 <li>Give the strengths and weaknesses of using the K-means algorithm.</li>

</ul>




<ol start="3">

 <li>DBSCAN</li>

</ol>

<ul>

 <li>Fill in the missing lines in DBSCAN.py and run the algorithm against three datasets (dataset1.txt, dataset2.txt, and dataset3.txt), respectively. Please view the file README.txt for coding requirements.</li>

 <li>Plot the clustering results for the three datasets using a scatter plot, with different colors representing different clusters. Evaluate the algorithm using (1) purity and (2) normalized mutual information for each dataset.</li>

 <li>Give the strengths and weaknesses of using DBSCAN.</li>

</ul>




<ol start="3">

 <li>GMM</li>

</ol>

<ul>

 <li>Fill in the missing lines in GMM.py and run the algorithm against three datasets (dataset1.txt, dataset2.txt, and dataset3.txt), respectively. Please view the file README.txt for coding requirements.</li>

 <li>Plot the clustering results for the three datasets using a scatter plot, with different colors representing different clusters. Evaluate the algorithm using (1) purity and (2) normalized mutual information for each dataset.</li>

 <li>Give the strengths and weaknesses of using GMMs.</li>

</ul>



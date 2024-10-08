---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
_\* means equal contribution_



<!-- 
{% include base_path %}
-->

<!-- New style rendering if publication categories are defined -->
<!--
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->


<style>
    .blue-quote {
        border-left: 4px solid #ffb563; /* Orange border */
        background-color: #f8f9fa; /* Light grey background */
        color: #333; /* Dark grey text color */
        padding: 10px 10px;
        margin: 10px;
        font-style: normal;
    }
  
  .green-quote {
        border-left: 4px solid #9cc5a1; /* Orange border */
        background-color: #f8f9fa; /* Light grey background */
        color: #333; /* Dark grey text color */
        padding: 10px 10px;
        margin: 10px;
      font-style: normal;
    }
</style>

Conference Papers
------
<blockquote class="green-quote">
Detecting Fraudulent Services on Quantum Cloud Platforms via Dynamic Fingerprinting <br>
<strong>Jindi Wu</strong>, Tianjie Hu, and Qun Li <br> 
43rd IEEE/ACM International Conference on Computer-Aided Design (ICCAD'24)
</blockquote>


<blockquote class="green-quote">
Quantum Network Routing Based on Surface Code Error Correction <br>
Tianjie Hu, <strong>Jindi Wu</strong>, and Qun Li <br> 
44th IEEE International Conference on Distributed Computing Systems (ICDCS'24) 
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10631008">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10631008)   -->
</blockquote>

<blockquote class="green-quote">
MORE: Measurement and Correlation-based Variational Quantum Circuit for Multi-classification <br>
<strong>Jindi Wu</strong>, Tianjie Hu, and Qun Li <br> 
4th IEEE International Conference on Quantum Computing and Engineering (QCE'23)  
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10313792">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10313792) -->
</blockquote>

<blockquote class="green-quote">
Laws: Look around and warm-start natural gradient descent for quantum neural networks <br>
Zeyi Tao, <strong>Jindi Wu</strong>, and Qun Li <br> 
2nd IEEE International Conference on Quantum Software (QSW'23)  
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10234243">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10234243)   -->
</blockquote>

<blockquote class="green-quote">
Scalable Quantum Neural Networks for Classification <br>
<strong>Jindi Wu</strong>, Zeyi Tao, and Qun Li <br> 
3rd IEEE International Conference on Quantum Computing and Engineering (QCE'22)  
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9951212">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9951212) -->
</blockquote>

<blockquote class="green-quote">
Efficient Privacy-Preserving Federated Learning for Resource-Constrained Edge Devices <br>
<strong>Jindi Wu</strong>, Qi Xia, and Qun Li <br> 
17th International Conference on Mobility, Sensing, and Networking (MSN'21)  
<!--   <a href="https://par.nsf.gov/servlets/purl/10358911">Paper</a> -->
<!--   [Paper](https://par.nsf.gov/servlets/purl/10358911) -->
</blockquote>

<blockquote class="green-quote">
SAFE: Similarity-aware multi-modal fake news detection <br>
Xinyi Zhou*, <strong>Jindi Wu</strong>*, and Reza Zafarani <br> 
24th Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD'20)  
<!--   <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7206257/">Paper</a> -->
<!--   [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7206257/) -->
</blockquote>





Journal & Magazine Articles
------
<blockquote class="green-quote">
Q-ID: Lightweight Quantum Network Server Identification through Fingerprinting <br>
<strong>Jindi Wu</strong>, Tianjie Hu, and Qun Li <br> 
IEEE Network (2024)  
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10530432">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10530432) -->
</blockquote>

<blockquote class="green-quote">
Distributed Quantum Machine Learning: Federated and Model-Parallel Approaches <br>
<strong>Jindi Wu</strong>, Tianjie Hu, and Qun Li <br> 
IEEE Internet Computing 28.2 (2024): 65-72.  
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10508212">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10508212) -->
</blockquote>

<blockquote class="green-quote">
SurfaceNet: Fault-Tolerant Quantum Networks with Surface Codes <br>
Tianjie Hu, <strong>Jindi Wu</strong>, and Qun Li <br> 
IEEE Network (2023)  
<!--   <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10288502">Paper</a> -->
<!--   [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10288502) -->
</blockquote>

<blockquote class="green-quote">
A survey of federated learning for edge computing: Research problems and solutions <br>
Qi Xia, Winson Ye, Zeyi Tao, <strong>Jindi Wu</strong>, and Qun Li <br> 
High-Confidence Computing 1.1 (2021): 100008. (HCC'21)  
<!--   <a href="https://www.sciencedirect.com/science/article/pii/S266729522100009X">Paper</a> -->
<!--   [Paper](https://www.sciencedirect.com/science/article/pii/S266729522100009X) -->
</blockquote>



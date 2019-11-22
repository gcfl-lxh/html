---
layout: base
---


<!-- Page Content -->
  <div class="container">


<!-- Portfolio Section -->
<h2 class="my-4">栏目2</h2>

<div class="row">
{% for post in site.posts %}
  <div class="col-lg-4 col-sm-6 portfolio-item">
    <div class="card h-100">
      <a href="{{site.baseurl}}/{{post.url}}/"><img class="card-img-top" src="img/lufei.jpg" alt=""></a>
      <div class="card-body">
        <h4 class="card-title">
          <a href="{{site.baseurl}}/{{post.url}}/">{{post.title}}</a>
        </h4>
        <p class="card-text">{{post.information}}</p>
     
      </div>
    </div>
  </div>
{% endfor %}
</div>

<!-- /.row -->



<hr>



</div>
<!-- /.container -->
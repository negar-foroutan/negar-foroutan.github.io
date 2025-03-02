<h2 id="publications" style="margin: 2px 0px -15px;">Work Experience</h2>

<div class="publications">
<ol class="bibliography">


{% for exp in site.data.experiences.main %}
<!-- <li> -->
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <strong> {{ exp.title }} </strong> | {{ exp.company }}, {{ exp.location }} [{{ exp.date }}]
    <div class="exps">
      <p>{{ exp.description }}</p>
    </div>
  </div>
</div>
<!-- </li> -->
<!-- <br> -->

{% endfor %}

</ol>
</div>

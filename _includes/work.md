<h2 id="work" style="margin: 2px 0px -15px;">Work Experience</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.work.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;padding-bottom: -5px">
      <div class="title"><a href="{{ link.video }}" gtag-section="work" gtag-item="{{ link.gtag_item }}">{{ link.title }}</a></div>
      <div class="author">{{ link.group }}</div>
      <div class="periodical"><em>{{ link.date }}</em></div>
      <div class="periodical">{{ link.description }}</div>
    <!-- <div class="links">
      {% if link.video %} 
      <a href="{{ link.video }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;" gtag-section="work" gtag-item="{{ link.gtag_item }}">Video</a>
      {% endif %}
      {% if link.slides %} 
      <a href="{{ link.slides }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;" gtag-section="work" gtag-item="{{ link.gtag_item }}">Slides</a>
      {% endif %}
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div> -->
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>

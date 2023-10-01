<h2 id="publications" style="margin: 2px 0px -15px;">Projects</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% assets/img/Wacker.png %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="Recent Advances in Wacker Oxidation: from Conventional to Oxidative Rearrangement of 1,1-disubstituted Alkenes to Ketones"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ Kecheng Wang }}</div>
      </div>
    <div class="links">
      {% assets/files/CHEM2505_Spring2023_Final.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
    </div>
  </div>
</div>
</li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% assets/img/Proposal_Supra.png %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="Fast Water Nanochannels with a Densely Fluorous Interior Surface"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ Kecheng Wang }}</div>
      </div>
    <div class="links">
      {% assets/files/Fast Water Nanochannels with a Densely Fluorous Interior Surface.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
    </div>
  </div>
</div>
</li>

<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% assets/img/EE_Project.jpg %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="Onboard 65W Type-C Charger"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ Kecheng Wang }}</div>
      </div>
    <div class="links">
      {% assets/files/EE-Project.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
    </div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>

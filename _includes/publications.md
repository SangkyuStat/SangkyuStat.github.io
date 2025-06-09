<br>

## Publications

<p style="margin:4px 0 18px;font-size:15px;">
[<a href="https://scholar.google.com/citations?user=E4S3q1gAAAAJ&hl=en"
  target="_blank" rel="noopener">Google&nbsp;Scholar</a>]
</p>

<style>
  .auth-notes{
    font-size:0.8em;   
    line-height:1.3;    
    display:inline-block;
    margin-bottom:0.6em;
  }
</style>

<div class="auth-notes">
  * denotes equal contribution; † denotes corresponding author<br>
  ‡ denotes students that I advised
</div>

### Preprints/Submitted Papers

<div class="publications">
<ol class="bibliography">
  
{% for link in site.data.preprints.main %}

<li>
<div class="pub-row">
 <div class="col-sm-12" style="position:relative;padding-right:15px;padding-left:15px;">
  <div class="title"><a href="{{ link.paper }}">{{ link.title }}</a></div>
  <div class="author">{{ link.authors }}</div>
  <div class="periodical"><em>{{ link.conference }}</em>
  </div>
   <div class="links">
     {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
    </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.CRAN %} 
      <a href="{{ link.CRAN }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">CRAN</a>
      {% endif %}
      {% if link.github %} 
      <a href="{{ link.github }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">GitHub</a>
      {% endif %}
      {% if link.shiny %} 
      <a href="{{ link.shiny }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Shiny</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Dataset</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<span style="display:block; height:16px;"></span>

{% endfor %}

</ol>
</div>

### Published Papers (Statistical Methods, Theories, and Software)

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position:relative;padding-right:15px;padding-left:15px;">
  <div class="title"><a href="{{ link.paper }}">{{ link.title }}</a></div>
  <div class="author">{{ link.authors }}</div>
  <div class="periodical"><em>{{ link.conference }}</em>
  </div>
    <div class="links">
     {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
    </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.CRAN %} 
      <a href="{{ link.CRAN }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">CRAN</a>
      {% endif %}
      {% if link.github %} 
      <a href="{{ link.github }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">GitHub</a>
      {% endif %}
      {% if link.shiny %} 
      <a href="{{ link.shiny }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Shiny</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Dataset</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<span style="display:block; height:16px;"></span>

{% endfor %}

</ol>
</div>

### Published Papers (Collaborative Applications)

<div class="publications">
<ol class="bibliography">

{% for link in site.data.applications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position:relative;padding-right:15px;padding-left:15px;">
  <div class="title"><a href="{{ link.paper }}">{{ link.title }}</a></div>
  <div class="author">{{ link.authors }}</div>
  <div class="periodical"><em>{{ link.conference }}</em>
  </div>
    <div class="links">
     {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
    </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.CRAN %} 
      <a href="{{ link.CRAN }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">CRAN</a>
      {% endif %}
      {% if link.github %} 
      <a href="{{ link.github }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">GitHub</a>
      {% endif %}
      {% if link.shiny %} 
      <a href="{{ link.shiny }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Shiny</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Dataset</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<span style="display:block; height:16px;"></span>

{% endfor %}

</ol>
</div>

## Statistical Software

<div class="publications">
<ol class="bibliography">

{% for link in site.data.software.main %}

<li>
<div class="pub-row">
  <div class="col-sm-12" style="position:relative;padding-right:15px;padding-left:15px;">
  <div style="display:flex; align-items:baseline; gap:0.6rem;">
  <div class="title"><a href="{{ link.paper }}">{{ link.title }}</a></div>
  <div class="periodical"><em>{{ link.role }}</em></div>
  </div>
  <div class="periodical">{{ link.explanations }}
  </div>
    <div class="links">
     {% if link.notes %} 
      <strong> <i style="color:#e74d3c; font-weight:600">{{ link.notes }}</i></strong>
      {% endif %}
    </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if link.CRAN %} 
      <a href="{{ link.CRAN }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">CRAN</a>
      {% endif %}
      {% if link.github %} 
      <a href="{{ link.github }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">GitHub</a>
      {% endif %}
      {% if link.shiny %} 
      <a href="{{ link.shiny }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Shiny</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.data %} 
      <a href="{{ link.data }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Dataset</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

<span style="display:block; height:8px;"></span>

{% endfor %}

</ol>
</div>

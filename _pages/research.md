---
layout: page
title: Research
permalink: /research/
<!-- description: Everything related to my research. -->
social: false
---


<!-- <div>
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
</div> -->

<div>
  {% bibliography -f papers %}
</div>

<!-- ### notes
1. Discrete computational optimal transport (with Adam Block) <small>[<a href="{{ site.url }}/assets/pdf/Discrete_Optimal_Transport.pdf">pdf</a>]</small>
2. L1-regularized regression <small>[<a href="{{ site.url }}/assets/pdf/L1_regularized_regression.pdf">pdf</a>]</small>
3. Sparse PCA (with Sinho Chewi) <small>[<a href="{{ site.url }}/assets/pdf/sparse_PCA.pdf">pdf</a>]</small> -->

<!-- ### presentations
1. Malliavin Calculus <small>[<a href="{{ site.url }}/assets/pdf/Malliavin_calculus.pdf">pdf</a>]</small>
2. Kernel density estimation via diffusion <small>[<a href="{{ site.url }}/assets/pdf/Kernel_density_estimation_via_Diffusion.pdf">pdf</a>]</small>
3. Normality testing via Wasserstein distance <small>[<a href="{{ site.url }}/assets/pdf/normality_testing.pdf">pdf</a>]</small>
4. The East-process <small>[<a href="https://github.com/PatrikGerber/East-process/blob/master/East_process_presentation.pdf">pdf</a>]</small>
5. Branching random walks with selection <small>[<a href="https://github.com/PatrikGerber/BRWs/blob/master/presentation.pdf">pdf</a>]</small>

### miscellaneous
1. I participated in <a href="https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2020/?tab=faq">RIPS</a> where I worked on deep reinforcement learning sponsored by AMD <small>[<a href="https://github.com/AMD-RIPS/RL-2018/blob/master/documents/arxiv/AMDFinalReportRIPS2018.pdf">pdf</a>] [<a href="https://github.com/AMD-RIPS/RL-2018">code</a>]</small>
2. I spent a summer in the Statistics department of University of Oxford working on interacting particle systems under the supervision of Professor Paul Chleboun <small>[<a href="https://github.com/PatrikGerber/East-process/blob/master/East_process.pdf">pdf</a>]</small>
3. I wrote a master's thesis on branching random walks with selection, supervised by Professor Julien Berestycki <small>[<a href="https://github.com/PatrikGerber/BRWs/blob/master/FINAL/final_version.pdf">pdf</a>]</small> -->


<!--
{% for project in site.projects %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %} -->

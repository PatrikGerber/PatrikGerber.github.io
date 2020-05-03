---
layout: page
title: projects
permalink: /projects/
description: A list of research/lecture-notes, presentations and other related things.
social: false
---
1. In 2018 I participated in <a href="https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2020/?tab=faq">RIPS</a> where I worked on reinforcement learning in the team sponsored by AMD. <a href="https://github.com/AMD-RIPS/RL-2018/blob/master/documents/arxiv/AMDFinalReportRIPS2018.pdf">pdf</a>, <a href="https://github.com/AMD-RIPS/RL-2018">code</a>. 
2. I spent a summer in the Statistics department of University of Oxford working on interacting particle systems under the supervision of Professor Paul Chleboun. <a href="https://github.com/PatrikGerber/East-process/blob/master/East_process.pdf">pdf</a>. 
3. I wrote a master's thesis on branching random walks with selection, supervised by Professor Julien Berestycki. <a href="https://github.com/PatrikGerber/BRWs/blob/master/FINAL/final_version.pdf">pdf</a>. 


## presentations
1. Kernel density estimation via diffusion <a href="{{ site.url }}/assets/pdf/Kernel_density_estimation_via_Diffusion.pdf">pdf</a>
2. Sparse PCA (with Sinho Chewi) <a href="{{ site.url }}/assets/pdf/sparse_PCA.pdf">pdf</a>.
3. Normality testing via Wasserstein distance <a href="{{ site.url }}/assets/pdf/normality_testing.pdf">pdf</a>.
4. The East-process <a href="https://github.com/PatrikGerber/East-process/blob/master/East_process_presentation.pdf">pdf</a>. 
5. Branching random walks with selection <a href="https://github.com/PatrikGerber/BRWs/blob/master/presentation.pdf">pdf</a>.

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

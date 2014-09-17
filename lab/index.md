---
title: "<img alt=\"Explore VR\" src=\"/assets/evr_logo.png\" alt=\"exploreVR logo\" />"
author: admin
layout: lab
published: true
---
<div class="bg-primary lab_highlight  grapher2">
<h2>The Lab</h2>
<p> This will be special section which will be geared towards the researchers who are working in the field of disability or VR. This section will house mainly two types of content:</p>
<ul>
<li>Data Repository: Download link and description of multiple datasets related to disability or VR</li>
<li>Data Analysis: Code used for data analysis and visualization will be provided under this section</li>
</ul>
</div>
<h2>RSA-911 Data</h2>
<p>The RSA-911 is an administrative dataset that captures a variety of demographic and other data for each individual whose case is closed during the fiscal year. It includes data such as: type of disability, services provided through the Vocational Rehabilitation (VR) and Supported Employment (SE) Programs, providers and costs of services, and employment outcomes.</p>

<div class="panel-group" id="accordion">
  <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">
        <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne">
          Downloadable RSA 911 Data Sets
        </a>
      </h4>
    </div>
    <div id="collapseOne" class="panel-collapse collapse jc_collapse">
      <div class="panel-body">
        <p><em>All these data sets are derived from RSA911 data set.</em></p>

        <p><strong><a href="/data/rsa_911/ClosureDuration_08to11.csv">ClosureDuration_08to11.csv</a>  <br />
        <a href="/data/rsa_911/ClosureDuration_08to11.xls">ClosureDuration_08to11.xls</a>  </strong></p>
        <p>This file provides data on different measures of time spent by clients of VR agencies from their application to closure, from determination of clients eligibility to their closure and time from determination of IPE to closure.</p>

        <p><strong><a href="/data/rsa_911/ClosureOccupation_08to12.xls">ClosureOccupation_08to12.xls</a>  </strong><br />
        This file provides data on occupation statistics for all the states and territories for all the clients with employment outcomes. Data is presented in aggregated format for period between 2008 to 2012.</p>

        <p><strong><a href="/data/rsa_911/MajOccTransPercent.xls">MajOccTransPercent.xls</a></strong>  <br />
        This dataset has statistics on percent of transitiong age youth between 14 to 24 employed in different major occupation types</p>

        <p><strong><a href="/data/rsa_911/TransitionAge2012.csv">TransitionAge2012.csv</a><br/>
        <a href="/data/rsa_911/TransitionAge2012.xls">TransitionAge2012.xls</a> </strong> <br />
        This dataset has aggregated data for following metrics on transition age (14 to 24) clients for all the US states and territories -  </p>


        <ul>
        <li> Cost of purchased services</li>
        <li> Total clients served</li>
        <li> Different calculated fields in ratio and percentages</li>
</ul>

      </div>
    </div>
</div>

<h2>Data Analyses</h2><p>The Institute for Community Inclusion (ICI) has generated a number of data analyses to increase knowledge about the public VR program and its role within the larger employment and disability service system within and across states and territories. </p>

{% for post in site.categories.home-ana %}


    <h4>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h4>


{% endfor %}

<h2>VR Survey Data (coming soon)</h2>
<p>The Institute for Community Inclusion (ICI) has surveyed a number of vocational rehabilitation (VR) agencies statewide to measure levels of VR services provided with respect to employment outcomes, agency partnerships, state demographics and other data points.</p>

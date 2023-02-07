---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  # You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Full list of "[Refereed publications](https://ui.adsabs.harvard.edu/search/filter_property_fq_property=AND&filter_property_fq_property=property%3A%22refereed%22&fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq=%7B!type%3Daqp%20v%3D%24fq_property%7D&fq_database=database%3A%20astronomy&fq_property=(property%3A%22refereed%22)&q=pubdate%3A%5B2014-01%20TO%209999-12%5D%20author%3A(%22Avila%2C%20Santiago%22)&sort=date%20desc%2C%20bibcode%20desc/metrics)" (ADS website).
 
 "[All papers including preprints](
  https://ui.adsabs.harvard.edu/search/fq=%7B!type%3Daqp%20v%3D%24fq_database%7D&fq_database=database%3A%20astronomy&q=pubdate%3A%5B2012-01%20TO%209999-12%5D%20author%3A(%22Avila%2C%20Santiago%22)&sort=date%20desc%2C%20bibcode%20desc&p_=0)"  ADS website.

[Page under construction]
====== 

#%Here, I help you navigate throught them: 


#%UNITsim papers
#%------ 

#%eBOSS papers
#%------

#%DES-Y3 BAO papers
#%-----

#%Other DES-Y3 papers
#%-----

#%DES-Y1 BAO papers
#%-----

#%Intensity Mapping papers
#%-----



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: default
---
# Speaking

I enjoy speaking at conferences and meetups to share my knowledge and ideas. Below you can find a list of my past and 
upcoming speaking gigs.

{% assign all_gigs = site.data.gigs | where_exp: "gig", "true" %}
{% include gig_list.html gigs=all_gigs %}
# Introduction
This repo is a trial for student who take CSCI3251 to familiar the workflow of a project.\
Each person shall only take one issue. Issue should be handled inorder. Also include personal info in _stu foloder.

First, the project manager(teammate 1) will setup the issue and check their progress time to time.\
Secondly, project manager(teammate 2) manage all the issue to project board as "To do" or something else.\
Then, Documentation manager(teammate 3) will write the readme.md to briefly introduce our project.\
Next, Development manager(teammate 4) will code for our project.\
Afterward, Delivery manager(teammate 5) will update the readme.md and get a status badge.\
Furthermore, Personnel manager(teammate 6) will setup the showcase for all of our team.\
Finally, Promotion manager(teammate 7) will deploy the repo webpage(.io) to public for us.

# Code
{% highlight c %}
{% include_relative code.c %}
{% endhighlight %}\
![example workflow](https://github.com/csci3251-2022/project-team-e/actions/workflows/main.yml/badge.svg)

# Contributors
{% for p in site.stu %}
  ![image]({{p.image}}) {{p.user}} {{p.name}}
  <p>{{ p.content | markdownify }}</p>
{% endfor %}
 

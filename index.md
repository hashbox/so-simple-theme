---
layout: about
show_excerpts: true
title: Jeeseung Han (한지승)
---

#### Data Scientist (feat. DevOps)
---
Hello, I'm Jeeseung Han. <br/>
I'm a **Data Scientist** who studies computer vision. and I also a **DevOps Engineer**.
{: .notice}

### Education
Master of Computer Science, *[Intelligent Data Systems Laboratory](http://ids.snu.ac.kr/) Seoul National University, Korea* (2018~now)

Bachelor of Computer Science, *Konkuk University, Korea* (2010~2016)


### Experience
Intelligent Service Team Leader, *[IntelliSys Corporation](http://intellisys.co.kr)* (2018~now)


### Publications
{% assign thesis = site.publications | sort: 'date' | reverse %}
{% for v in thesis %}
- **{{ v.title }}**<br/>{{v.authors}}<br/>{{v.publication}}
{% endfor %}

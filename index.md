---
layout: about
show_excerpts: true
title: Jeeseung Han
---

#### Data Scientist (slash DevOps)
---
Hello, I'm Jeeseung Han. <br/>
I'm a **Data Scientist** who studies object detection. slash I also a **DevOps Engineer**.
{: .notice}

### Education
* Master of Computer Science and Engineering (MCSE), *[Intelligent Data Systems Laboratory](http://ids.snu.ac.kr/) Seoul National University, Korea* (2018~now)

* Bachelor of Computer Science and Engineering (BCSE), *Konkuk University, Korea* (2010~2016)


### Experience
* Intelligent Service Team Leader, *[IntelliSys Corporation](http://intellisys.co.kr)* (2018~now)
    - Led packaging and installation of visual intelligence engine of company L, including convert to Triton inference server for models
    - Conducted research of fashion item detector for service based on DeepLab using PyTorch
    - Implemented infrastructure using AWS Cloud, Kubernetes, Terraform
    - Designed fashion AI inference system using PyTorch, RabbitMQ
    - Instructed microservice architecture (MSA) for Fitzme service using Spring boot and Django


### Publications
{% assign thesis = site.publications | sort: 'date' | reverse %}
{% for v in thesis %}
- [**{{ v.title }}**]({{v.url}})<br/>{{v.authors}}<br/>{{v.publication}}
{% endfor %}

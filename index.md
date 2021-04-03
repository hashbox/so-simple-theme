---
layout: about
show_excerpts: true
title: Jeeseung Han
---

#### Data Scientist (and is also DevOps)
---
Hello, I'm Jeeseung Han. <br/>
I'm a **Data Scientist** who studies object detection, and is also also a **MLOps Engineer**.
{: .notice}

### Education
* Master of Computer Science and Engineering (MCSE), *[Intelligent Data Systems Laboratory](http://ids.snu.ac.kr/) Seoul National University, Korea* (2018~2020)
    - Member of Intelligence Data Systems Laboratory
    - Teaching Assistant of Graduate School Recommendation System 2020

* Bachelor of Computer Science and Engineering (BCSE), *Konkuk University, Korea* (2010~2016)
    - President of the student council of Konkuk Information and Communications Undergraduate College
    - Director of Information Technology, Konkuk Student Council
    - Completed Cisco Certified Network Associate (CCNA) Routing and Switching: Introduction to Networks
    - Leave of absence for military conscription, Republic of Korea Military Police (2014–2016)

### Experience
* MLOps Engineer, *[Clova CIC](https://clova.ai)*, *[Naver Corporation](https://navercorp.com)* (2020~now)
* Team Leader, Intelligence, Architect and Cloud DevOps Engineer, *[IntelliSys Corporation](http://intellisys.co.kr)* (2018~2020)
    - Led packaging and installation of visual intelligence engine, including convert to Triton inference server for models
    - Conducted research of fashion item detector for service based on DeepLab using PyTorch
    - Implemented infrastructure using AWS Cloud, Kubernetes, Terraform
    - Designed fashion AI inference system using PyTorch, RabbitMQ
    - Instructed microservice architecture (MSA) for Fitzme service using Spring boot and Django

* Working scholars, Infra, Infrastructure network management, *Zungwon Engineering & System, Inc.* (2010-2012, 2016)
    - Monitored network status for Konkuk University, including wireless access point activity
    - Supported installation and set-up of routers and switches at newly constructed engineering building
    - Assisted in network installation for student and special events

### Publications
{% assign thesis = site.publications | sort: 'date' | reverse %}
{% for v in thesis %}
- [**{{ v.title }}**]({{v.url}})<br/>{{v.authors}}<br/>{{v.publication}}
{% endfor %}

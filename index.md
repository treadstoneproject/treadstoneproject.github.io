---
layout: page
title: Treadstone Project.
description: Treadstone Project, Malware Analysis malware tools.
tagline: Supporting tagline
---
{% include JB/setup %}


## Abstract

Computer Virus is one of the major security concerns for many enterprises that heavily used personal computer. Virus scanning software becomes an important tool that allows users to detect computer virus threat early. This work presents the parallelization techniques that enable the malware detected engine, which used Aho-Corasick algorithm, to run on multi-core computer more efficiently. This technique is very useful in enhancing the performance of a computer virus scanning process. The concept can also be applied to various anti-virus software.

    
## Architecture

* [Malware static scan engine, Code Name : Hanuman](#)
* [Device sandbox](#) monitoring process for financial software.
* [Tracethreat](#) tracing malware tools for presenting statistic infected file in system.


## Blog post status

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Based on the paper techniques.

* [Applying Parallelization Techniques to Speedup ClamAV Anti-Virus.](https://www.researchgate.net/publication/262820325_Applying_Parallelization_Techniques_to_Speedup_ClamAV_Anti-Virus)


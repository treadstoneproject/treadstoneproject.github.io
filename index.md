---
layout: page
title: "Treadstone Project."
description: "Treadstone Project, Malware Analysis malware tools."
tagline: Supporting tagline
---
{% include JB/setup %}


## Abstract

Computer Virus is one of the major security concerns for many enterprises that heavily used personal computer. Virus scanning software becomes an important tool that allows users to detect computer virus threat early. This work presents the parallelization techniques that enable the malware detected engine, which used Aho-Corasick algorithm, to run on multi-core computer more efficiently. This technique is very useful in enhancing the performance of a computer virus scanning process. The concept can also be applied to various anti-virus software.

    
## Architecture

* [Tracethreat-MAT](https://github.com/treadstoneproject/tracethreat-mat)(Code name Hanuman)
* [Device sandbox](#) monitoring process for financial software.
* [TracethreatWeb](#) tracing malware tools for presenting statistic infected file in system.


## Blog post status

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Based on the paper techniques.

* [Applying Parallelization Techniques to Speedup ClamAV Anti-Virus.](https://www.researchgate.net/publication/262820325_Applying_Parallelization_Techniques_to_Speedup_ClamAV_Anti-Virus)

## Disclaimer

Tracethreat-MAT(TT-MAT) is a research prototype and is provided “as is” without warranty or support of any kind, whether expressed or implied. The creators of TT-MAT Tools make no guarantee and hold no responsibility for any damage, injury, loss of property, loss of data, loss of any and all resources, or any negative influence what-so-ever that may result from any and all use of HNM Tools and associated materials. 

TT-MAT Tools are open source software for non-commercial and academic use under the Apache Licence 2.0. Commercial use is in general prohibited and requires a commercial license. For a commercial license please contact us at treadstone-at-treadstoneproject-dot-io

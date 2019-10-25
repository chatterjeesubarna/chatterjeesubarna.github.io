---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<style>
p { margin-bottom: -10px; }
</style>

<font face="helvetica" size="3"> <p>In my Tyrion-sized research career, I have worked on the following topics.</p><br>


<font face="helvetica" color="black" size="4.5">
          <p>Data stream processing for IoT applications</p></font>
<font face="helvetica" size="3"> 
  <p align="justify">A streaming platform cannot be categorized as “good” or “bad” as every platform is differently designed to process specific stream types. Each platform is unique about the nature of data sets, the variable message processing semantics, and the differential hardware expectations. Therefore, it is extremely difficult, yet crucial, to judicially select the streaming platform that not only suits the application requirements but also abides by the resource offerings of the physical infrastructure of the host organization (or an end-user). To address this issue, I focused on a thorough comparative analysis of three data stream processing platforms that are chosen based on their potential to process both streams and batches in real-time. </p> <br>
</font>



<font face="helvetica" color="black" size="4.5">
          <p>Sensor-cloud infrastructure</p></font>

 <font face="helvetica" size="3"> 
   <p align="justify">This research focused on the conceptualization and implementation of a new Internet of Things (IoT)-cloud infrastructure called sensor-cloud infrastructure rendering a novel service called <i>Sensors-as-a-Service (Se-aaS)</i>. The motivation behind the emergence of sensor-cloud platforms was due to the limitations encountered with conventional Wireless Sensor Networks (WSNs) as WSN-based applications are generally single-user centric, in which a user-organization owns and deploys its personalized sensor network and typically does not share the accessed data to another party (user/organization). Thus, generally, only user- organizations that own a sensor network have satisfactory access to sensor data. To resolve the afore-mentioned limitations and widely disseminate the sensor technology to the common mass of people, a newly proposed architecture namely sensor-cloud architecture was being considered as a potential substitute for traditional WSNs. When I started my research back in 2013, several works were being initiated in this direction to primarily focus on the principles, the dogma, and the challenges involved in this shift of paradigm from WSN to sensor-cloud platforms. However, the technicalities that are required from an implementation perspective, inclusive of the theoretical modeling, experimental analysis, architectural designs, and development of this platform, were yet to be explored. Therefore, I focused on resolving the principal technical challenges associated with the complete conceptualization of sensor-cloud and eventually built a fully-functional prototype of sensor-cloud infrastructure.</p><br>
 </font>




 <font face="helvetica" color="black" size="4.5">
            <p>Cloud-assisted smart healthcare</p></font>
 <font face="helvetica" size="3"> 
    <p align="justify">This research focused the domain of cloud-assisted smart healthcare as it is extremely relevant from an Indian (developing country) perspective. In order to ensure an optimal routing strategy, the work establishes an architecture in which health data from patients are transmitted from wearable body sensor nodes (that sense and report physiological parameters of human body) to cloud servers for remote analysis and diagnosis. Later, this architecture was further revisited from an ambulatory healthcare perspective in collaboration with the All India Institute of Medical Sciences, (AIIMS) Bhubaneswar, and B. C. Roy Hospital, India. The work further matured as we proposed a privacy-aware ambulatory healthcare system using wireless body area networks (WBANS). </p>
 
</font>
---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, Stanford University, 2025 (expected)
* B.A. in Computer Science and Mathematics, Middlebury College, 2020

Honors & Awards
=====
* Graduated __Salutatorian__ and __Summa Cum Laude__ (Middlebury College)
* Won __Phi Beta Kappa__ prize (Middlebury College) 
* Phi Beta Kappa junior inductee (Middlebury College)
* Timothy T. Huang Award in Computer Science (Middlebury College)

Professional Experience
======
* Winter 2021 - present: Ph.D Research Assistant, Stanford University
  * Advisor: Caroline Trippel
  * Researching hardware security and formal methods
  * Project: Leakage Containment Models
	* Implemented tool that statically detects Spectre v1 and v4 leakage in C programs
	* Analyzed the crypto library libsodium for Spectre vulnerabilities
	* Developed a general, theoretical framework (LCM) that underpins leakage detection tool
	* Approach outperforms existing tools for Spectre vulnerability analysis
  
* Spring 2021: Ph.D Research Assistant, Stanford University
  * Worked with Philip Levis as part of Stanford's rotational program
  * Researched virtualization of distributed energy resources
  
* Fall 2020: Ph.D Research Assistant, Stanford University
  * Worked with Dawson Engler as part of Stanford's rotational program
  * Researched memory checkers in embedded systems

* Summer 2017, Fall 2017, Summer 2018: Computer Vision Research Assistant, Middlebury College
  * Supervisor: Daniel Scharstein
  
  
Skills
======
* __Programming Languages__: C, C++, x86 assembly, Python, bash, Verilog, Java, Swift
* __Programming Environments__: macOS, Linux, FreeBSD
* __Tools__:
  * _Reverse engineering and debugging_: IDA Pro, gdb
  * _Building & source control_: make, CMake, git
  * _Virtualization_: Docker, VirtualBox
  * _Formal methods_: Z3, SMT-LIB

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

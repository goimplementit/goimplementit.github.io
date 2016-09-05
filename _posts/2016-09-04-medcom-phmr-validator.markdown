---
layout: post
title:  "Medcom just got a danish HL7 PHMR validator"
permalink:  "medcom-phmr-validator"
date:   2016-09-04 11:58:35 +0100
categories: HL7, CDA, PHMR
---
Medcom needed a way for external parties to validate whether or not the PHMR data their devices generate is valid or not according to a danish extension to the HL7 Personal Health Monitoring Report (PHMR) standard.

GoImplement.it created a validation REST service with java and schematron. Moreover we created a simple user interface with angularjs.

![Danish PHMR validator by GoImplement.it]({{ '/images' | prepend: site.baseurl }}/medcom-phmr-validator.png)
*Simple user interface for validating both textual and file input.
GoImplement.it created both the user interface and the backend validation service*

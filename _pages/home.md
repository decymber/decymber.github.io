---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#20b2aa"
  overlay_image: /assets/images/mm-home-page-feature.jpg
excerpt: >
  A group of security and automation professionals aiming to build and safeguard Blockchain infrastructure.<br />
feature_certificate_title:
  - image_path: /assets/images/certification.svg
    alt: "aws"
feature_certificate:
  - image_path: /assets/images/aws.png
    alt: "aws"
  - image_path: /assets/images/gcp.png
    alt: "gcp"
  - image_path: /assets/images/azure.png
    alt: "azure"
  - image_path: /assets/images/ccsp.png
    alt: "ccsp"
feature_services_title:
  - image_path: /assets/images/services.svg
    alt: "aws"
feature_services:
  - image_path: /assets/images/audit.png
    alt: "audit"
    title: "Infrastructure Security"
    excerpt: "Blockchain Infrastructure Security and Audit."
  - image_path: /assets/images/automation.png
    alt: "automation"
    title: "NodeOps"
    excerpt: "Build Blockchain Infrastructure with devops and automation."
---
{% include feature_row %}

{% include feature_row id="feature_certificate_title" type="left" %}
{% include feature_row id="feature_certificate" %}
{% include feature_row id="feature_services_title" type="left" %}
{% include feature_row id="feature_services" %}

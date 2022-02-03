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
gallery_certificate:
  - image_path: /assets/images/aws68x68.svg
    alt: "aws"
  - image_path: /assets/images/gcp68x68.svg
    alt: "gcp"
  - image_path: /assets/images/azure68x68.svg
    alt: "azure"
  - image_path: /assets/images/ccsp68x68.svg
    alt: "ccsp"
feature_services_title:
  - image_path: /assets/images/services.svg
    alt: "aws"
gallery_services:
  - image_path: /assets/images/audit68x68.svg
    alt: "audit"
    title: "Infrastructure Security"
    excerpt: "Blockchain Infrastructure Security and Audit."
  - image_path: /assets/images/automation.svg
    alt: "automation"
    title: "NodeOps"
    excerpt: "Build Blockchain Infrastructure with devops and automation."
---
{% include feature_row %}

{% include feature_row id="feature_certificate_title" type="left" %}
{% include gallery id="gallery_certificate" layout="fourth" %}
{% include feature_row id="feature_services_title" type="left" %}
{% include gallery_row id="gallery_services" layout="fourth" %}

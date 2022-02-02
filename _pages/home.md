---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/mm-home-page-feature.jpg
excerpt: >
  A group of security and automation professionals aiming to build and safeguard Blockchain infrastructure.<br />
feature_certificate_title:
  - title: "Certificate"
feature_certificate:
  - image_path: /assets/images/aws.svg
    alt: "aws"
  - image_path: /assets/images/gcp.svg
    alt: "gcp"
  - image_path: /assets/images/azure.svg
    alt: "azure"
  - image_path: /assets/images/ccsp.svg
    alt: "ccsp"
feature_services:
  title: "Services"
  - image_path: /assets/images/audit.svg
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
{% include feature_row id="feature_certificate" type="center" %}
{% include feature_row id="feature_services" type="center" %}

---
title: Autotune Release Notes
sidebar: mydoc_sidebar
permalink: autotune_release_notes.html
folder: mydoc
---

## Kruize Version 0.4

You can get it from
quay.io/kruize/autotune_operator:0.4
docker.io/kruize/autotune_operator:0.4
Branch: master, Tag: v0.4
Commit id: 58b8bf8c2feb9b5ca1719a4f7d11faf41b2fea47

## Major changes include

[Deploy] 
[API] Add support for MetadataProfile
[API] New Bulk API format related to kafka changes
[API] Alpha level support for GPU autoscaling (MIG right-sizing) with Instaslice integration
[API] Add config support for single term and single model to be specified in createExperiment API
[API] Autoscaler to use custom term and model specified in createExperiment API
[Bug] VPA Integration validation checks
[Bug] Dynamically calculate threshold value for term
[Bug] Update ubi-minimal with latest
[Bug] Fix RBAC error in Kruize log
[Bug] 
[Demo] Bulk demo UX updates
[Demo] GPU Demo for instaslice inetgration
[Tests] Add stress tests for bulk API
[Tests] Add VPA testing


**Full Changelog**: https://github.com/kruize/autotune/compare/v0.3...v0.4

## Kruize Version 0.3!

You can get it from
quay.io/kruize/autotune_operator:0.3
docker.io/kruize/autotune_operator:0.3
Branch: master, Tag: v0.3
Commit id: 0d8bf0cbf492eaf2fe230f67a64d7e2ef2f6a1a1

## Major changes include

[Deploy] Add isROSEnabled flag to enable remote_monitoring
[API] Support concurrent remote_monitoring & local_monitoring
[API] Bulk API filtration support
[API] Bulk API timer support
[API] Auto mode support in Kruize for VPA integration PoC
[Bug] Jetty server upgrade to address CVE
[Bug] Better bulk API error handling
[Bug] Fix no data available issue in generate recommendations
[Bug] Fix listing experiments to display recommendations for both container & namespace
[Demo] VPA demo & Bulk demo UX updates
[Demo] Demo updates for concurrent remote_monitoring & local_monitoring
[Tests] Test updates for concurrent remote_monitoring & local_monitoring

**Full Changelog**: https://github.com/kruize/autotune/compare/v0.2...v0.3


## Older Versions

Click here: https://github.com/kruize/autotune/releases 


{% include links.html %}

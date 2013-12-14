jQueryCrossProtocol
===================

Lets find a way to help our students avoid the cross protocol jquery loading issue they all get.

# Issue:
  jQuery loading issues when on local (file://) vs http: vs https://

## Description:
When students are first learning jquery, we direct them to add a script tag with a source on the google cdn. This causes an error when they try to load it from the file:// protocol. I have seen at least a dozen students have this problem in the last 6 months or so. 

## Potential Solutions (easiest first)
1. We should change the project structures so that they download the file into a local folder. I know file systems and downloading js is an issue for some, but there can be a quick walkthrough document that they can go through.

2. A solution like the one Google Analytics uses to load. The files are in the repo. The main issue with this is that it is a bit messy and adds an onload handler to the body tag. Please let me know how we can improve this.

Thanks,

Tomas
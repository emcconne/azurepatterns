---
layout: post
title:  Publish Jekyll with Azure DevOps
date: 2019-08-12
summary: |
 Publish a Jekyll website to Azure Storage Account using Azure DevOps
tags: azure website devops
---
In this post we'll look at how to setup Azure DevOps to monitor a GitHub 
repository that contains a Jekyll website and compile and publish the website on
every commit to master.


## Problem
How do we use Azure DevOps to monitor a GitHub Jekyll repository and compile
every change to the master branch and publish those changes to our Storage
Account we setup in previous posts.


## Solution 

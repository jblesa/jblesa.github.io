---
title: "Release cadidates branches strategy"
date: 2026-04-08T10:00:00+02:00
lastmod: 2026-04-08T10:00:00+02:00

# Categorization
tags: ["git", "release candidate", "branch", "strategy"]
categories: ["programming"]

# SEO & social
description: "Advantages and hhow to apply a RC branches strategy."

# Display
author: "Javi"
cover:
  image: "images/cover.jpg"
  alt: "Cover description"
  caption: "Optional caption"

# Optional but useful
toc: true                      # table of contents
weight: 0                      # for ordering within a section
math: false                    # enable KaTeX/MathJax if your theme supports it
---

# Introduction

The release candidate branches strategy consists of creating specific branches in the Git repository that represent versions considered ready for release. These branches are created from the main development branch at a given point in time, when the set of features is mature enough to prepare a delivery.

In these branches, feature branches that have already passed initial testing are integrated and subjected to a more exhaustive validation cycle: integration tests, regression tests, quality checks, and final reviews. If the candidate version meets the quality criteria, it becomes the official release that goes into production. If issues are found, they are fixed directly in the candidate branch, preventing unstable changes from contaminating the main development flow.

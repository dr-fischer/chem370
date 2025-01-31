---
layout: default
title: Data Processing
nav_order: 3
permalink: /project/faas/data-processing
has_toc: true
parent: FAAS
grand_parent: Project (e-Cigarettes)
last_modified_date: 2020-12-26
---

# FAAS Data Processing
{: .no_toc  }

----

<details open markdown="block">
  <summary>
  Table of Contents
  </summary>

  {: .text-delta }
1. TOC
{:toc}
</details>

The following video walks you through the data processing portion of this lab.

<div class = "tip">
You should turn a ZIP folder containing:  (1) your complete lab notebook as an .html and .jl file functioning with no errors, (2) your data files, (3) your completed assessment.
</div>

<iframe src="https://wcu.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=733fb481-8a20-4369-bf3c-ac67011c358e&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" height="405" width="720" frameBorder = "0" style="border: 0px solid #464646; display: block; margin: 15px;" allowfullscreen allow="autoplay"></iframe>

## Organize and Import Your Data

1. Create a folder for this lab on your computer.
1. Paste your data file into the folder.
1. Import the data using `CSV.read()`.

## Create a standard Curve

1. Use Julia to fit and plot a standard curve.

## Determine the Concentration of Your Samples

1. Determine the concentration of your samples and QCs.  Remember to factor in all dilutions.
1. Use the confidence intervals or a *t*-test (whichever you prefer) to determine whether the metal concentration is *significantly* different before and after vaping. (See [Useful Information > Comparing Means]({{site.url}}/useful-info/statistics#comparing-means) for more information.)

## Validate Your Results

1. Determine the concentration of the QC.
1. Determine the percent difference from the expected value.
1. Determine your LOD and LOQ.

## Save & Turn In Your Work

1. Save your work as a .jl (Julia) file and .html (static HTML).
1. Compress your entire lab notebook including the .jl, .html, and .csv files into a ZIP file.
1. Attach the ZIP file to the MS Teams assignment for this lab when turning it in.

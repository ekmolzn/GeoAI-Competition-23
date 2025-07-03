# GeoAI Competition: The Hyperspectral Imaging Challenge

**Date:** 12 November 2023

**Team Name:**  
MTTDATA

**Team Members:**  
- Brock Bennett
- Isabella Lieberman
- John Ramirez
- Nathan Zlomke

## Table of Contents
1. [EXECUTIVE SUMMARY](#Executive-Summary) 
2. [COMPANY OVERVIEW](#Company-Overview) 
3. [PROBLEM STATEMENT](#Problem-Ptatement)  
4. [AN OVERVIEW OF HYPERSPECTRAL IMAGING](#An-Overview-of-Hyperspectral-Imaging) 
5. [MODELING](#Modeling)  
6. [INSIGHTS & RECOMMENDATIONS](#Insights-Recommendations)  
7. [APPENDICES](#Appendices)  
    - [APPENDIX A](#Appendix-a)  
    - [APPENDIX B](#Appendix-b)


## Executive Summary

ESA Φ-lab, in collaboration with KP Labs and their partner QZ Solutions, has launched an extraordinary initiative that is set to transform the future of agriculture by leveraging in-orbit processing. The primary goal is to enhance farm sustainability by utilizing the latest advancements in Earth observation and artificial intelligence. This approach not only helps address the challenge of affordable food production but also contributes to environmentally friendly agriculture practices.

One of the key aspects is providing farmers with timely information about soil parameters to optimize their fertilization processes. This optimization can lead to the selection of more suitable fertilizer mixes and reduce overall fertilizer usage. Currently, the traditional method for quantifying soil parameters is labor-intensive and time-consuming. It involves collecting soil samples in the field and sending them to be specialized labs for chemical analysis. Moreover, the limited number of sampling points in the field, often spread across large areas, compromises the accuracy of test results. In-situ analysis is not scalable and is highly time-inefficient.
The proposed solution is to harness cutting-edge airborne and satellite hyperspectral imaging technology to promote more sustainable agriculture practices, ultimately contributing to a better future for our planet.

## Company Overview

AI for Good is organized by ITU in partnership with 40 UN Sister Agencies. The goal of AI for Good is to identify practical applications of AI to advance the United Nations Sustainable Development Goals and scale those solutions for global impact. It is the leading action-oriented, global & inclusive United Nations platform on AI.

## Problem Statement

The objective of this challenge is to advance the state-of-the-art in soil parameter retrieval from hyperspectral data in preparation for the forthcoming Intuition-1 mission. In March 2021, a campaign was conducted over agricultural regions in Poland, involving extensive ground samplings that were coordinated with airborne hyperspectral measurements from sensors mounted on an aircraft. The hyperspectral data consists of 150 contiguous hyperspectral bands spanning from 462 to 942 nm, with a spectral resolution of 3.2 nm, matching the spectral range of the hyperspectral imaging sensor aboard Intuition-1.

Intuition-1 is a 6U-class satellite mission developed by KP Labs, designed to observe Earth using a hyperspectral instrument and an on-board computing unit equipped for in-orbit data processing using artificial intelligence. It will be the world's first satellite with the processing power required for advanced analysis of hyperspectral images in orbit.

In this challenge, the primary aim is to automatically estimate specific soil parameters, including potassium (K), phosphorus pentoxide (P2O5), magnesium (Mg), and pH.

## An Overview of Hyperspectral Imaging

### Summary of Hyperspectral Imaging

Hyperspectral imaging is a technique that collects and processes information across the electromagnetic spectrum to obtain the spectrum for each pixel in an image. This allows for the identification of objects and materials by analyzing their unique spectral signatures. Applications of hyperspectral imaging include food quality & safety, waste sorting and recycling, and control and monitoring in pharmaceutical production.

### Background Research

According to Specim, “Hyperspectral imaging is an increasingly used technique in industry, research, and remote sensing. The data provided by hyperspectral imaging systems can be used during inspection to locate, sort, or quantify the concentration of various materials that are invisible to common cameras or the human eye.”

## Modeling

Chemometric Models that were considered were partial least squares (PLS) regression, support vector regression (SVR), or convolutional neural networks (CNN). To find relationships between the spectral data and the soil properties with the calibration data in mind, we would explore the usage of the chemometric models.

### Data Exploration

![Figure 1: Initial distributions of Potassium (K), Magnesium (Mg), Phosphorous (P), and pH.](Figure_1.png)  
_Figure 1: Initial distributions of Potassium (K), Magnesium (Mg), Phosphorous (P), and pH._

## Insights & Recommendations

According to the Climate Change Post, adequate potassium in soil can improve water use efficiency in plants, and

Thank you for your time and attention, please [click here](#Table-Of-Contents)

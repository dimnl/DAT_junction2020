<img src="./DAT.png" alt="DAT" title="DAT" align="right" width="250" />

# DAT_junction2020
Submission for Junction 2020 Connected

## Introduction

Opetushallitus is a Finnish governmental body responsible for Education; it  has lots of data regarding state funding for projects and activities in the educational domain. All this data is very messy, disorganized and in general not used though. Besides that, the outcomes and achievements of the projects are often evaluated by internal surveys that Opetushallitus does not know about. 


## Problem

The data is not accessible to the public in a clear and concise matter. The goal of Opetushallitus is to serve the public and it could improve in this aspect. 

Furthermore, the data is not used to its potential; internal data-informed decision-making could be used to improve the effective allocation of funds.

## Solution

We introduce the DA(T)shboard as a solution; an intuitive screen filled with visualizations to actually see what is happening with these funded projects. Everyone will be able to access and see what is happening: teachers, students, parents, you name it! The dashboard is free to use for transparency and has extra options for the decision making of future project proposals of Opetushallitus. 

### Implementation

The different projects are extracted from the dataset as well as their focus areas and funding. Furthermore, additional datasets are extracted from the organizations of the projects to evaluate the outcome; these are subsequently linked semantically.

As it is assumed that the outcomes will be in the form of text (and not concrete values), we use sentiment analysis using natural language processing. This classifies the text as either "positive", "neutral" or "negative". A machine could thus identify the outcomes automatically under the guidance of human supervision.

#### Development

The data has been traversed and translated manually, which resulted in [this image](https://raw.githubusercontent.com/dimnl/DAT_junction2020/main/data_structure/data_structure.svg) showing the data structure of the parts identified as most relevant from the dataset. This diagram has been made in MarkDown using [Mermaid](https://mermaid-js.github.io/mermaid/#/). 

A sample was chosen, after initial exploration, to focus on and show the potential of the dataset. The visualization has been done with this sample with the help of Flourish and Canva. [The demo](https://www.canva.com/design/DAEM31mo9WE/view) shows a future usage of the the dashboard and its use-cases.

#### Possible roadblocks along the way

 - Combinations of datasets without certain identifying keys is inexact and has a margin of error, which could be too high;
 - Not all data is consistent, it could be impossible to get a complete overview;
 - Outcomes of projects could be hard to gather from the organization that did the project.

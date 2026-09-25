---
title: 'CanadaWildfireDaily: A Dataset and Benchmark for Daily Wildfire Spread in Canada'
layout: default
---

<p class="teaser"> <img src="assets/CanadaWildFireDaily_overview.png" width="85%" alt="Overview of the CanadaWildFireDaily dataset"/>
</p>

## Abstract

<p class="abstract">
<!-- TODO: replace with the paper's abstract -->
CanadaWildfireDaily is a large-scale dataset and benchmark for daily wildfire spread prediction across Canada, designed to support research on forecasting the evolution of active wildfires. It pairs daily satellite-derived fire perimeters with weather, fuel, and terrain covariates, and provides standardized train/val/test splits along with baseline models to enable reproducible comparison of spread-prediction methods.
</p>

## Dataset and code

The dataset is available for [download](https://huggingface.co/datasets/CanadaWildFireDaily/CanadaWildFireDaily-v1), and we release the [code](https://github.com/hagerradi/CanadaWildFireDaily) for building the dataset in other regions of the world and for the benchmark.

## Authors

<div class="authors" id="authors">
{%- for person in site.data.authors -%}
<div class="person">
  {%- if person.image and person.image != "" -%}
  <img src="{{ person.image }}" alt="{{ person.name }}"/>
  {%- else -%}
  <span class="avatar-fallback">{{ person.name | slice: 0 }}</span>
  {%- endif -%}
  {%- if person.url and person.url != "" -%}
  <a href="{{ person.url | relative_url }}">{{ person.name }}</a>
  {%- else -%}
  <span>{{ person.name }}</span>
  {%- endif -%}
  <span>{{ person.title | replace: '&', '<br>' }}</span>
</div>
{%- endfor -%}
</div>

<p>
For questions, please contact us at:
<a href="mailto:hager.radi@mila.quebec">hager.radi@mila.quebec</a>
</p>

## Citation

<div class="citation-block">
Coming soon
</div>

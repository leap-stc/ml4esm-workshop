---
layout: default
---

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project. -->

<!-- > This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor. -->


<!-- ```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
``` -->

# Workshop summary

<p align="center">
  <img src="ClimSim.jpg" alt="ClimSim" width="500"/>
</p>

Climate change is a major concern for human civilization, yet significant uncertainty remains in future warming, change in precipitation patterns, and frequency of climate extremes. Proper adaptation and mitigation demands accurate climate projections capable of simulating the atmosphere, ocean, land, and their interactions. Numerical models exhaustively tuned by domain scientists have been the gold standard for modeling both weather and climate because of their interpretability
and ability to simulate “what-if” scenarios not present in the historical record. Although AI forecasts have made operational progress in weather prediction, climate projections are a harder problem. For example, High Impact-Low Likelihood events are undersampled in ERA5 reanalysis
data, and substantial decadal variability in modes of climate variability (like the El-Niño Southern Oscillation) limit the ability of AI forecasts to reliably extrapolate into the future.
This workshop seeks to accelerate progress on using machine learning to improve climate projections,
emphasizing areas that domain scientists have deemed amenable to machine learning approaches. Examples include hybrid physics-ML climate models, where machine learning is used to emulate subgrid
processes too expensive to resolve explicitly, and dynamical downscaling, where high-resolution climate
variables are inferred from coarse-resolution models in a physically consistent manner.
In service of this, our workshop will be accompanied by a $50,000 Kaggle competition on the ClimSim
dataset [ClimSim](https://leap-stc.github.io/ClimSim/), which won the Outstanding Datasets and Bench-
marks Paper award at NeurIPS 2023.


We welcome submissions on machine learning topics that can advance earth system model development. Some examples include deep generative models, explainable AI, physics-informed neural networks,
and uncertainty quantification. While machine learning is not new to the climate science community,
dedicated opportunities for cross-fertilization of ideas are rare, and machine learning experts motivated to
make an impact may not be aware of domain science research directions most in need of their expertise.
This workshop directly addresses both of these challenges.

# Workshop time and location

ICML 2024

July 26, 2024 or July 27, 2024 (TBD)

Vienna, Austria

# Workshop format

This program consists of invited and contributed talks, two poster sessions, and
a panel discussion. Talks and accepted papers will be viewable on YouTube and OpenReview, respectively.
Links to papers, posters, and talks will be hosted on our website (see table below). Invited talks and panel
discussion will be in-person. Contributed talks will be in-person or virtual, and the poster sessions will
be in-person. Our invited speakers consists of both climate science and machine learning experts. The
morning session consists of talks discussing areas where machine learning has already advanced climate
science. The afternoon session consists of talks on SOTA machine learning techniques with high applicability to climate science. There are six invited 20 minute talks and six contributed 12 minute talks, with
5 and 3 minutes for live Q&A, respectively. Questions for talks and the panel discussion will be taken
in-person and virtually. All speakers have been confirmed. A schedule can be found in the table below.


# Diversity Commitment

We are dedicated to ensuring our workshop is accessible and welcoming to all. Speakers, panelists, and organizers for this workshop are composed of domain scientists and machine learning
experts that span multiple countries and are balanced across gender. We seek contributions from all
backgrounds, and we especially encourage submissions from underrepresented groups.

# Previous related workshops

The most similar workshops are the AI 4 Earth Sciences workshop hosted at
NeurIPS in 2020 and the AI 4 Earth and Space Science workshop hosted at ICLR in 2022. There is some
overlap with Climate Change AI’s Tackling Climate Change with Machine Learning NeurIPS and ICLR
workshops (hosted since 2019) and the AI 4 Differential Equations workshop hosted this year at ICLR.
The organizers of this workshop have been informed that Climate Change AI does not plan on hosting a
workshop this year at ICML.

This workshop distinguishes itself from previous workshops by orienting itself around a public competition meant to draw in machine learning experts on a well-defined, long-standing climate science problem using a dataset and paper accepted in the 2023 Neurips Datasets and Benchmarks track. This serves as a foothold for machine learning experts to help drive progress in other open problems in earth system modeling. We also intentionally invited experts at the direct intersection of physics (turbulent flow, molecular dynamics, etc.) and machine learning to provide fundamental, first-principles insight into the challenges of generalizing data-driven methods in the physical domain of climate models. Unlike previous workshops, our emphasis is on using advances in this intersection to accelerate the development of the next generation of climate models and bring much-needed clarity for our warming future. Finally, we expect that advances in machine learning methods made to allow them to dynamically and predictably interact with physical models have promising potential to push the field of AI itself forward in new and unexpected directions.

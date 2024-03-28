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

July 26, 2024 or July 27, 2024 (TBD)
Vienna, Austria

# Call for papers

We are currently accepting submissions of short papers investigating machine learning techniques with the potential to advance earth system modelling. Topics include but are not limited to:

- hybrid physics-ML climate modelling
- full model emulation for weather and climate
- differentiable climate modelling
- dynamical downscaling
- uncertainty quantification
- anomaly detection
- parameter estimation for climate models

The deadline for all submissions is June 17, 2024 (AOE).

# Submission requirements

Papers must be 4 pages long, and author names must be omitted prior to submission. Submissions must clearly articulate applications relevant to earth system modelling. Accepted papers will be invited to give poster presentations, and a total of six will be invited to give spotlight talks. 

# Review Process

The review process for this workshop is double-blind, and we are accumulating a pool of reviewers with relevant expertise.

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

# Schedule

This workshop is divided into 5 main sections:

1. **Introduction**: This section sets the theme of the workshop and also reviews ClimSim, a paper and dataset accepted in the Neurips 2023 Datasets and Benchmarks Track used for the competition.

2. **Spotlight ClimSim submissions**: This section covers spotlight talks and a poster session for exceptional submissions to the upcoming ClimSim competition.

3. **Advancing the Domain**: This section covers cases of how machine learning is changing the underlying domain science of earth system modeling.

4. **New Directions**: This section discusses ways in which advancements in physics-guided machine learning can manifest in future breakthroughs for earth system modeling.

5. **Panel Discussion**: The panel discussion seeks to bring everything together for a thoughtful discussion on how machine learning will continue to advance the future of earth system modeling given existing opportunities for low-hanging fruit and promising new directions.

_All listed speakers have been confirmed._ The coffee breaks, poster sessions, Q&A sessions, and panel discussion will serve as opportunities for broad discussion. Invited speakers will be expected to give 20-minute talks with 5 minutes left for Q&A, where questions are taken from invited speakers. For the panel discussion, questions will be taken from online and in-person attendees.


| Time             | Event                                                                                                      |              
|:----------------|:-----------------------------------------------------------------------------------------------------------|
| 9:00-9:10        | Introduction and Opening Remarks [[Jerry Lin](https://www.linkedin.com/in/jerry-lin-3a8801104/)]           |
| 9:10-9:35         | *Advancing the Domain* Invited Talk [[Kara Lamb](https://datascience.columbia.edu/people/kara-lamb/)]  |                               | 
| 9:35-10:00         | *Advancing the Domain* Invited Talk  [[Maria Molina](https://mariajmolina.github.io/)]   |
| 10:00-10:25        | *Advancing the Domain* Invited Talk  [[Stephan Mandt](http://www.stephanmandt.com/)]   |
| 10:25-11:15        | Poster Session 1 |
| 11:15-12:00        | *Advancing the Domain* Contributed Talks (3) |
| 12:00-1:00        | Networking Lunch |
| 1:00-1:15        | *New Directions* Invited Talk [[Aditi Krishnapriyan](https://a1k12.github.io/)] |
| 1:15-1:30        | *New Directions* Invited Talk [[Nils Thuerey](https://ge.in.tum.de/about/n-thuerey/)] |
| 1:30-1:45        | *New Directions* Invited Talk [[David Rolnick](https://davidrolnick.com/)] |
| 1:45-2:35        | Poster Session 2 |          
| 2:35-3:50        | *New Directions* Contributed Talks (3)          |
| 3:50-4:00        | Coffee Break          |
| 4:00-5:00        | Panel Discussion          |
End                                                                                                        | End                           |

# Invited Speakers and Panelists

<div class="speakers-grid">

<div class="speaker">
<h2>Kara Lamb <br>(Columbia University, US)</h2>

<div class="speaker-img"><div style="background-image: url('photos/KaraLamb.jpeg')"></div></div>

<p><a href="https://datascience.columbia.edu/people/kara-lamb/">Kara Lamb (she/her)</a> is an Associate Research Scientist at Columbia University
in the NSF Learning the Earth with Artificial Intelligence and Physics (LEAP) Center and collaborates
with researchers at NASA GISS on the NASA Digital Twins for Climate Science Project. Her research
lies at the intersection of observations (from laboratory and field studies) and high-resolution modeling,
with the goal of improving climate model parameterizations of aerosol and cloud processes. She combines
traditional process-based approaches with data science, scientific machine learning, and reduced-order
modeling. She was on the science team for the NASA KORUS-AQ and AToM aircraft campaigns and
the NOAA FIREX Firelab study, was the lead mentor for the 2022 Frontier Development Laboratory
Europe challenge on Aerosols, and is a member of the AMS STAC Committee on AI Applications to
Environmental Science.</p>
</div>

<div class="speaker">
<h2>Julia Kaltenborn <br>(McGill University & Mila Quebec AI Institute)</h2>
<div class="speaker-img"><div style="background-image: url('photos/JuliaKaltenborn.png')"></div></div>

<p><a href="https://juliakaltenborn.github.io/"> Julia Kaltenborn (she/her)</a> is a PhD student at McGill University and the Mila-Quebec AI Institute. She explores machine learning for climate model emulation and cryospheric sciences. She focuses on creating ML resources that can be used cross-disciplinarily, such as ClimateSet, and developing ML models that are actively used in the field, e.g., by MOSAiC, the largest polar expedition in history. Julia co-founded the NGO Unser Dialog, co-organized AI Helps Ukraine, and was a local Greenpeace leader in her youth. She has been a fellow of the German Academic Scholarship Foundation, received the Mitacs Globalink Research Fellowship, and was a DeepMind scholar. Last but not least, Julia was a member of the Juneau Icefield Research Expedition 2023 and has traversed the Juneau Icefield. </p>
</div>

<div class="speaker">
<h2>Stephan Mandt <br>(University of California, Irvine, US)</h2>

<div class="speaker-img"><div style="background-image: url('photos/StephanMandt.jpg')"></div></div>

<p><a href="http://www.stephanmandt.com/">Stephan Mandt (he/him)</a> is an Associate Professor of Computer
Science and Statistics at the University of California, Irvine. From 2016 until 2018, he was a Senior
Researcher and Head of the statistical machine learning group at Disney Research in Pittsburgh and
Los Angeles. He held previous postdoctoral positions at Columbia University and Princeton University.
Stephan holds a Ph.D. in Theoretical Physics from the University of Cologne, where he received the
German National Merit Scholarship. He is furthermore a recipient of the NSF CAREER Award, the UCI
ICS Mid-Career Excellence in Research Award, the German Research Foundation’s Mercator Fellowship,
a Kavli Fellow of the U.S. National Academy of Sciences, a member of the ELLIS Society, and a former
visiting researcher at Google Brain. Stephan is an Action Editor of the Journal of Machine Learning
Research and Transaction on Machine Learning Research and currently serves as Program Chair for AIS-
TATS 2024.</p>
</div>

<div class="speaker">
<h2>Aditi Krishnapriyan <br>(University of California, Berkeley, US)</h2>

<div class="speaker-img"><div style="background-image: url('photos/AditiKrishnapriyan.png')"></div></div>

<p><a href="https://a1k12.github.io/">Aditi Krishnapriyan (she/her)</a> is an assistant professor of
Chemical Engineering and EECS at UC Berkeley where she is also a member of Berkeley AI Research
(BAIR) and part of the AI+Science group in EECS and the theory group in Chemical Engineering.
She is interested in developing methods in machine learning that are driven by the distinct challenges
and opportunities in the natural sciences, with particular interest in physics-inspired machine learning
methods. Some areas of exploration include approaches to incorporate physical inductive biases (such
as symmetries, conservation laws) into ML models to improve generalization for scientific problems, the
advantages that ML can bring to classical physics-based numerical solvers (such as through end-to-end
differentiable frameworks and implicit layers), and better learning strategies for distribution shifts in the
physical sciences. </p>
</div>

<div class="speaker">
<h2>Nils Thuerey <br> (Technical University of Munich, Germany)</h2>

<div class="speaker-img"><div style="background-image: url('photos/NilsThuerey.jpg')"></div></div>

<p><a href="https://ge.in.tum.de/about/n-thuerey/">Nils Thuerey (he/him)</a> is an associate professor at the
computer science department of the Technical University of Munich (TUM) where he leads a research
group working on deep learning methods for physical simulations, with an emphasis on fluid flow prob-
lems. He has co-authored a freely available, Jupyter based textbook on physics-based deep learning, and
his group has pioneered novel methods for improving the stability, rollout, and physical consistency of
neural network-based PDE solvers. He is especially interested in solvers that employ traditional numerics
alongside learned components, and, more recently, in leveraging diffusion modelling for improved neural
simulations. </p>
</div>

<div class="speaker">
<h2>David Rolnick <br>(McGill University & Mila Quebec AI Institute)</h2>

<div class="speaker-img"><div style="background-image: url('photos/DavidRolnick.jpg')"></div></div>

<p><a href="https://davidrolnick.com/">David Rolnick (he/him)</a> is an Assistant Professor and
Canada CIFAR AI Chair in the School of Computer Science at McGill University and at Mila Quebec AI
Institute, where his work focuses on applications of machine learning to help address climate change. He
is a Co-founder and Chair of Climate Change AI and Scientific Co-director of Sustainability in the Digital
Age. Dr. Rolnick received his Ph.D. in Applied Mathematics from MIT. He is a former NSF Mathematical
Sciences Postdoctoral Research Fellow, NSF Graduate Research Fellow, and Fulbright Scholar, and was
named to the MIT Technology Review’s 2021 list of “35 Innovators Under 35. </p>
</div>

</div>

# Organizers

<div class="speakers-grid">
<div class="speaker">
<h2>Ritwik Gupta <br>(UC Berkeley)</h2>

<div class="speaker-img"><div style="background-image: url('photos/RitwikGupta.jpg')"></div></div>

<p><a href="https://ritwikgupta.me/">Ritwik Gupta (he/him)</a> is a Ph.D.
student at the University of California, Berkeley. His research focus is on computer vision for humanitarian assistance and disaster response, as well as the development of policies related to the use of machine
learning in developing areas. His research has been used widely by organizations such as the United Nations, CAL FIRE, and the International Red Cross. Ritwik is a Graduate Fellow with the Berkeley Risk
and Security Lab, a Research Fellow at Berkeley's Human Rights Center, and a Fellow at Berkeley's AI
Policy Hub. Ritwik is the Director of the Berkeley AI Research Climate Initiative which brings together
researchers to work on AI research through the lens of climate change and helps to translate that work
into real-world applications.</p>

<b>ritwikgupta [at] berkeley [dot] edu</b>
<b><a href="https://scholar.google.com/citations?user=4Cdwp_MAAAAJ&hl=en">Google Scholar</a></b>
</div>

<div class="speaker">
<h2>Laura Mansfield <br> (Stanford University)</h2>

<div class="speaker-img"><div style="background-image: url('photos/LauraMansfield.jpg')"></div></div>

<p><a href="https://profiles.stanford.edu/laura-mansfield">Laura Mansfield (she/her)</a> is a postdoctoral researcher at
Stanford University. Her research focuses on Bayesian statistics and machine learning methods for the
development of subgrid-scale gravity wave parameterizations in climate models, in order to improve the
representation of stratospheric dynamics. She works on both the calibration and uncertainty quantification of conventional and on machine learning parameterizations. She completed her Ph.D. in Gaussian
processes for climate change projection from the University of Reading and Imperial College London in
2021. She is the convener for the AGU session on Machine Learning Subgrid-Scale Parameterizations.
She will be participating virtually.</p>

<b>lauraman [at] stanford [dot] edu</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=edNb_cUAAAAJ">Google Scholar</a></b>
</div>


<div class="speaker">
<h2>Tian Zheng <br>(Columbia University)</h2>

<div class="speaker-img"><div style="background-image: url('photos/TianZheng.jpg')"></div></div>

<p><a href="https://stat.columbia.edu/~tzheng/">Tian Zheng (she/her)</a> is Professor and Department
Chair of Statistics at Columbia University. She is Chief Convergence Officer and Education Director of
the NSF Science Technology Center “Learning the Earth with AI and Physics”. In her research, she develops novel methods for exploring and understanding patterns in complex data from different application
domains such as biology, psychology, climate modeling, etc. In 2016, she designed Applied Data Science,
a project-based learning course that offers mini data-intensive challenges. She was Associate Director for
Education at Columbia’s Data Science Institute from 2017 to 2020 and a faculty advisor for Columbia
Statistics Club from 2016 to 2021. She has organized and served as a judge in 10+ data competitions and
hackathons. </p>

<b>tian.zheng [at] columbia [dot] edu</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=-4J-KZoAAAAJ">Google Scholar</a></b>
</div>

<div class="speaker">
<h2>Margarita Geleta <br> (UC Berkeley & Stanford University)</h2>

<div class="speaker-img"><div style="background-image: url('photos/MargaritaGeleta.jpeg')"></div></div>

<p><a href="https://margaritageleta.github.io">Margarita Geleta (she/her)</a> is a Ph.D. student at the University of California, Berkeley, affiliated with Berkeley AI Research (BAIR) and the Stanford Biomedical Data Science Department (Stanford DBDS). She
has led research on multimodal deep steganography at the Image Processing Group (UPC), developed
algorithms for genotype compression, simulation, and imputation in the Bustamante Lab at the Stanford
School of Medicine, and interned at Amazon.com as an Applied Scientist. In addition to teaching at
UPC, UC Irvine, and tech academies, Margarita has organized workshops and career fairs with +200
participants and co-organized Europe’s biggest student hackathon with +700 participants. She will be
participating virtually.</p>

<b>geleta [at] berkeley [dot] edu</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=jv-xu10AAAAJ">Google Scholar</a></b>
</div>


<div class="speaker">
<h2>Jerry Lin <br>(UC Irvine)</h2>

<div class="speaker-img"><div style="background-image: url('photos/JerryLin.jpg')"></div></div>

<p><a href="https://www.linkedin.com/in/jerry-lin-3a8801104/">Jerry Lin (he/him)</a> is a PhD candidate at UC Irvine
and graduate research assistant in the NSF Learning the Earth with Artificial Intelligence and Physics
(LEAP) Center working on neural network emulators of convection and radiation coupled inside climate
models. His current work involves developing and coupling stochastic parameterizations, and he previously developed push-button capabilities for multi-hundred ensemble tests for coupled hybrid physics-ML
climate simulations. He is a co-author and active maintainer for ClimSim and an organizer for the upcoming Kaggle competition. He has previously managed a student-run data science course at UC Berkeley. </p>

<b>jerryL9 [at] uci [dot] edu</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=r8zHDdMAAAAJ">Google Scholar</a></b>
</div>


<div class="speaker">
<h2>Yongquan Qu <br>(Columbia University)</h2>

<div class="speaker-img"><div style="background-image: url('photos/YongquanQu.jpg')"></div></div>

<p><a href="https://yongquan-qu.github.io">Yongquan Qu (he/him)</a> is a Ph.D. candidate at Columbia
University. His primary research delves into the intersection of scientific machine learning and computational methods, aiming to enhance the modeling and understanding of turbulence in the atmospheric
boundary layer. He also works on developing a hybrid framework that integrates probabilistic machine
learning with data assimilation in the context of climate projections. He is a graduate research assistant
of the NSF Science and Technology Center “Learning the Earth with Artificial Intelligence and Physics”
(LEAP). He is also affiliated with the “Multiscale Machine Learning In Coupled Earth System Modeling”
(M2LInES) project - an international collaborative project to improve climate models with scientific machine learning. He will be participating virtually.</p>

<b>yq2340 [at] columbia [dot] edu</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=LnBGvRoAAAAJ">Google Scholar</a></b>
</div>



<div class="speaker">
<h2>Maja Rudolph <br>(Bosch Research)</h2>

<div class="speaker-img"><div style="background-image: url('photos/MajaRudolph.jpg')"></div></div>

<p><a href="http://maja-rita-rudolph.com">Maja Rudolph (she/her)</a> is a Senior Research Scientist at the
Bosch Center for Artificial Intelligence, where she works in the field of deep probabilistic modeling. She
completed her Ph.D. in Computer Science at Columbia University, advised by David Blei, in 2018. Maja
holds an MS in Electrical Engineering from Columbia University and a BS in Mathematics from MIT.
Her research lies at the intersection of Bayesian machine learning and deep learning, with a focus on
deep probabilistic sequence models, neural transformation learning, and embedding methods. She will be
participating virtually. </p>

<b>marirudolph [at] gmail [dot] com</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=QW_JZnsAAAAJ">Google Scholar</a></b>
</div>

<div class="speaker">
<h2>Mike Pritchard <br>(NVIDIA corporation & University of California, Irvine)</h2>

<div class="speaker-img"><div style="background-image: url('photos/MikePritchard.jpeg')"></div></div>

<p><a href="https://research.nvidia.com/person/mike-pritchard">Mike Pritchard (he/his)</a> is the Director of Climate Simulation at NVIDIA, an associate professor of
Earth System Science at UC Irvine, and the Institutional Integration Director for the NSF Learning the
Earth with Artificial Intelligence and Physics (LEAP) Center. He works at the interface between next-
generation climate simulation and machine learning. His main focus is on accelerating cloud-resolving climate simulations using physics-informed machine learning. He is also interested in reinforcement learning
approaches to climate model calibration, understanding the limits of autoregressive weather simulations
trained on observational data, and AI-assisted low-latency analysis of large high-resolution climate simulation datasets. He will be participating virtually. </p>

<b>mpritchard [at] nvidia [dot] com</b>
<b><a href="https://scholar.google.com/citations?hl=en&user=TfyToUUAAAAJ">Google Scholar</a></b>
</div>


</div>






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

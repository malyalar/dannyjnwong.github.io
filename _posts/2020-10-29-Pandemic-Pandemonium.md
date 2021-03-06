---
title: "Pandemic Pandemonium"
author: "Danny Wong"
date: "06 November, 2020"
layout: post
blog: true
tag:
- "COVID-19"
- "thoughts"
- "medicine"
---

What a whirlwind few months it has been since I last [blogged in March 2020](https://dannyjnwong.github.io/UK-COVID-19-Cases/). Back then, the COVID-19 cases were just starting to rise in the UK, following the trends from Italy. Little did we know how rapidly things would escalate, and within a couple of weeks of my post, the UK entered into lockdown as patients with COVID-19 started flooding through the hospital doors.

## Falling ill during the first wave

I was caught up with all the events, beginning to intubate a few patients in the emergency department before our hospital started instituting measures to cope with the influx. It's easy to look back with the benefit of hindsight now, but back then things were extremely confusing and frightening. The first patient I intubated was very unwell and desaturated so quickly after induction of anaesthesia that I was forced to bag them up again, despite the fact we were told to avoid doing so as much as possible. 

Soon after those first few days however, I quickly fell ill myself, and tested positive for COVID-19. My wife also fell ill, and it wasn't clear whether I caught it from my patient interactions at work, or through my wife, who similarly had seen patients in her GP practice with symptoms. More likely than not though, the personal protective equipment (PPE) that I had access to as a hospital anaesthetist meant that I was far better protected than she was, and she was probably the one that caught it and passed it to me. 

The next few weeks were really a blur, were holed up at home, in bed horizontal for most of the time. Our appetites were absent, not least because we couldn't taste anything we ate, but also just that we didn't have the hunger to eat anything. The tickly dry cough at the back of our throats was constant. Those things we could bear with. What was really difficult to tolerate was the near-constant fevers that went away for short bursts when the paracetamol was working, only to come back again like clockwork once the doses ran out of effect. On one of those blurry days I managed to secure a swab test at a drive-through test centre to get myself tested for the virus, this was before the days routine government testing was available to the general public, and so they had to be rationed to health workers via their occupational health service. The test was unsurprisingly positive.

I had 10 days of fevers and shakes, while my wife had 14. We dumped our kids (aged 5 and 3) in front of the television for most days, and took turns lying down on the sofa next to them when the fevers were more bearable. We took to staggering our paracetamol doses in order that we weren't both febrile while having to look after the kids. Those were some bad days. We had both lost about 5kg in weight (don't worry, we have since put them back on), and desaturated to 92% on air (wife is a GP so we have a pulse oximeter at home), but managed to avoid having to go into hospital for oxygen therapy. The kids themselves were also fortunately well for the most part, with the older one only having a mild temperature for 2 days, and the younger one completely unscathed.

As my symptoms eventually resolved, I couldn't help but feel guilty that I was stuck at home while the news of what was happening in hospital filtered through via email and WhatsApp. We sorted out amongst a group of trainees and consultants a plan for redeploying staff to ICU, and I did what I could at home online via my computer, including using my knowledge of R to write some code to assign people to emergency rota slots based on their rankings of those slots. I had also started coming up with the design for the [intubateCOVID](https://intubatecovid.org/) project with a bunch of colleagues at Guy's and St Thomas' just prior to going off sick, so kept working at it to try and gather some data to answer the question of what risks of transmission we as healthcare workers interacting with symptomatic patients were facing. Finally, I was checking the statistics of case numbers so frequently every day that I decided I should write an [R Shiny app to act as my own dashboard of what was going on](https://dannyjnwong.shinyapps.io/COVID/).

## Returning to work

When I was eventually well enough again to go back to work, some 3 weeks after first becoming symptomatic with a fever, I was redeployed to the emergency labour ward rota from the theatre anaesthetic on-call rota. While much of the elective surgical work was suspended during the lockdown, pregnant women were still needing to deliver babies safely. I returned to a world which I scarcely recognised. Processes had changed, and wearing PPE all the time became the norm.

After a few weeks in Labour Ward, I was then rotated to ICU to help with the efforts there, while some of my colleagues who had been redeployed there earlier in the pandemic could come out and decompress. I won't dwell on my time in ICU, there were many sad stories, and some more uplifting ones, but nothing I will write could do ever justice to the events that happened there, and many others would've written better accounts of what it was like in ICU during the first wave.

## Trying to move whilst stuck in treacle

During the lockdown, everyone's plans were up-ended. Including my plans to finally undergo my PhD viva exam. I had submitted my thesis in January to the examiners and the viva was planned for March, delayed till May, and then further delayed till June 26th. Lockdown restrictions were still in place when the final viva date was looming, and so we decided to conduct it all via Zoom, like many of the other activities people now do in this new normal life. Thank goodness I passed. I couldn't bear with another postponement and it felt good that something in life was progressing at least, even if everything else in the world remained on hold. The examiners' comments were useful and I spent the next month correcting the thesis to quickly finalise the PhD. If anybody is interested it's now available [here at the UCL thesis repository](https://discovery.ucl.ac.uk/id/eprint/10108589/), or [here on ResearchGate](https://www.researchgate.net/publication/343968739_Postoperative_critical_care_resource_availability_patient_risk_and_other_factors_influencing_referral_and_admission). I've also decided to share the underlying code for the entire thesis [here on GitHub](https://github.com/dannyjnwong/PhD_Thesis).

While many kids around the country were isolated at home with their parents as schools were shut, fortunately my kids' school remained open for key workers such as my wife and I. This was an absolute Godsend, and I couldn't imagine juggling home schooling, going into hospital to face COVID-19 and also having to finish off the PhD corrections, day-in-day-out. I have huge respect to the teachers and other staff who kept their gates open for those of us who needed their help to continue doing our work on the frontline. In many ways, the pandemic has shown that essential workers aren't just those of us who work in healthcare, but also include teachers, maintenance staff, delivery workers, etc.

## Looking forward

We can probably conclude now that 2020 is a washout. It will be a big asterisk in history, and will mark itself in most people's memories as a terrible year. As I write this, the cases are again rising exponentially across the UK and much of Western Europe, and pressures are starting again to build in the health service. Another lockdown is imminent, and I think it's a question of when and not whether it will happen. I am worried, as many others probably are, about the future. We can only hope it gets better soon.

## Addendum: 6th November 2020

When I started writing this post on the morning of 29th October 2020, I was feeling in a reflective mood as I received a call from my dad that my grandfather was unwell and took a turn for the worst in hospital. He had been admitted to hospital the night before in Malaysia, having spiked a temperature and become short of breath. He was COVID-19 swab negative, and had right lower lobe consolidation essentially had an aspiration pneumonia. He was 94 and had a long list of comorbidities and had not been well for a year or two, bouncing in and out of hospital with recurrent pneumonias. By now he was bed-bound and had such a poor swallow that he was receiving nasogastric feeding and being kept nil by mouth: it wasn't a good quality-of-life by any measure. 

My dad told me my grandfather had deteriorated and was now on intensive care and was receiving non-invasive ventilation. He was clearly not doing well. Despite the NIV, he was not improving and was clearly suffering. Over a Zoom videocall, with over twenty people on the line, we discussed with the ICU physician and a collective decision was made that we should withdraw treatment. He died about two or three hours later. 

The pandemic meant that none of us abroad were able to attend the funeral in Malaysia. Again I had to participate in the funeral events remotely via Zoom over the weekend that followed. Is there anything more emblematic of 2020?


{% highlight r %}
sessionInfo()
{% endhighlight %}



{% highlight text %}
## R version 3.5.2 (2018-12-20)
## Platform: x86_64-w64-mingw32/x64 (64-bit)
## Running under: Windows 10 x64 (build 18363)
## 
## Matrix products: default
## 
## locale:
## [1] LC_COLLATE=English_United Kingdom.1252 
## [2] LC_CTYPE=English_United Kingdom.1252   
## [3] LC_MONETARY=English_United Kingdom.1252
## [4] LC_NUMERIC=C                           
## [5] LC_TIME=English_United Kingdom.1252    
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
## [1] knitr_1.25
## 
## loaded via a namespace (and not attached):
## [1] compiler_3.5.2  magrittr_1.5    tools_3.5.2     stringi_1.1.7  
## [5] stringr_1.4.0   xfun_0.10       packrat_0.4.9-3 evaluate_0.14
{% endhighlight %}

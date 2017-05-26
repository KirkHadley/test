#### HMS and Improved Claims Selection: Moving Towards Deep Learning

* Current Claims Selection processes, in both complex and data mining products are developed in an ad hoc process that ultimately results in poorer results
* Can this be improved, and if so, how and to what degree?

+++

#### Machine Learning

* Learning subtle relationships
* More data, better model
* Better features (input), better model
* Bias-Variance


+++


#### But first some housekeeping
* Data wrangling on average 40-60% of ML projects
* Want pipelines, not steps
* Ongoing proces; generally with diminishing marginal returns
* Current painpoints: lack of hadoop-mysql direct interaction; future of hadoop for employment


+++


#### Baseline Results
* Why are we still calling these baseline results?
* Stats:
  * Finding Rate: 48%
  * "New Stuff" Increase: 16%
  * False Positive Reduction: 30%
* More helpful considered in context


+++


#### Tale of 100 Complex Claims
* SAS *selects* 100 claims
* SAS **finds** 16 positive claims
* Comparatively, current baseline would *select* 70 claims
  * 55 exact same as SAS would've selected
* 15 new claims
  * Model designed to pick new claims only if quite confident
  * Conservative discount:   
* Initial testing shows that traditional machine learning models are a welcome improvement over SAS
  * 20% cost savings, 15% new claims
* Is this good enough?
  * It sounds like it should be, but there's hidden costs here.
  * Primarily:
    * Maintenance- having to regularly retrain after deployment
    * Silent failures
* Where to next?


+++

## Enter Deep Learning

* What's deep learning offer that we don't get out of the traditional approaches?
* Robustness
* Online training
* Leveraging unique structure of our domain  
* Graph Theory and Clustering

+++

### Demos to come! 




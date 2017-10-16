# Weekly Update

* [6th October 2017](#date-6th-october-2017)

### Date: 6th October 2017

#### Who did I help this week?

* I helped Andrea set up project email
* I helped Anila review the L1 script and compared the results with SPM

#### Who helped me this week?

* Satra reviewed one of my PRs
* Yoel with some stats questions

#### What did I achieve?

* Level one + group analysis for banda project
* Paperwork for MTBI texas and NDAR renewal
* Scheduled more controls for voice
* Sorted fmriprep problem on /om (singularity + space issue, solved with changing the CACHEDIR)
* Wrapping up some PRs for nipype

#### What did I struggle with?

* Heudiconv packaging had to take a backseat this week

#### What would I like to work on next week?

* Heudiconv RF
* Brain Plotting enhancements
* Voice consents/scans
* Cerebellar + subcortical analysis
* convert MTBI-Texas to BIDS(again) and validate

#### Where do I need help?

* Support on nipype, lab questions

#### Any other topics

* Machine learning with lab QC data - can we make a DNN to pass/fail our data?? How can we establish a ground truth?
* After RF heudiconv - run a labwide conversion seminar to get other data in BIDS

-----

* [29th September 2017](#date-29th-september-2017)

### Date: 29th September 2017

#### Who did I help this week?

* Jakub and I helped Nick with some simulations that randomize voxels across time but keep its position within the image

#### Who helped me this week?

* Satra met with me and we went over a few things
* Andrea will help with the voice recruiting

#### What did I achieve?

* more refactoring - very close to finishing the heudiconv upgrade
* ran all ~650 camcan subjects through mindboggle + partly through fmriprep
* mindboggled voice

#### What did I struggle with?

* encountered a problem with voice in fmriprep - need to investigate more
* some IRB paperwork for texas/autoxy (need to meet with satra)

#### What would I like to work on next week?

* Packaging heudiconv
* convert MTBI-Texas to BIDS(again) and validate - didn't get to it last week
* Banda l1 processing
* cerebellar analysis for montreal

#### Where do I need help?

* IRB updates

#### Any other topics

still interested in:
* Machine learning with lab QC data - can we make a DNN to pass/fail our data??
* After RF heudiconv - run a labwide conversion seminar to get other data in BIDS

-----

* [22nd September 2017](#date-22nd-september-2017)

### Date: 22nd September 2017

#### Who did I help this week?

* I helped Xavier run a matlab script within a python workflow.
* I helped Todd with some heudiconv debugging
* I helped a nipype contributor with their PR.

#### Who helped me this week?

* Isabelle helped by curating the BANDA NIH toolbox metadata

#### What did I achieve?

* I answered questions on neurostars, and reviewed a nipype PR.
* I finished running BANDA fully through the HCP BIDS-App
* I continued refactoring heudiconv into a package
* I created some figures to show at the data blitz

#### What did I struggle with?

* adding brainmask to the mindboggle123 pipeline

#### What would I like to work on next week?

* Finish Packaging heudiconv
* Complete preprocessing for voice (mindboggle + fmriprep)
* Finally convert MTBI-Texas to BIDS(again) and validate

#### Where do I need help?

* Mindboggle with lesions (Satra)
* Finding more controls for voice

#### Any other topics

* Machine learning with lab QC data - can we make a DNN to pass/fail our data??
* After RF heudiconv - run a labwide conversion seminar to get other data in BIDS

-----

* [15th September 2017](#date-15th-september-2017)

### Date: 15th September 2017

#### Who did I help this week?

* I met with Maiya and ran the Mindboggle pipeline on her montreal project. Afterwards, we visualized the results.
* I helped Julia with HTML/CSS as she set up her website.

#### Who helped me this week?

* Jakub and Xavier helped me scan by yellowing badging.
* Satra helped me understand how to properly specify fieldmaps.

#### What did I achieve?

* I consented and scanned 2 participants for voice.
* I answered a few questions on neurostars.
* I ran some of BANDA **completely** through the BIDS-App HCP_Pipeline.
* I started to work on breaking up and debugging the newly changed heudiconv.

#### What did I struggle with?

* Making dcmstack python 3 compatible

#### What would I like to work on next week?

* Add brainmask to Mindboggle to allow better segmentation of lesions (is this possible without creating a new template?).
* Packaging heudiconv
* Prepare some slides for Datablitz
* Continue processing other BIDS projects with BIDS-Apps (Automate this process as best as I can)

#### Where do I need help?

* Mindboggle with lesions (Satra)
* Finding more controls for voice

#### Any other topics

Spending some time on ML this week - possibly DL

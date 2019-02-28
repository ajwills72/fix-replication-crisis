# fix-replication-crisis

Slides for a talk I gave at the Plymouth University School of Psychology Resarch Seminar Series, on 13 Feb 2019. It's an opinionated survey of seven causes of the replication crisis in psychology, and a practical how-to guide for avoiding these causes in your own reserch. It's aimed at a broad audience of psychology professionals, starting around final-year psychology undergraduate student and going through to mid-career academic.

View the slides:[PDF](fix-replication-crisis.pdf)

Listen to the talk: [video](https://youtu.be/_OqiTVq12Pk)

Print the t-shirt: [jpg](t-shirt/revolution.jpg)

You can use this [file](t-shirt/revolution.jpg) at a service such as [Abracadabra Clothing](https://www.abracadabraclothing.com/) to print yourself a t-shirt in either black or white, in a range of sizes.

## Summary

I gave an opinionated survey of seven causes of the replication crisis in psychology, and seven actions we could all take today to avoid it in future. In brief:

1. Publication bias

Publication bias comes in part from null results being meaningless with traditional statistics. Use Bayes Factors instead, they can provide evidence for the null, and are easy to do in R.

2. Small sample size

Most of us do not collect enough data in our experiments. Use a power calculation to work out an appropriate sample size. This is easy to do in R.

3. Misunderstanding statistics

No-one in psychology really understands p values. Also, a p value between .04 and .05 is strangely common in psychology, yet p-values in this range provide only very weak evidence. Use Bayes Factors instead.

4. Low reproducibility

If you run a different experiment to me, and do different analysis, is it that surprising you get a different answer? Ensure your work is reproducible by publishing your raw data, analysis scripts, stimuli, and experiment code.

5. 'p' hacking

Common practices in flexible analysis, like testing for significance after every 10 participants, and stopping when it's significant, can lead to false positive rates of about 60%. Pre-register your next big study, so you don't fool yourself.

6. Poor project management

Most psychologists do not have adequate private archiving and recording within their own labs. Use a version control system (e.g. github) to improve project management in your lab.

7. Publication norms

Pressure to publish lots of papers leads to lots of poor outputs, rather than a few good ones. Publish fewer, better papers. If you are a manager, focus hiring, promotion, and appraisal less on volume and more on quality.


## Source code

These slides were produced using the `rmarkdown` pacakge of `R`. If you use _RStudio_, start a new Version Control project, and use the _git_ option to download the files. Then open the `.Rmd` file, and click _knit_.  

If you use R outside of RStudio (e.g. you use Emacs), the file `render.R` contains the commands you need to knit the file. 

## Contributors

_Talk and slides_: Andy Wills

_Talk host_:  Alastair Smith

_T-shirt design_: Helen 'Ellie' Lloyd 

_Tech support_: Chris Longmore      


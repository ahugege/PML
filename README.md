# PML
Repository for Practical Machine Learning.

Hello everyone, I'm going to write my process and thoughts down here before I got myself clear on how to compose in Rmd file and html format. Sorry ahead for my new-birdness and awkward, while meantime, "exotic" English.

registerDoMC(cores= 4)
model <-randomForest(training[-ncol(training)], training$classe, ntree=200)

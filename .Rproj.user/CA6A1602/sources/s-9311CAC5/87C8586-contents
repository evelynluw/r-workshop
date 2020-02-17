# Open table
load(file = "babies.Rda")

# EDA: Check basic info of table
View(babies)
head(babies)
summary(babies)
mean(babies$age)
mean(babies$age, na.rm=TRUE)
max(babies$age)
min(babies$ht)
class(babies)
class(babies$age)
dim(babies)
nrow(babies)
ncol(babies)

# Data cleaning
babies = na.omit(babies)  # drop rows with NA
rownames(babies) <- NULL  # reset the index / rownames of each row
mean(babies$age)
mean(babies$ht)

# Indexing 
babies$date
babies[[4]]
babies[1, ]
babies[1,4]
babies[1:5, ]
babies[:2, ] # doesn't work
babies[1:2, ]
babies[1:2, 1:5]
babies[1:2, -(1:5)]

# Subsetting
subset(babies, age == 27)
subset(babies, ed == "College")
subset(babies, age == 27 & ed == "College")
subset(babies, age == 27 | ed == "College")



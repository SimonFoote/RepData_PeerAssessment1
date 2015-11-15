# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

* Load the data

```r
activity=read.csv("activity.csv")
```
* Process/transform the data (if necessary) into a format suitable for your analysis

```r
totalSteps<-aggregate(steps~date,data=activity,sum,na.rm=TRUE)
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?

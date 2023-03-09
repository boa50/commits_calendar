# Commits callendar

R package used to plot a commits calendar somehow like GitHub's

### How to install
Using the devtools package, you could run
```R
devtools::install_github('https://github.com/boa50/commits_calendar/commits_calendar')
```

### How to use
First you need to load the package `library(commits.calendar)`.

After that you could using the function `plot_calendar` passing a dataframe with a `commit_date` column.

It would plot something like this

![Commits Calendar](https://github.com/boa50/commits_calendar/img/calendar.png "Commits Calendar")

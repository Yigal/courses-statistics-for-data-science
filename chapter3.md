---
title: 'Single Variable Statistics '
description: 'Central tendency and dispersion'
---

## Insert exercise title here

```yaml
type: NormalExercise
key: 80969112c3
xp: 100
```

<!-- Guidelines for contexts: https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->

`@instructions`
You are given a table of historical characters and the type of each field. For each field, write Python code to produce the central tendency and variability.

The table and key are both in a variable called `dataTable`.

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@pre_exercise_code`
```{python}
dataTable = {
  "key": {
    "Name": {
      "Type": "Nominal"
    },
    "Position": {
      "Type": "Ordinal",
      "Order": ["Monarch", "Prime Minister", "Minister of Defence"]
    },
    "Country": {
      "Type": "Nominal"
    },    
    "From": {
      "Type": "Date",
      "Format": "YYYY-MM-DD"
    },
    "DaysInOffice": {
      "Type": "Ratio",
      "Unit": "Days"
    }
  },
  "data": [
    {
      "Name": "George VI",
      "Position": "Monarch",
      "Country": "UK",
      "From": "1936-12-11",
      "DaysInOffice": 5535
    },
    {
      "Name": "Edward VII",
      "Position": "Monarch",
      "Country": "UK",
      "From": "1936-01-20",
      "DaysInOffice": 326
    },
    {
      "Name": "George V",
      "Position": "Monarch",
      "Country": "UK",
      "From": "1910-05-06",
      "DaysInOffice": 9390
    },
    {
      "Name": "Winston Churchill",
      "Position": "Prime Minister",
      "Country": "UK",
      "From": "1940-05-10",
      "DaysInOffice": 1903
    },
    {
      "Name": "Winston Churchill",
      "Position": "Prime Minister",
      "Country": "UK",
      "From": "1951-10-26",
      "DaysInOffice": 1257
    },
    {
      "Name": "Neville Chamberlain",
      "Position": "Prime Minister",
      "Country": "UK",
      "From": "1937-05-28",
      "DaysInOffice": 1078
    },
    {
      "Name": "Clement Attlee",
      "Position": "Prime Minister",
      "Country": "UK",
      "From": "1945-07-26",
      "DaysInOffice": 2283
    },
    {
      "Name": "Winston Churchill",
      "Position": "Minister of Defence",
      "Country": "UK",
      "From": "1940-05-10",
      "DaysInOffice": 1903
    },
    {
      "Name": "Winston Churchill",
      "Position": "Minister of Defence",
      "Country": "UK",
      "From": "1951-10-26",
      "DaysInOffice": 127
    },
    {
      "Name": "Manny Shinwell",
      "Position": "Minister of Defence",
      "Country": "UK",
      "From": "1950-02-28",
      "DaysInOffice": 605
    },
    {
      "Name": "Albert Victor Alexander",
      "Position": "Minister of Defence",
      "Country": "UK",
      "From": "1946-12-20",
      "DaysInOffice": 1166
    },
    {
      "Name": "Clement Attlee",
      "Position": "Minister of Defence",
      "Country": "UK",
      "From": "1945-07-26",
      "DaysInOffice": 512
    },
    {
      "Name": "David Ben-Gurion",
      "Position": "Prime Minister",
      "Country": "Israel",
      "From": "1948-05-17",
      "DaysInOffice": 2080 
    },
    {
      "Name": "David Ben-Gurion",
      "Position": "Prime Minister",
      "Country": "Israel",
      "From": "1955-11-03",
      "DaysInOffice": 2792
    },
    {
      "Name": "Moshe Sharet",
      "Position": "Prime Minister",
      "Country": "Israel",
      "From": "1954-01-26",
      "DaysInOffice": 646
    }    
  ]
}
```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
```

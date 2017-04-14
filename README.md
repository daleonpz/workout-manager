# Workout-manager
Manage my workout

## How to run:
./wointerface -r "pathToFile"

![Screenshot](https://github.com/daleonpz/dnl_tools/blob/master/_extraImages/wointerface_001.png)

## Features:
### Add workouts files
You must create your workout file. The format is as follows:

```
** Superset 1
** Break: time
* excercise 1
reps
* excercise 2
reps

** Superset 2
** Break: time
* excercise 1
reps
* excercise 2
reps
```

After each super set there must be an `\n`

### Record your sessions
Creates a log file with the day and hour, routine name, and duration

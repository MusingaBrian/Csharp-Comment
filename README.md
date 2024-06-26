# C# Control Structures

## A Students Grading Console App.

### If, IfElse, ForEach

##Sample Code

#### initialize variables - graded assignments

```
int examAssignments = 5;

int[] sophiaScores = new int[] { 90, 86, 87, 98, 100, 94, 90 };
int[] andrewScores = new int[] { 92, 89, 81, 96, 90, 89 };
int[] emmaScores = new int[] { 90, 85, 87, 98, 68, 89, 89, 89 };
int[] loganScores = new int[] { 90, 95, 87, 88, 96, 96 };
int[] beckyScores = new int[] { 92, 91, 90, 91, 92, 92, 92 };
int[] chrisScores = new int[] { 84, 86, 88, 90, 92, 94, 96, 98 };
int[] ericScores = new int[] { 80, 90, 100, 80, 90, 100, 80, 90 };
int[] gregorScores = new int[] { 91, 91, 91, 91, 91, 91, 91 };

```

#### Checking For Student from the arrays

```

if (currentStudent == "Sophia")
        // assign Sophia's scores to the studentScores array
        studentScores = sophiaScores;

    else if (currentStudent == "Andrew")
        // assign Andrew's scores to the studentScores array
        studentScores = andrewScores;

    else if (currentStudent == "Emma")
        // assign Emma's scores to the studentScores array
        studentScores = emmaScores;

    else if (currentStudent == "Logan")
        // assign Logan's scores to the studentScores array
        studentScores = loganScores;

    else if (currentStudent == "Becky")
        // assign Becky's scores to the studentScores array
        studentScores = loganScores;

    else if (currentStudent == "Chris")
        // assign Chris's scores to the studentScores array
        studentScores = loganScores;

    else if (currentStudent == "Eric")
        // assign Eric's scores to the studentScores array
        studentScores = loganScores;

    else if (currentStudent == "Gregor")
        // assign Gregor's scores to the studentScores array
        studentScores = loganScores;

    else
        continue;

```

# water
This code was used to try and figure out why executing
./gradlew -q afterEvaluate --stacktrace causes and error
"Could not compile build file 'C:\Users\Tom\AndroidStudioProjects\water\build.gradle'."
And yet ./gradlew -q hello --stacktrace  works fine. Both use the afterEvaluate maven function.
https://docs.gradle.org/current/userguide/multi_project_builds.html#sec:defining_common_behavior

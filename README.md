# FocusFlow

FocusFlow is a simple focus-session planner for students who feel overwhelmed by large assignments. It turns a task into a short, achievable focus session and keeps a local history so users can see their progress.

## Core functionality

- User can create a focus task with a title and planned duration.
- User can edit or delete an unfinished focus task.
- User can view a list of current and completed focus tasks.
- User can start a countdown focus session for a selected task.
- User can pause, resume, or finish an active session.
- User can mark a task complete when the session ends.
- App shows an empty state when no tasks have been created.
- App stores tasks and session history locally on the device.
- User can view basic completion statistics, including completed sessions and total focus minutes.

## Current folder structure

```text
FocusFlow/
|- app/
|  |- src/main/
|  |  |- java/com/example/focusflow/MainActivity.kt
|  |  |- res/values/strings.xml
|  |  |- res/values/themes.xml
|  |  `- AndroidManifest.xml
|  `- build.gradle.kts
|- gradle/libs.versions.toml
|- .gitignore
|- build.gradle.kts
|- settings.gradle.kts
`- README.md
```
## How to download and run the project

1. Open the repository on GitHub.
2. Click the green **Code** button and choose **Download ZIP**, or clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/FocusFlow.git

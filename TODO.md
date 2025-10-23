# TODO List for UI Flow Implementation

## Completed Tasks
- [x] Created StorySelectionScreen with two story options
- [x] Modified HomeScreen to show single "Start" button
- [x] Updated navigation to go from Home -> StorySelection -> GameScreen

## Pending Tasks
- [x] Test the app to ensure the flow works correctly
- [x] Verify that both stories load properly from the selection screen

## Testing Results
- [x] App launched successfully on Windows
- [x] UI flow implemented: Home → Start → Story Selection → Game Screen
- [x] Both story files (story.json, desert_story.json) are available in assets

## Pending Tasks for Chapter 2 End Screen
- [x] Update Player model to include choicesMade and secretsFound counters
- [x] Modify ChoiceHandler to increment choicesMade and detect secrets
- [x] Create EndScreen widget in lib/widgets/end_screen.dart
- [x] Update GameScreen to display EndScreen for Chapter 2 completion
- [x] Add story-specific ending line in the top area of EndScreen
- [x] Test the end screen layout and stats display

## Notes
- HomeScreen now shows "Start" button that navigates to StorySelectionScreen
- StorySelectionScreen has "Chapter 1" (story.json) and "Chapter 2" (desert_story.json)
- Chapter 1 description: "Start your mystical journey through The Forgotten Quest"
- Chapter 2 description: "Venture deeper into the desert lands"
- Each story button navigates to GameScreen with the appropriate storyFile
- End-of-story buttons: 3 buttons for Chapter 1, 1 button for Chapter 2
- New end screen for Chapter 2 will show: Choices made, Secrets found, Final Score based on reputation and health

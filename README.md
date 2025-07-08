# window-placement-switcher
Window Placement Switcher is a convenience plugin for the Godot Engine editor.
It adds a dropdown button to the toolbar that lets you switch directly between screens/monitors to run your project on.

## How does it work?
It reads & sets the editor setting `run/window_placement/screen` and generates its options directly from the corresponding `hint_string`, attempting to stay up-to-date with possible future changes.

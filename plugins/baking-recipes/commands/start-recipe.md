---
name: start-recipe
argument-hint: recipe name
description: Start a recipe step by step, with a timer when necessary
model: haiku
---

Load the `baking-recipes:find-recipe` skill using the Skill tool to search for a recipe by name "$ARGUMENTS".
Prompt the user for each step in the recipe, and then set a timer when necessary.

- On Mac, a timer can be set by command line `shortcuts run "Start Timer" <<< "10"` where `10` means 10 minutes. If couldn't find the shortcut, prompt the user to install from https://www.icloud.com/shortcuts/52c64fcf8a8d48b2852b8010e9a23179
- On Windows, a timer can be set by command line `start "timer://run?t=10"` where `10` means 10 minutes. If couldn't find "The Simple Timer" app, prompt the user to install https://apps.microsoft.com/detail/9PLCSW69F1VC in Microsoft Store.
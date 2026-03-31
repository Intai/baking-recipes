---
name: start-recipe
argument-hint: recipe name
description: Start a recipe step by step, with a timer when necessary
---

Load the `find-recipe` skill using the Skill tool to search for a recipe by name "$1".
Prompt the user for each step in the recipe with a "Continue" button, use `create_schedule` to set a timer when necessary.

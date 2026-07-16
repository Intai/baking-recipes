---
name: find-recipe
argument-hint: recipe name
description: Find a baking recipe by name
model: haiku
---

Find a recipe "$ARGUMENTS" in @plugins/baking-recipes/skills/find-recipe/recipes.

The recipes are an Open Knowledge Format bundle. Start from `index.md`, which lists every recipe with
its description. `index.md` and `log.md` are reserved filenames and are never recipes themselves —
every other markdown file is one recipe.

Match "$ARGUMENTS" against each recipe's `title`, `description` and `tags` frontmatter as well as its
filename, so a search for an ingredient, a method or a meal ("yeast", "savoury", "overnight") finds
the recipe even when the filename does not contain the word.

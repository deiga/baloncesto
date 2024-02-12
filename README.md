# Baloncesto

This is a personal project for suggesting what to cook in the next week for my family.

## Tech

I'm writing this project in Rust to familiarise myself with the language.

## MVP

Build a CLI that takes 7 or 14 days as input and suggests a menu for the chose time-frame. It should store when a food was last suggested and how many times a food was suggested so that it can pick with a weighted random algorithm from the least frecent foods.

### Nice to Have

- Each food should have some keywords or tags so that the algorithm doesn't pick the same type
- Some foods are pairings of `Topping` and `Base` and the program should be able to mix and match these pairings

### Extra Nice

- Tags/Keywords should have some weighting system so that some tags tolerate being picked multiple times in the given timespan
- Input ingredients found at home and suggest existing food recipes based on them (Possibly use a LLM here to get an updated recipe)
  
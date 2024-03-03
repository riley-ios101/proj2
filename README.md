# Project 2 - Wordle Again

Submitted by: Riley Dou

Wordle Again is an app that replicates the popular game Wordle. You guess the word, and the color codes of each letter cell tells you if you're close or not! You can play in different themes, have more guesses, and guess words of various letters. You can also have the goal word change every time you guess wrong (if you want to torture yourself that way)!

Time spent: 2 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] User can change the number of letters per row (the length of the goal word)
- [x] User can change the numbers of rows on the board (how many guesses allowed)
- [x] User can select a new themed set to pull the goal word from
- [x] User can select "alien wordle", causing the goal word to change after each guess


The following **optional** features are implemented:

- [x] App displays a reset button on the top left to reset the game (but make no changes to the settings)

The following **additional** features are implemented:

- [ ] App displays an endgame UI message that indicates if you won or not.

## Video Walkthrough

[Demo](https://imgur.com/a/KXb8mp0)


## Notes

A challenge was implementing the reset functionality. I looked at the didTapSettings() function and was confused on what the perform function did (because I thought I was supposed to use that). But after finding out what the purpose of the function was (to bring up a view which was not supposed to happen) and looking at the hints, I was able to figure it out.

## License

    Copyright [2024] [Riley Dou]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

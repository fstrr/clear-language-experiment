# xkcd-simplewriter

A desktop app version of the [xkcd Simple Writer](http://xkcd.com/simplewriter/)

## Updates to the app since the November 2020 fork of the original app

1. The Ace editor no longer has a keyboard trap: press the <kbd>Escape</kbd> key to exit the editor after entering some words.
2. Duplicate words are removed from the less-than-simple results. This has resulted in a side effect of having the results presented in lowercase rather than as entered.
3. Added `<main>` and `<section>` elements to the app to replace `<div>`s.

### Word lists
There are now three word lists:

1. the original XKCD list;
2. the top 3,000 of Google's 10,000 most common English words;
3. the top 5,000 of Google's 10,000 most common English words.

#### Word list notes:

1. The word Google word lists come from the [Google 10000 English repo](https://github.com/first20hours/google-10000-english).
2. The word list used is [Google 10000 English](https://github.com/first20hours/google-10000-english/blob/master/google-10000-english.txt), which isn't constrained to "American English" and does contain profanities.
3. You can change which word list is used by commenting and un-commenting the `<script>` tags in the `index.html` file.

## To do

1. Add stemming to remove common suffixes.
# fantastyprosdraft
Fantasy Football Drafting Software Fantasy Pros Edition

## What it does
This is my first attempt at a fantasy football drafting application to help someone with their draft. The goal was to simplify your draft day preparations specifically if you draft in person and not online eliminating the need to carry a bunch of papers or navigate a multi tabbed spreadsheet.  You create a draft kit based on your league settings and upload tier csv files from the website fantasy pros.There is some weighing going on but it's minor based mostly on positions you need and comments you leave such as if a player is predicted to be a bust or sleeper. 

## How it works
First you enter in all of your league and draft information. Multiple drafts can be created for multiple leagues that have different setups and you can toggle between them all. Once your league draft information is entered, download all the positional tier lists you need over at https://www.fantasypros.com/nfl/rankings/consensus-cheatsheets.php
Make sure to pick the right one based on your league scoring (standard, half ppr and ppr) and make sure you keep updating those csv files up to draft day.
This can run as is but I created it using Claude so if you don't run it in Claude you won't be able to  auto save your draft or access the button that gives you real time player updates however I included an export to JSON  button that at least lets you save your settings and draft progress locally but you have to remember to manually press it. This is a notes button where you can add notes for specific players before your draft. This could be positive, negative or neutral notes. Positive and negative (sleeper and bust) will slightly impact their place on the list but it's really minor and there is a neutral option that doesn't impact anything. As I said before there is a button  that can fetch the latest information about a player but that goes through the Claude AI and requires and account and use  tokens so be aware of that. If you are not running it in Claude it simply won't work. You can draft players, mark them as drafted by someone else and they will vanish from the list but if you toggle on "show undrafted" you can still see them. All these actions can also be undone and they can be returned to the drafting pool if you misclick. You can also filter for each player by name and toggle between lists of specific positions. 

## The Future
I am currently building an alternative version of this that has its own points computation engine powered by seasonal projections for all players but this is good if you just want to eliminate paperwork on draft day.

Built with the assistance of Claude (Anthropic), including iterative debugging based on real-world testing

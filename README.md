# Advance_WebApps_Masters
My Masters Degree Course Work (Advance Web Applications and Services)

Poker Game:

Description: In this assignment, I'm going to develop a poker game using JavaScript and
jQuery animation. One of the key elements of using jQuery is to learn how to use the library.
As for the game, user will place a bet on every hand. First, two cards will be shown to the user,
user can raise the bet (the bet must be between 1 and 10); after user place the bet, the
remaining three cards will be shown to the user and the score will be updated.
I implemented logic for various hands including royal flush, four
of a kind, full house, straight, flush, three of a kind, two pairs, one pair and nothing. There is a
reset button to reset the score back to 100.

The easiest way to start a new hand is to reload the page, the only thing needs to keep track of
is the score which can be stored using localStorage.
// reload the page
location.reload();
// get score
var score = localStorage.getItem("score");
// reset score
localStorage.setItem("score", 100);

The webpage “https://api.jquery.com/animate/” is a great resource for the animation

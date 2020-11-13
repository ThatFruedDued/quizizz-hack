# Quizizz Hack
## !IMPORTANT!

This script currently **does not** work. In addition, this **will not** be able to function in the future with the way Quizizz functions right now. I understand that this is disappointing, but there is not much I can do right now to fix this.

### Why won't it work?

Quizizz has updated their application so that answers are submitted to and checked **server side**, meaning there is no way to automatically fetch the answers and use them to submit the question automatically.

### How can we fix it?

I am currently working on a solution that involves searching for the set using the Quizizz search API. The only caveat to this approach would be if the Quizizz was private or it was not popular enough to appear in search results.

Another solution for this issue would be to require finding the Quizizz on the quiz browser. This would allow us to get the real quizID (which is what we need), then use that to fetch the answers in a Quizizz game. This would allow the script to continue working (although it would be a downgrade from what we had before).

## Bookmarklet

`javascript:fetch('https://thatfrueddued.github.io/quizizz-hack/Quizizz.js').then(function(response){response.text().then(function(text){eval(text);});});`  

Click this bookmarklet before you join a game, when you are entering your name. Then, press the w key to automatically answer. This does not currently work on mobile, but support is coming soon. Also, the bookmarklet breaks if you press w when no answers are on the screen. This will also be fixed in an upcoming update.

## Reactivating Bookmarklet

If the bookmarklet breaks in the middle of a game, reload the page. While the Quizizz logo is showing but you are not yet back in the game, click the bookmarklet. This should reactivate it if anything breaks.

## Upcoming Features

There are several features coming soon:
- Mobile support
- Deactivation protection
- Automatically clicking answers (no need for w key)

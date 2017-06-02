# Bitmaker Mystery
In today's assignment, we're going to take a step away from code for a bit, and instead do a Choose Your Own Adventure. In case you've never had the pleasure of reading a Choose Your Own Adventure story, the idea is pretty simple. At key points within the story, you'll be presented with a choice, and your choices will effect the outcome of the story.

There's a twist to the usual formula though. Rather than simply making our choices and living with the outcome, we're going to cheat a little. Sometimes in a Choose Your Own Adventure story, one of your choices will lead you to an undesirable result. So instead of accepting whatever outcome we arrive at, we'll use the power of git branches and merges to jump between all the possible choices we could make, see where they lead, and make a final choice once we're satisfied with the outcome.

You're free to work on this on your own, but you might find it beneficial to work in small teams. That way, you can explore several choices at the same time.

## Key Concepts
To succeed in this assignment, you'll need to understand what a **git branch** and a **git merge** are.

Branches allow us to break off from our *master* branch, where all our final decisions will be recorded. This way we can experiment without committing to some final result.

Once we're happy with the state of our branch, and we feel like its safe to make our decisions final, we'll merge the branch back into *master*. The *master* branch should be considered our final source of truth, so we should try to make sure that we're happy with our decisions before we merge into it.

## Making Choices
The story will be presented as a few paragraphs of text, followed by a multiple choice. Each choice will lead you to the next part of the story, which will either present you with another choice, or an ending. We'll record all of our choices in a file as we go, `CHOICES.txt`. The trick is that **we won't ever delete anything from this file** if we don't like a choice we've made, instead we'll use the power of branches to rewind time.

Progressing through the story and making choices will look something like this:
1. First, make a **branch** in git. This way if you end up not liking the choice you made, you can simply switch back to *master*.
1. Next, read through the story up to that point, and decide what choice you want to make.
1. Record your choice in the `CHOICES.txt` file. Simply record the option you chose at whatever part of the story you're at. Make a **git commit** representing the choice.
1. The choice you chose will have a link. Click on it, and read the next part of the story.
1. Once you're satisfied with the choice or choices you've made, merge your branch back into *master*. You may choose to do this after one choice, or after several. This is for you to decide, but remember, you're **not allowed to simply delete choices from `CHOICES.txt`**. So if you go several choices in, and then decide you want to go back, you'll have to go back to where you branched off of, so merging frequently is probably not a bad idea.
1. Make a new branch, and go back to **Step 2** until you reach an ending you like.

One more thing. If at any point, you feel like you explored all the choices you could, and its impossible to proceed, click on [this link](story/6a.md) to get a hint. Try to hold off for as long as possible, or you'll spoil the story!

Alright, [let's jump into the story!](story/intro.md)

# Git Force Pull
A handy script to force pull from origin repository.

## Rationale

I'm often not so tidy, forgetting to add variable local files to `.gitignore` and things like that. Pulling from origin can be too much needless work (and if you're not a **Git Ninja**, like I'm not, you mess stuff up).

## What it does

It deletes all your local files that correspond to the ones in the origin so that there are no conflicts, checks out locally modified files, and finally pulls the origin. TL;DR it overwrites your local working directory with contents of the origin and syncs you to the final commit in the origin.   
  
It's a quick and dirty hack, mostly useful in scenarios like using git to deploy on web servers etc.

## Credit

I'm not the author. I found this handy script on [StackOverflow](http://stackoverflow.com/a/13242127/743765) and all props should go to [Strahinja Kustudić](http://stackoverflow.com/users/1343616/strahinja-kustudic) obviuosly. Given it was shared freely on a public domain site I suppose it's ok for me to fork it here. Keeping it here for safekeep knowing how weird mods are at SO nothing is safe there.
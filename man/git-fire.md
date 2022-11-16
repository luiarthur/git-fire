% GIT-FIRE(1) | Git Plugin Manual

NAME
====
**git-fire** - Type this command in case of fire.

SYNOPSIS
========
| **git-fire** [optional-branch-name]

DESCRIPTION
===========
Unsaved changes will be saved and pushed to a new branch named:
  `$USER/fire/some-long-hash`

EXAMPLE
=======
A fire just started, and you need to leave. But you have just enough for one last commit.

```
git fire
```

Options
=======
Optionally supply a shorter identifier for your branch. I.e., 

```
git fire some-short-name
```

The changes will be pushed to a new branch named:
  `$USER/fire/some-short-name`

AUTHOR
======
Arthur Lui

SEE ALSO
========
**git-commit(1)** **git-push(1)**

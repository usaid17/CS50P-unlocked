___

Some people have a habit of lecturing speaking rather quickly, and it’d be nice to slow them down, a la YouTube’s 0.75 playback speed, or even by having them pause between words.

In a file called `playback.py`, implement a program in Python that prompts the user for input and then outputs that same input, replacing each space with `...` (i.e., three periods).

Hints

- Recall that `input` returns a `str`, per [docs.python.org/3/library/functions.html#input](https://docs.python.org/3/library/functions.html#input).
- Recall that a `str` comes with quite a few methods, per [docs.python.org/3/library/stdtypes.html#string-methods](https://docs.python.org/3/library/stdtypes.html#string-methods).

## [Demo](https://cs50.harvard.edu/python/2022/psets/0/playback/#demo)

## [Before You Begin](https://cs50.harvard.edu/python/2022/psets/0/playback/#before-you-begin)

You should find that your terminal window’s prompt resembles the below:

```
$
```

Next execute

```
mkdir playback
```

to make a folder called `playback` in your codespace.

Then execute

```
cd playback
```

to change directories into that folder. You should now see your terminal prompt as `playback/ $`. You can now execute

```
code playback.py
```

to make a file called `playback.py` where you’ll write your program.
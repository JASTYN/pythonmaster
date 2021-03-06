# House

Write a program that outputs the nursery rhyme 'This is the House that Jack Built'.

> [The] process of placing a phrase of clause within another phrase of
> clause is called embedding. It is through the processes of recursion
> and embedding that we are able to take a finite number of forms (words
> and phrases) and construct an infinite number of expressions.
> Furthermore, embedding also allows us to construct an infinitely long
> structure, in theory anyway.

- [papyr.com](http://papyr.com/hypertextbooks/grammar/ph_noun.htm)

Rhyme found in http://www.pitt.edu/~dash/type2035.html

The nursery rhyme reads as follows:

```plain
This is the house that Jack built.

This is the malt
that lay in the house that Jack built.

This is the rat
that ate the malt
that lay in the house that Jack built.

This is the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the rooster that crowed in the morn
that woke the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the farmer sowing his corn
that kept the rooster that crowed in the morn
that woke the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.

This is the horse and the hound and the horn
that belonged to the farmer sowing his corn
that kept the rooster that crowed in the morn
that woke the priest all shaven and shorn
that married the man all tattered and torn
that kissed the maiden all forlorn
that milked the cow with the crumpled horn
that tossed the dog
that worried the cat
that killed the rat
that ate the malt
that lay in the house that Jack built.
```

You are expected to create 2 functions `rhyme` and `verse`.

`rhyme` will return the whole song as above, while `verse` will return a particular verse of the song.
`verse` will take a verse_no as the parameter

An example:

``` python
>>> verse(3)
'This is the cat\n'\
'that killed the rat\n'\
'that ate the malt\n'\
'that lay in the house that Jack built.'
```

``` python
>>> verse(2)
'This is the rat\n'\
'that ate the malt\n'\
'that lay in the house that Jack built.'
```

## Source

British nursery
rhyme [http://en.wikipedia.org/wiki/This_Is_The_House_That_Jack_Built](http://en.wikipedia.org/wiki/This_Is_The_House_That_Jack_Built)



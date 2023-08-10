_General disclaimer:_ this is not necessarily the final notation we are going to use for formally  documenting the LaTeX namespace, but it is reasonably simple, and -- I hope -- easy enough to understand and follow, and most importantly easy to use within markdown.

#### Notation (BNF like with different symbols) :

 - `<foo>`  means the tag "foo" in the LaTeX name space
 - `</foo>` means the end tag "foo" in the LaTeX name space
 - `{bar}`  means that further details are hidden and explained separately (what angle brackets are in BNF)
 - `[...]`  grouping "..."  and the group is optional --- 0 or 1 time
 - `(...)`  grouping "..."  --- for use with modifiers
 - `*`      the previous group can be repeated multiple times (including 0)
 - `+`      the previous group can be repeated multiple times but at least once
 - `|`      means exclusive "or" (its scope is limited by grouping)

##### Notes

 - I've gone for this notation in order to immediately see the terminals from the LaTeX name space (in angle brackets).

 - I only use a few meta symbols because that is all I need right now and they are easy to remember because they are used with the same meaning elsewhere often too.

 - As I write these by hand for now, more "formal" structure would overflow my brain :-) so while a different or better formal notation may have to be discussed, I would suggest for now to take it as is and not have this discussion until after there is a suitable amount of material using it.

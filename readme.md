# Markdown Comments

## Introduce

This file is targeting to check different comments of markdown. Can you see the following lines?

test1 begin

[]: # (This is a comment)

test1 done

test2 begin

[]: # "And this is a comment"

test2 done

test3 begin

[]: # 'Also this is a comment'

test3 done

test4 begin

[//]: # (Yet another comment)

test4 done

test5 begin

[comment]: # (Still another comment)

test5 done

Each of these lines works the same way:

[...]: identifies a reference link (that won't be used in the article)
# defines the destination, in this case # is the shortest valid value for a URL
(...), "...", and '...'define the reference title, which we repurpose to make a comment
While this is the best approach that I'm aware of, it doesn't allow multi-line comments and each comment must appear on it's own line.

I personally prefer to use [//]: # since, as a software developer, I tend to associate // with comment syntax.

## This head title having comment at tail <!-- this is comment -->

You cannot see this comment "<!-- this is comment -->" in the double quote.

test6 begin
<!-- this is comment -->
test6 done

Adding HTML Comments in Markdown
If you'd like for your comments to show up in the HTML output, a simple modified HTML comment syntax will work:

<!--- This is an HTML comment in Markdown -->

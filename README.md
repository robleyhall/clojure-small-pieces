# clojure-small-pieces
Clojure in Small Pieces -- Literate Clojure - Created by Tim Daly

Tim Daly's original post
```
 Well, I previously commented that Advocacy is Volunteering
and then I managed to advocate moving clojure to literate
form. Since I'm studying the details of the inner workings
of Clojure this seemed to be the right time to experiment
with a literate form.
I have put together the beginnings of a Clojure in Small Pieces
book. The PDF of the books is at:
http://daly.axiom-developer.org/clojure.pdf
and the literate program sources are at:
http://daly.axiom-developer.org/clojure.pamphlet

The book is in pure latex and requires a single style file at:
http://daly.axiom-developer.org/clojure.sty

The book is hyperlinked so if your pdf reader supports it you
can go to the index and find pieces of code or move from the
table of contents to the appropriate code chunks. Chunking is
very coarse-grained at the moment but will become smaller as
more code is explained.

The literate chunk machinery uses the previously posted code.

The code has been lightly modified to fit into the page format.
Clearly some of the developers have very wide screens. When
rendered on a page in raw form the code runs off the side of
the page. The book sources are 1.3.0-alpha4 (so far). There is
almost no prose in the book yet as the initial format process
has taken up most of the time so far.

You can see from the outline that there is much to discuss.
The goal is to break out the code that implements various
features into sections organized around the ideas, making
it easier to get a "conceptual view" of the code. Suggestions
for other sections are welcome. Feel free to pick a section
that interests you and we can coordinate adding it to the book.
I'm "Acting Editor-in-Chief" at the moment so I get to choose
the final form (mostly for style, flow, clarity, etc).

The aim of the book is to enable anyone to study and contribute
their understanding of portions of Clojure. I am beginning to
study the PersistentTreeMap which is based on Red-Black trees.
In the book you can see that I've split out portions of the
code into the Red-Black section, the Seq section, and the
Iterator section.

I am also experimenting with parallel programming using both
MPI and MapReduce (Hadoop). The idea is to build a multiple
node Ants demo that has N independent ant colonies, one per
parallel node, all being displayed on a single ant field.
I would like the parallel form to be very close in spirit
to Rich's original version so I'll have to document that in
detail first.

Note that the people named on the front cover are from the
author tags in the source code. I have no idea who else might
have worked on portions of the code. If you know, please let
me know.

Literature references are especially welcome. I have a few,
such as the Multi-Version Concurrency Control papers, which
will be added when I get to the STM section.

In any case, this is purely an experiment in literate clojure.
Feedback is welcome.

Tim Daly
```

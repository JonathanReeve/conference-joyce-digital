Joyce in the Digital Age
========================

Conference Details
------------------

 - Sunday, October 1st, 2017, 10am-4:30pm 
 - Studio@Butler, 208B Butler Library, Columbia University 
 - Organizer: Jonathan Reeve, jonathan.reeve@columbia.edu 
 - Sponsors: Columbia University Department of English and Comparative Literature; 
 Columbia University Dean of Humanities; 
 The Society of Fellows and Heyman Center for the Humanities; Butler Library Digital Humanities.

RSVP
----

Attendees, [RSVP using this Google Form](https://docs.google.com/forms/d/e/1FAIpQLScaASilcYuCtrPu-8pKfmv9RFcB6AP6374OLtQGZ-lZD17W2A/viewform) so that we can add your name to the list we give library security. 

Introduction
------------

Advances in digital media have made possible textual technologies like
hypertext, semantic markup, and crowdsourced annotation---technologies
that hold powerful potential applications for scholarly editing. The
works of James Joyce, as highly allusive and self-referential works of
literary modernism, have often been described as proto-hypertexts. As
such, they form excellent subjects for the applications of these
emergent technologies. This single-day conference will present work from
scholars that leverage these new digital techniques toward the creation
of new editions, analyses, or visualizations of Joyce's works. The
keynote lecture will feature Hans Walter Gabler, Professor Emeritus of
Ludwig-Maximilians-Universität, and editor of the most influential
editions of Joyce's novels *Ulysses* and *A Portrait of the Artist as a
Young Man*, who will present his recent work in visualizing the
composition histories of the novels. A series of other talks will
follow, by scholars working in computational approaches to *Ulysses*. In
the afternoon, we will hold a workshop and hackathon, introducing
participants to the new open critical editions of *Portrait* and
*Ulysses*, and providing a brief introduction to textual editing with
the markup language TEI XML (Text Encoding Initiative Extensible Markup
Language). Participants will then be invited to contribute to the
editions, by directly editing the text.

About the Editions
------------------

The [Open-Source Critical Editions of James Joyce's
*Ulysses*](https://github.com/JonathanReeve/corpus-joyce-ulysses-tei)
and [*A Portrait of the Artist as a Young
Man*](https://github.com/JonathanReeve/corpus-joyce-portrait-TEI) will
be the focus of the afternoon hackathon. Since these works have only
recently entered the public domain, the projects are six months and
eighteen months old, respectively, and are in search of more
contributors. They are open-source, open-access, community-owned, and
democratically-edited critical editions. At the moment, they represent
the work of about twelve scholars: Hans Walter Gabler, whose editions
form the base of each text; Ronan Crowley (Universität Passau); Chris
Forster (Syracuse U); Jonathan Reeve (Columbia U); and a number of
undergraduate contributors from Sarah Cole's Fall 2016 course *James
Joyce* at Columbia University. The editions seek to combine the rigor of
modern scholarly editing practices with the rich semantic markup of TEI
XML and the collaborative abilities made possible with distributed
version control systems. Using TEI XML, editors can declare not only the
*appearance* of a segment of text, as with traditional markup, but its
literary or linguistic *meaning* or *function*. Thus, the HTML markup
for italics, `<i>omphalos</i>`, becomes
`<foreign xml:lang="grc-Latin">omphalos</foreign>` in TEI XML,
indicating that the contained word is italicized because it is a foreign
word of Greek origin, written in the Latin script. TEI XML is a
structured method of rich textual description that allows for
computational analyses of the text that would otherwise not be possible.
Dialogue attribution of the form
`<said who="Buck Mulligan">―Come up, Kinch!</said>`, for instance,
allows literary scholars to easily extract the language of each
character, and [analyze the statistical similarities among
them](https://github.com/JonathanReeve/corpus-joyce-ulysses-tei/blob/master/analysis/character-speech.ipynb).
TEI XML also allows for the explicit linking of text and critical
writing, so that it may be possible to create a hypertext edition of the
text that link to the critical articles that discuss it. These tags and
categories should not monolithic, however, since TEI XML provides
mechanisms for encoding spectra of certainty, ambiguity, and divergent
interpretations. The potential of this style of digital scholarly
editing for research and pedagogy is immense, but remains largely
unexplored in 20th Century English literary studies.

### Links:

-   [A short presentation about the
    *Portrait* edition.](http://jonreeve.com/presentations/portrait-xml/)
-   [A proof-of-concept web prototype of the *Portrait* edition, showing
    a few features of the markup.](https://joyce-portrait.netlify.com/)
-   [A proof-of-concept web protoype of the *Ulysses* edition, showing
    dialogue attribution.](https://ulysses-tei.netlify.com/)

### Schedule:

**10am-11:30am**: Presentations from:

-   Moacir P. de Sá Pereira (NYU) on [Fabula and Sjužet in “Wandering
    Rocks”](https://muziejus.github.io/wandering-rocks/)
-   Jonathan Reeve (Columbia), on statistical analyses of character
    voice in *Ulysses*
-   Emily Fuhrman, on [visualizing the "Sirens" episode as a graphic
    score](http://emilyfuhrman.co/projects/joyce-ulysses-sirens-redux.html)
-   Ronan Crowley (U Antwerp), on finding and categorizing (and tagging)
    quotation, allusion, and unmarked borrowing in *Ulysses*

**11:30-12:30pm**: Keynote address, Hans Walter Gabler: "Joyce in the
Digital Age: Genetic Editing and Digital Genetic Editing."

**12-1:30pm**: Break for lunch.

**1:30-2:00pm**: An introduction to the open critical editions of
*Portrait* and *Ulysses*: features of the text, markup conventions,
potential analyses.

**2:00-2:30pm**: An introduction to editing using TEI XML. A quick
introduction to XML (tags, attributes), and then to TEI conventions, to
prepare participants for editing and annotating the editions.

**2:30-4:30pm**: Hackathon: collaborative editing of Portrait and
Ulysses editions.

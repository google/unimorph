These are the raw data that were developed as part of the project reported in
the paper:

Richard Sproat, Bruno Cartoni, HyunJeong Choe, David Huynh, Linne Ha, Ravindran
Rajakumar, Evelyn Wenzel-Grondie. 2014.  A Database for Measuring Linguistic
Information Content. Language Resources and Evaluation Conference, Reykjavík,
Iceland.

[http://www.lrec-conf.org/proceedings/lrec2014/pdf/47_Paper.pdf](https://goo.gl/e4y11Q)

<hr>

# Abstract

Which languages convey the most information in a given amount of space? This is
a question often asked of linguists, especially by engineers who often have some
information theoretic measure of "information" in mind, but rarely define
exactly how they would measure that information. The question is, in fact
remarkably hard to answer, and many linguists consider it unanswerable. But it
is a question that seems as if it ought to have an answer. If one had a database
of close translations between a set of typologically diverse languages, with
detailed marking of morphosyntactic and morphosemantic features, one could hope
to quantify the differences between how these different languages convey
information. Since no appropriate database exists we decided to construct
one. The purpose of this paper is to present our work on the database, along
with some preliminary results. We plan to release the dataset once complete.

<hr>

# Per the paper

Our data are taken from a few domains of interest to Google including driving
directions and answers generated from structured data for Google Now™. (Note
that no Google user data is included in our data collection.)  Obviously such
examples are but a subset of the ways in which language is used to communicate:
The reason for picking data from this circumscribed set of domains is that for
part of the data at least, the text corresponds to, and in a real application
would be automatically generated from, data in a defined format (see below for
an example). Therefore the basic intended meaning of a message is to a large
extent given, thus obviating the need to do semantic annotation. By producing
parallel target sentences in various languages, and making sure that the
translations are as close as possible, while still being stylistically and
socially acceptable, we can be minimize differences in information content that
might arise for irrelevant reasons, such as liberal choices of wording taken by
the translators. We are therefore focusing as much as possible on what the
languages must convey, rather than one what they may convey.

Our initial dataset consists of 85 sentences from a mix of domains for the
following languages: English, French, Italian, German, Russian, Arabic, Korean
and Mandarin Chinese. These languages were chosen from among languages for which
we have very good resources, to be somewhat typologically balanced, representing
languages of the “isolating” or quasi-isolating type (English, Mandarin),
“inflectional” (French, Italian, German, Russian, Arabic) and “agglutinative”’
(Korean). We are also interested in languages with rich case systems (German,
Russian, Korean), gender systems (French, Italian, German, Russian, Arabic),and
a variety of language families — four in this case.2 For the current dataset,
translators were given the English original in a spreadsheet, and were given the
following instructions:

This is a request for natural sounding and socially appropriate translations
which should be inserted directly into the provided spreadsheet in the column
for your language.  Important: There is no character restriction for these
translations. However, we want translations that are succinct as possible,
natural sounding, and socially appropriate.

# The Expert at the Card Table

## Introduction

I have created this project to share in a more modern form the classic on cards manipulation: **The Expert at the Card Table** by **S.W. Erdnase**.

The first step of the project will be to re-write the content of the book using Markdown.  
The second step of the project will be to generate this content in a mobile-first approach.  
Then I would love to re-publish the book, with a modern touch in layout and calligraphy - not in content - but that is for later :)

## Changes

The objective of the project is to remain as close as possible to the original content. Nonetheless some changes are mandatory due to the conversion of format.

**Page numbers** - The conversion to a digital format makes the notion of pages irrelevant, as such we will not try to maintain any information about the pages of the book.

**Pictures** - All pictures will be converted to a vertorized format (like SVG). The pictures were positioned in the book to be near the middle of the page for aestetic reason. As the notion of pages is not kept, the pictures will be placed closest to their first reference.

## Copyright

The original book, published in 1902, is part of the Public Domain and can be accessed as a PDF in the collection of the [Library of Congress](https://www.loc.gov/item/34011788/).

The content of this project has to be considered as released under the [CC0 - Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) licence.

The logo used for the user account has been created by [Tomchen1989](https://commons.wikimedia.org/wiki/User:Tomchen1989) as part of the wikimedia collection and it is licenced through the [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.en).

## Development

To see the documentation locally - on http://localhost:4000 - use the following command:

**Windows**  
`docker run --rm --volume="%CD%/docs:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:pages jekyll serve`

**Linux**  
`docker run --rm --volume="$PWD/docs:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:pages jekyll serve`

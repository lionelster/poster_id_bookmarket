# Page ID Bookmarklet

Bookmarklet that returns a string of text that uniquely identifies the current webpage. The string can be used as **a roughly self-source-citing filename**, helpful for naming media files saved from the web: images, video, audio, etc.

Generally the author is the first part of the string, to help you group items by author.

## Supported webpages

| Page | String |
| --- | --- |
| Reddit post | [username] [post ID] |
| Reddit comment | [username] [post ID] [comment ID] |
| YouTube | [channel name] [video ID] [video title] |
| DeviantArt | [url with `/` each replaced with a space] |
| Instagram\* | [username] [post ID] |
| Facebook | [name] [url with `www.facebook.com`, `/`, and `?` each replaced with a space] |

_\* After exiting the bookmarklet prompt, you will immediately be taken to the direct URL of the media file._

## How to add to your browser

1. In **pageid.js**, copy the single-line of Javascript code under `// without whitespace`.
2. Create a new bookmark in your browser.
3. Paste the code in the URL/location field.
4. Whatever name you like in the name field, e.g. "pageid".
5. Done/OK.

## How to use

1. Go to a single media page (not a front page, news feed, etc.) that this bookmarklet supports.
2. Click on the bookmarklet.
3. Press Ctrl-C to copy the selected text.
4. Press either Enter/Esc or click either OK/Cancel. It doesn't matter lol.
5. Do as you wish with the copied text.

## TODO

* Context (i.e. the site name) and non-context versions
* Check if anything's broken after all these years

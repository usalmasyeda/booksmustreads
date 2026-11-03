# Barakah Reads: bio-link page

A free, cover-led landing page for your Instagram bio link. It is one file (`index.html`) plus a `covers/` folder.

## Put it online for free (GitHub Pages, about 10 minutes)

1. Sign in to github.com and create a new **public** repository, for example `barakahreads`.
2. On the repository page choose **Add file > Upload files**, then upload `index.html` and the `covers` folder. Click **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
4. After a minute or two the page is live at `https://<your-github-username>.github.io/barakahreads/`.
5. Paste that address into your Instagram bio.

## Adding your affiliate links

Open `index.html`, find the `BOOKS` list near the bottom, and replace each `link: "#"` with the book's affiliate link.

## Covers

Each book has an `isbn`. When the page is online, the real cover loads automatically from Open Library's free cover archive.
If Open Library has no cover for that ISBN, the page shows a typeset cover in the brand colours instead.

To use your own image (for example the official cover from your affiliate program):
1. Save it into `covers/`, e.g. `covers/piranesi.jpg`.
2. In the `BOOKS` list set `cover: "covers/piranesi.jpg"`. It takes priority over the ISBN.

Ten books have no ISBN yet (they have many editions, so pick the one you link to): The Sealed Nectar, Men Around the Messenger, The Clear Quran, Tafsir Ibn Kathir, Revive Your Heart, Fortress of the Muslim, Don't Be Sad, Being Muslim, The Productive Muslim and Al-Muhaddithat. Add an `isbn` or a `cover` image for each.

## Changing what's featured

`featured: true` puts a book in "On the feed now". Keep it to three, and move the book you just posted about to the top of the list.

## Instagram button

The button already points to instagram.com/barakahreads.

# Bookshelf

A free bookshelf that learns what you like to read, then writes the prompt for your own chatbot to recommend what to read next.

**[Open the live bookshelf](https://lifeofaelita.github.io/bookshelf/)**. There is nothing to install, no account to make and nothing to pay for.

![Your shelf](docs/shelf.png)

## What it does, and what it does not

Most book apps ask for a star rating and stop there. This one asks two questions about every book: how much the ideas mattered to you, and how easy it was to keep reading. That second score is what explains why you gave up on a book you were sure you would love.

- It shows your books on a wooden shelf, sorted by genre.
- It works out what earns a five from you and what makes you stop.
- It writes a ready-made prompt from your shelf. You paste that prompt into Claude, ChatGPT or Gemini and the chatbot suggests what to read next.
- It does not contain a chatbot, send emails or collect your data. That is why it costs nothing.

## Why not Kindle or Kobo recommendations?

Kindle and Kobo learn from what you buy and how many stars you give. That works while your taste stays put. Mine did not. Over the years my style changed so much that the suggestions kept describing a reader I no longer was, because every old purchase counted as much as last month's.

A star rating also hides the reason behind it. A three-star book might have been brilliant and heavy going, or easy and forgettable, and a store cannot tell which. The two scores here separate those cases, and a book you gave up on tells the chatbot something too.

## Why I built it

I am 39 and I am still finding out what I like to read. For years I loved the idea of the books I was supposed to read, then struggled once I started them. This year was about learning what I enjoy and being fine with the fact that not every book has to be educational. The bookshelf is how I keep track of that, and it is why the reading score sits next to the ideas score.

## Start in five minutes

1. **Open the page.** Go to the live link above. You will see 13 sample books so you can look around first.
2. **Add your own books.** Open the **Add books** tab and pick whichever option suits you (see below). When your own books are in, press **Clear the sample books** on the shelf.
3. **Rate a few.** Click a book to open it, then set your rating and the two scores. Ten rated books is enough for good picks. Three is the minimum.
4. **Get your prompt.** Open **Get picks**, choose how many picks you want and press **Build my prompt**, then **Copy the prompt**.
5. **Paste it into a chatbot.** Use the Claude, ChatGPT or Gemini links under the prompt. Free plans work.

## Four ways to add books

![The Add books tab](docs/add-books.png)

Aim for about 10 books with a rating, because that is when your patterns start to show. The page accepts as few as three, but the picks stay general until you add more.

| Option | Best for | How |
| --- | --- | --- |
| Start from ten titles | Anyone with no Goodreads history | Paste ten books you have read into a chatbot with [prompts/06-first-shelf-from-ten-books.md](prompts/06-first-shelf-from-ten-books.md). It writes a file you import, plus suggested Ideas and Reading scores for you to check. |
| Import from Goodreads | Anyone with a long reading history | On Goodreads open **My Books**, then **Import and export**, then **Export Library**. Download the file, then choose it under **Import from Goodreads** on the Add books tab. Books you already have are skipped. |
| Add one book | A short list, or books you read recently | Fill in the form on the Add books tab. Only the title is required. |
| Import from another app | StoryGraph users | Export your library as a CSV file and import it the same way. The common column names are recognised, but not every export has been tested. |

Imported books land on the right shelf when the genre is clear, and on **Not sorted yet** when it is not. Open a book to move it. The file [prompts/04-sort-my-books.md](prompts/04-sort-my-books.md) shows how to ask a chatbot to sort a long list for you.

## How the two scores work

Open any book and you will see three controls.

![Open a book to rate it](docs/book-drawer.png)

| Control | What it measures | Example |
| --- | --- | --- |
| Rating | How much you enjoyed it overall, 1 to 5 | 3 stars |
| Ideas | How much the subject and ideas mattered to you, 1 to 5 | 5 |
| Reading | How easy it was to keep reading, judged by pace, structure and voice, 1 to 5 | 2 |

That example is a book you found brilliant and a slog. It tells the chatbot that the topic suits you and the style does not, so it should suggest a lighter, story-led book on the same subject instead of another heavy one.

A few more rules the prompt passes on to the chatbot:

- A book you did not finish is a clue about style, even when you do not say why.
- A book you read because you felt you should counts for less than one you chose with enthusiasm. Mark this under **Why you picked it up**.
- Recent reads count more than old ones. Fill in **When you read it** to help.

The shelf also has a key, **How to read your shelf**, that explains the number badges, the red ribbon (a five), the dark DNF badge and the TBR badge.

![How to read your shelf](docs/key.png)

![What your shelf says about you](docs/taste.png)

## Getting your recommendations

![The Get picks tab with a ready prompt](docs/get-picks.png)

**What should I read next?** (the Get picks tab)

- Choose 3, 5 or 8 picks.
- Choose a format: any, ebook or paperback, or audiobook.
- Add anything to avoid or include, for example "nothing set in wartime".
- Tick the weekly box if you want a repeating prompt (see below).

**Will I like this book?** (also on the Get picks tab)

Type a title that someone recommended. The prompt asks the chatbot to compare it with your shelf and score the ideas fit and ease of reading out of 100. If the chatbot does not recognise the book, it should say so and mark its confidence as low.

Always glance at the picks before you buy. Chatbots occasionally invent books, and the prompt tells them to leave out any title they are unsure exists.

## Picks every week

The page cannot email you, because it has no server. You have three options, all free:

| Option | How |
| --- | --- |
| Ask the chatbot to repeat it | Tick the weekly box, paste the prompt into a new chat and ask for fresh picks every Monday. |
| Use the chatbot's own scheduling | ChatGPT has a Tasks feature and Claude has scheduled tasks on some plans. Plans change, so check what yours offers. |
| Set a calendar reminder | A repeating Monday reminder that says "get book picks". Update your shelf first so the prompt includes last week's reading. |

## Sale watch

If you buy ebooks, you can ask a chatbot which wishlist books are worth buying when they drop in price. The page cannot watch prices itself, so you paste your wishlist with today's prices, or let a chatbot that can browse check them. The prompt is in [prompts/05-sale-watch.md](prompts/05-sale-watch.md), along with free price-alert services such as eReaderIQ and BookBub.

## Your data and privacy

- Everything is saved in your browser on your device. Nothing is uploaded to a server.
- It is saved per browser and per device. A different computer, or a private window, starts empty.
- Clearing your browser data erases the shelf. Press **Download a backup** now and then. To move to a new device, open the page there and press **Restore from a backup**.
- **Start again** erases everything and asks you to tap twice so it cannot happen by accident.
- Book covers load from Open Library when an imported book has an ISBN. Books without one get a coloured cover with the title.

## If something goes wrong

| Problem | Fix |
| --- | --- |
| The shelf is empty after I came back | You are in a different browser, a private window or on another device. Restore your backup file. |
| The import added no books | Make sure you chose the exported CSV file and that it has a Title column. |
| Most books are on Not sorted yet | Open a book to choose its shelf, or ask a chatbot to sort the list with prompts/04-sort-my-books.md. |
| The Build my prompt button asks for more ratings | Rate at least three books first. |
| The Copy button does not work | Click inside the prompt box and press Ctrl+C or Cmd+C. |

## Use it without the page

The **prompts** folder holds plain-text versions you can paste straight into a chatbot: build a taste profile, weekly picks, check a single book, sort books into shelves, and build your first shelf from ten books.

## Run your own copy

1. Press **Fork** at the top of this repository, or download it with **Code, Download ZIP**.
2. To open it on your computer, unzip it and double-click **index.html**.
3. To host it free on GitHub Pages: in your fork open **Settings**, then **Pages**, choose the **main** branch and the **/ (root)** folder, and press Save. Your page appears at your-name.github.io/bookshelf after a minute or two.

The code is one HTML file plus the **fonts** and **wood** folders. There is nothing to build.

![Genre guide](docs/genre-guide.png)

## Checking it works

[TESTING.md](TESTING.md) is a 15-minute checklist covering the page, a phone and a chatbot. [examples/sample-goodreads-export.csv](examples/sample-goodreads-export.csv) is a small file you can use to try the import.

## Credits

Built by [Aelita](https://github.com/lifeofaelita) with Claude. The sample books are examples only and their ratings are made up. Licence: MIT, so you are free to use and change it.

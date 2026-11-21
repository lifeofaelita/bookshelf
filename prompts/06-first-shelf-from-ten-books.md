# Prompt 6: build your first shelf from ten books

Use this when you are starting from nothing, with no Goodreads history. Ten books you have already read is enough for the page to find patterns. Three is the least it will accept.

Paste the prompt into Claude, ChatGPT or Gemini, then paste your list under it. For each book give the title, the author, your own star rating out of 5 and a few honest words, including any book you stopped reading.

```
I am setting up a reading shelf from scratch. Below are books I have read, each with my star rating out of 5 and a few words on what I thought.

Do two things.

PART 1. Write a CSV I can save as a file and import. Use exactly this header and one row per book:

Title,Author,My Rating,Exclusive Shelf,Bookshelves,Date Read

Rules for the columns:
- My Rating: copy my rating. If I did not give one, leave it empty. Never invent a rating for me.
- Exclusive Shelf: use read, did-not-finish or to-read.
- Bookshelves: use one genre word from this list: thriller, sci-fi, cosy, literary fiction, memoir, history, psychology, self-help, spiritual. If none fits, leave it empty.
- Date Read: a year if I gave one, otherwise empty.
- Put any title or author that contains a comma inside double quotes.

PART 2. Make a short table with the columns Title, Ideas, Reading and Why.
- Ideas: how much the subject and ideas seem to have mattered to me, from 1 to 5.
- Reading: how easy the book seems to have been to keep reading, from 1 to 5, judged by pace, structure and voice.
- Why: a few words pointing to what I wrote.
Base every score only on my own words. If my words do not say enough, write "not enough to tell" instead of guessing.

Do not recommend any books yet.

MY BOOKS:
[paste your list here, one book per line: title, author, rating, a few words]
```

What to do next:

1. Copy the CSV into a plain text file and save it with the ending .csv.
2. In the page, open **Add books** and choose the file under **Import from Goodreads**.
3. Open each book and type in the Ideas and Reading scores from the table. The import does not carry those two scores across, and you know better than a chatbot how a book felt, so change any that look wrong.

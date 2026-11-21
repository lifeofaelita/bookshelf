# Testing checklist

Run through this before you share the link. It takes about 15 minutes.

## In the browser (desktop and phone)
- [ ] The live page loads with sample books and no errors
- [ ] Add one book on Add books and find it on My shelf
- [ ] Import `examples/sample-goodreads-export.csv` and see four books added
- [ ] Open a book, change rating, scores, shelf and notes, close, reopen: changes stayed
- [ ] Reload the page: your books are still there
- [ ] Back up, Start again (tap twice), then Restore the backup file: books return
- [ ] My taste and Genre guide fill in once you have rated three or more books
- [ ] Phone width: nothing runs off the screen

## With a chatbot
- [ ] Read next: copy the prompt, paste it into Claude, ChatGPT and Gemini, paste each reply back and check you get picks as cards with match scores
- [ ] One-link setup: paste the one line into a chatbot, answer its questions, paste the shelf block into Add books and check the books appear
- [ ] Sale watch: paste a wishlist, paste the reply back and check the worth-buying rows and links
- [ ] Will I like this book: try one you know and one that does not exist, the second should come back as low confidence

## For someone else
- [ ] Ask a friend to follow the README from the top, unaided. Fix anything they stumble on.

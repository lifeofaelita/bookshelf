# Prompt 5: sale watch

This one scores the books you want to buy against your taste, so that when one goes on sale you know whether it is worth buying. It is the same idea as a weekly wishlist scan, run by your own chatbot.

The page cannot watch prices, so the chatbot needs the prices from you or from its own web access. Pick the mode that matches your chatbot.

**Mode A: works in any chatbot.** Copy your wishlist from your Kobo, Kindle or Amazon wishlist page, with the prices you can see today, and paste it where the prompt says.

**Mode B: chatbot with web browsing or scheduled tasks.** Give it the link to your wishlist and ask it to check prices itself every Monday. Wishlists are often private, so it may need you to be signed in. If it cannot open yours, fall back to Mode A.

```
You are my book sale watcher. Tell me which books on my wishlist are worth buying at today's price, using only my reading history.

MY READING HISTORY:
[paste your shelf, or the history block copied from the Get picks tab]

MY WISHLIST WITH TODAY'S PRICES:
[paste titles, authors and prices, or give your wishlist link]

Score every wishlist book from 0 to 100 for how likely I am to enjoy it, based on my ratings, and give one short reason that names a book from my history. If I have given you no basis for a score, write "not scored" instead of guessing.

Then show a table ordered by score: title, author, price, on sale or not, score, reason.

Flag as "buy now" any book that is on sale and scores 80 or more. Say so plainly if nothing qualifies. Do not recommend books that are not on my wishlist, and do not invent prices. If you could not check a price, say "price unchecked".

Every Monday, run this again, tell me what changed since last time, and ask me to update my ratings first.
```

Scores are reasoned estimates, not a trained model. They sharpen as you confirm ratings and add books. Check the price in your store before you buy, because stores change prices and regions.

## Setting price alerts yourself

These free services watch prices for you. None of them is part of Bookshelf, and plans and features change, so check each one before relying on it.

- **eReaderIQ** emails you when a Kindle book reaches a price you choose. You add books by ASIN or Amazon link.
- **BookBub** sends a daily email of ebook deals by genre. It shows all deals, not only your wishlist.
- **Amazon wishlist** sometimes emails about sales, though not reliably.
- **Kobo wishlist** may email price drops. One reader reports this, but I could not find an official Kobo page confirming it, so check your own account settings.

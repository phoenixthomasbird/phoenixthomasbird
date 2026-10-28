# Phoenix T. Bird

I believe AI should be used as a tool and not a crutch. As someone with a documented disability, I have used AI to make up the difference in how my brain thinks and how the world around me functions. I am currently working on a few different applications designed to help others bridge the gap between what they can do and what the world expects of them using the tools and support that AI offers.

## What I'm working on

**Bōcere** (TypeScript, Electron; source private, [prototype installers public](https://github.com/justhurkledurkling-max/bocere-releases))
A desktop app for writers. The design question: how do you bridge the gap between human and AI without AI generating content? Bōcere is designed to make writing easy, editing manageable and prepress a click of a button. It has no AI chat of its own. Books are plain Markdown files, so the author's own AI tools can read them, but the app controls how any outside change reaches the page.
- Every outside change, from an editor or from the author's own AI, arrives as a tracked change. The author accepts or rejects each one, and nothing touches the text until they do.
- Bōcere writes a guide into each book folder (`AGENTS.md` and `CLAUDE.md`) telling AI tools to suggest rather than rewrite, and how to send suggestions so they open in the app as tracked changes.
- Author and editor pass versions back and forth. Only what changed is marked, and a renamed or renumbered chapter is matched by its words, not its file name.
- The page has no network access, and only the main process reads or writes the author's files.
- The accounts server's row-level security is tested by running the real SQL in an in-memory Postgres and having an author, an editor, a stranger and a publisher each try what they should and shouldn't be able to do.

**[More projects](https://github.com/phoenixthomasbird/phoenixbird-portfolio)**: a Claude tool-use research agent, a Hebrew speaking tutor, an Agent SDK experiment, and the Python I wrote while learning.

## How I work

- I spend 30 minutes every morning writing down all of my crazy ideas on a sheet of paper while enjoying a cup of coffe.
- I focus on a few select tasks for the day: edit a book, add features to the app, draft another book, etc.
- To date I have used Bōcere to assemble and print 8 books. My first prototype was a web app version assembled in July of this year. I moved the concept into Electron by the end of September, though had my first printed book in hand by September 4th, 2026, produced through the web app prototype.
- My day ends with walking my Cardigan Corgi puppy, Watson, around the neighborhood before enjoying a glass of wine with a home cooked meal.
- 

## Also

- I'm an artist and love to cartoon. I developed my own art style for a comic about parenting. Still a work in progress. 
- I'm also a licensed Home Inspector in the state of Washington. Not that I've done much with it due to factors outside of my control, but I have the license and know a thing or two about houses. → [phoenixtbird.com](https://phoenixtbird.com)

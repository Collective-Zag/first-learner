# first-learner

The Gumption first-learner page: the tool Pichi uses to watch a finished case
and log his answer at each Socratic pause.

Served at https://first.gumptioner.com

Deliberately outside the platform Rafa is building. Static, no accounts, no
build step. One file.

- `index.html` is the whole site.
- `CNAME` holds the custom domain.

Each case carries its YouTube video id and the pause times measured from its
lock record. The page stops the video at each pause and will not continue
until an answer is typed. Answers are held in the phone's own storage and sent
to Daniel on WhatsApp.

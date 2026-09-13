# bot-state

Machine-managed branch. Do not edit, merge or delete.

`jobs.db` is the AI Job Hunter's deduplication database -- the record
of every posting ever seen and every alert ever sent. It is what stops
the same job being sent to WhatsApp twice.

This branch is force-pushed as a single commit on every run so the
repository never accumulates binary history. Deleting it makes the bot
forget everything and re-alert on jobs you have already been told about.

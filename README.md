# backups/

This folder is managed automatically by the GitHub Actions weekly backup workflow.

`strains.json` is overwritten every Sunday at 6:00 AM UTC with a full export
of the Supabase `strains` table. Each commit is timestamped, so the full
backup history is preserved in Git — you can browse or restore any previous
week from the commit log.

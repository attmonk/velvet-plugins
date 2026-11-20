# ATTMonk repository

## ATTMonk bot attribution and clean history

Use `attmonk-ci <342793482+attmonk-ci[bot]@users.noreply.github.com>` for both
author and committer. Set `attmonk.requireBotAttribution=true` in this checkout
and keep the commit guard enabled. Use Conventional Commits and no co-author
trailers. Pushes, tags, workflow runs and releases use the existing ATTMonk
GitHub App; CI credentials accept `ATTMONK_CI_APPKEY` or `ATTMONK_CI_APP_KEY`.

Keep history limited to clean ATTMonk snapshots and subsequent reviewed work.
Do not merge or push retired histories, branches or tags. Import upstream work
through reviewed patches or source snapshots so retired ancestry is not restored.
Legacy deployment compatibility values belong in local/server environment
configuration, never tracked source. Preserve runtime identities and storage
together when migrating existing installations.

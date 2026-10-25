# Social Demand Intelligence OS — published portal

This repo holds **only the built site** (a single self-contained HTML file). The
source code lives in a private repo; every push there rebuilds and republishes
here automatically.

Live: https://barisknightwork-ship-it.github.io/sdios-portal/

It is the front end for a Bangalore housing-demand desk: it reads live leads from
Supabase (Devi webhook + a Supabase cron that sorts each post with a model chain)
and falls back to a rule engine when the models are unreachable.

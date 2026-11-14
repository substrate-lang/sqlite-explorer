# sqlite-explorer

A dashboard, a query page and a database page over a made-up shop's data,
written in [Substrate](https://github.com/substrate-lang/substrate) on web-ui
and substrate-sqlite. SQLite runs in the page. Queries are written in a small
query language, a Substrate DSL. The dashboard's queries become SQL when the
program compiles. The query page's queries become SQL in the browser.

    substrate test -A          # the tests, ten of them in Chromium
    substrate build            # the site, in build/sites/explorer

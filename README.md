```
█▀█ ▄▀█ ▀█▀ █▀█ █ █▀▀ █▄▀   █▀▀ █▄ █ █▀▄ █▀█ █▀▀ █▀▀
█▀▀ █▀█  █  █▀▄ █ █▄▄ █ █   ██▄ █ ▀█ █▄▀ █▀▄ ██▄ ▄▄█

data engineer · python · sql · snowflake · patrickendr.es
```

```console
$ whoami

Data engineer. I work on the unglamorous half of the stack — ingestion,
modeling, and the warehouse jobs that have to be correct at 6am whether
or not anyone is awake to check.

Mostly Python and SQL against Snowflake. Comfortable owning a pipeline
end to end: pull it, type it, land it, and make the failure mode obvious
instead of silent.

Currently learning Go.
```

```console
$ stack --sorted

python       ████████████████████░░░░   daily driver · requests, bs4, dataclasses
sql          ███████████████████░░░░░   snowflake, stored procedures, modeling
bash / git   ███████████████░░░░░░░░░   glue, cron, ci
javascript   ██████████░░░░░░░░░░░░░░   enough to be dangerous
go           █████░░░░░░░░░░░░░░░░░░░   in progress
```

```console
$ ls -1 ~/projects
```

<pre><table>
<tr><td><b><a href="https://github.com/patrickendres/gi_scraper">gi_scraper</a></b></td>
<td>Multi-tenant Shopify catalog scraper. Walks a list of storefronts, normalizes
<code>products.json</code> into typed <code>dataclasses</code> (product / variant / image), and lands flat
CSVs. Uses <code>curl_cffi</code> to survive TLS fingerprinting. Python</td></tr>

<tr><td><b><a href="https://github.com/patrickendres/nhl_wiki_agg">nhl_wiki_agg</a></b></td>
<td>Aggregates all 32 NHL rosters off Wikipedia into one normalized CSV — or one
per team. Generator-based parsing, identifies itself with a real User-Agent,
raises on bad status instead of silently writing garbage. Python · BeautifulSoup</td></tr>

<tr><td><b><a href="https://github.com/patrickendres/boxing_wiki_agg">boxing_wiki_agg</a></b></td>
<td>Flattens current boxing rankings — every division, every sanctioning body — into one
deduplicated roster per division. Building it surfaced three bugs in the parse: a hardcoded
division count silently dropping Strawweight, two fighters glued into a single name, and
title annotations breaking dedupe across bodies. Python · BeautifulSoup</td></tr>
</table></pre>

```console
$ cat notes/why-scrapers.md

All three are scrapers, which is on purpose. Public data on the
open web is the closest thing to a real ingestion problem you can run on
a laptop: the schema drifts, the markup is inconsistent, the source is
rate-limited, and nobody is going to fix it upstream for you. Everything
that makes a production pipeline annoying is already there.
```

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=patrickendres&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000&title_color=3fb950&icon_color=3fb950&text_color=8b949e">
  <img src="https://github-readme-stats.vercel.app/api?username=patrickendres&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000&title_color=1a7f37&icon_color=1a7f37&text_color=57606a" alt="GitHub stats">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=patrickendres&layout=compact&langs_count=6&hide_border=true&bg_color=00000000&title_color=3fb950&text_color=8b949e">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=patrickendres&layout=compact&langs_count=6&hide_border=true&bg_color=00000000&title_color=1a7f37&text_color=57606a" alt="Top languages">
</picture>

</div>

```console
$ cat contact.txt
```

<pre>web      <a href="https://patrickendr.es">patrickendr.es</a>
mail     <a href="mailto:patrickjendres92@gmail.com">patrickjendres92@gmail.com</a>
github   <a href="https://github.com/patrickendres">@patrickendres</a>
</pre>

```console
$ _
```

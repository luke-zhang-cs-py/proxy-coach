# Proxy Coach prototype (live page)

**Open it:** https://luke-zhang-cs-py.github.io/proxy-coach/

This is an AI coaching prototype for licensed real estate agents at a New York City brokerage. It follows one agent's working day and the managing broker's weekly view: which leads to call first, call prep, follow-up drafts, listings checked against New York's fair housing, broker-fee and advertising rules, commission slips, practice role-plays and a rules and zoning briefing.

- **Sample data only.** Every client, address, number, split and fee is made up. The coach's answers are prewritten, so no AI model is called.
- **Nothing is saved.** Use "Reset demo" in the header or reload the page to start over.
- **Two views.** "Viewing as" switches between the agent (Jamie L.) and the managing broker (Ryan).
- **Not legal advice.** The rules briefing cites its sources and was current as of October 2026.

This repository only hosts the page for GitHub Pages: `index.html` is the whole app in a single file, with no build step. Development, browser tests and CI happen in a separate private repository, and each tested version of `index.html` is copied here.

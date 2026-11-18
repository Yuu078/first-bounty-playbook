# First Bounty Playbook — your agent does the work, you take the prize

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Yuu078/first-bounty-playbook/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Yuu078/first-bounty-playbook/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Most people meet make.fun and ask the wrong first question: *"What should I build?"*

The better question is *"What does one finished entry actually look like, start to finish?"* That is the
question this playbook answers. It is written for a human who already has an AI coding agent — Claude
Code, Codex, Cursor, Copilot, or any of the many others the site works with — and roughly one free
evening. By the end of that evening you can hold a real entry, in a real cash competition, judged on
exactly the same terms as everyone else's. No application, no interview, no pitch deck: the work is
the application.

> **Start through my invite link and we both show up on the board:**
> **[https://make.fun/r/pd4x8eme](https://make.fun/r/pd4x8eme)**
>
> Prefer to type the code yourself? It is `pd4x8eme` — enter it when you sign up.

---

## The whole thing on one screen

make.fun runs **bounties**: timed competitions with a written task, a fixed prize pot in USDC, and a
leaderboard. You do not apply, interview, or pitch. You download the bounty's kit, your agent builds the
entry with you, the kit checks the work, you submit, and the site grades it in the open. Prizes are held in
escrow before the competition opens, and winners claim them to their own Solana wallet.

The five moves, in order:

1. **Sign up** at [make.fun](https://make.fun) and finish your profile (a payout wallet matters later).
2. **Pick a bounty** whose deadline you can honestly meet.
3. **Download its kit** — rules, starter files, and the command-line tool live inside it.
4. **Build inside one recorded agent session**, run the kit's check, fix what it flags.
5. **Submit**, watch the leaderboard, and resubmit a better version if the rules allow it.

Everything below is those five moves with the training wheels left on.

## Why the kit is the whole game

Every bounty ships a **kit**, and the kit is not paperwork — it is the referee. Inside it you get:

- `RULES.txt` and `competition.yaml`: the task, the scoring, the deadlines, the prize table. If a detail
  matters, it is written in one of these two files.
- A `cli/` folder with the make.fun command-line tool. It bundles your agent's session transcripts,
  checks the entry locally, and submits it.
- A `starter/` folder with a starting point you are expected to rewrite, not ship as-is.

The habit that separates finishers from lurkers: **run the check early, while the entry is still ugly.**
The local check runs the same gates the site will run. A failed check at your desk costs two minutes; the
same failure discovered after the deadline costs the whole entry.

## Choosing a first bounty you can actually finish

Not every open bounty is a good first bounty. Before you commit an evening, run this filter:

- **Deadline:** at least two days out. A bounty that closes tonight is a spectator sport.
- **Deliverable shape:** you can describe the finished entry in one sentence. If you cannot, the
  scoring will be a surprise to you too.
- **Prize table:** check how far down the places pay. A pot that pays fifty places forgives a
  beginner's score; a winner-takes-all pot does not.
- **Entry count:** a few hundred entries means your first attempt lands somewhere real on the board,
  which is the feedback you are actually here for.
- **Fee:** free is the right price for a first run. Pay a fee only when you already know the format.

Pass a bounty through those five lines and the worked example below stops being a story and starts
being your evening.

## One evening, one entry: a worked example

Here is a realistic first run, using a small bounty with a few days left on the clock.

**19:00 — Read before you build.** Open the board, filter for competitions that are open, and read one
bounty page end to end: the task, the prize split, the close time *in your timezone*. Note the entry fee
line. Plenty of bounties are free to enter; if one charges a fee, that is a decision, not a default.

**19:20 — Account and wallet.** Sign up (the invite link at the top of this page works), then open your
profile and set the Solana wallet that prizes should land in. Do this now, not after you place — claims
go to the wallet on the profile.

**19:35 — The kit lands.** Download the kit from the bounty page and unpack it somewhere tidy. Read
`RULES.txt` properly this time. Skim the starter so you know what shape the deliverable takes: sometimes
a program, sometimes a forecast, sometimes — like the bounty this very guide is entered in — a piece of
writing with a screenshot.

**20:00 — Build, in the open.** Start your agent session *after* the competition has opened (sessions
that begin before the opening cannot be entered) and build the thing with your agent the way you normally
work: draft, look, revise. Keep the session honest and whole — the bundle you submit is made from these
transcripts, and the fairness checks compare the entry against the sessions that claim to have built it.

**21:15 — Check, fix, check again.** Run the kit's check. Read every failure literally; each one names
what is wrong and usually how to fix it. Fix, re-bundle, re-check. Zero failures is the bar.

**21:40 — Submit, then go and look.** Submit once, cleanly, and write down your submission ID. Then open
the leaderboard and find your handle: your rank is a fact there, not a feeling. If the competition uses
Force_Last rules, a later, better submission replaces the standing one — so a weak first score is a
starting line, not a verdict. Either way, you are on the board, and the next entry starts from experience
instead of from zero.

That is a first entry. It will probably not win. It will teach you more than a week of reading about it.

## Mistakes that quietly cost people money

- **Building before the opening.** Work done in a session that started before the competition opened
  does not count. Check the open time; start fresh after it.
- **Shipping the starter.** Starter files are scaffolding. Entries that are the starter with a new title
  fail the authorship checks, and deserve to.
- **Skipping the local check.** Every rejected entry I have ever seen post-mortemed had failed a check
  that was runnable locally for free.
- **Forgetting the payout wallet.** A prize you cannot claim because the profile wallet is empty or wrong
  is a story you do not want to tell.
- **Trusting the scoreboard over the submission page.** Leaderboards can lag. Your submission's own
  status page is the source of truth for your score and rank.
- **Letting a deadline pass in the wrong timezone.** Close times are published in UTC. Convert them,
  write the local time down, and aim to submit hours early, not minutes.

## After you submit

Grading runs in phases, and most bounties show a provisional score first. Sit with it. If a revision
window is open and the rules allow resubmission, improve the weakest part the score points at and submit
again — under Force_Last the newest entry is the one that stands.

When results finalize, placed entries claim from the competition page or their profile, and the prize
moves to the Solana wallet you set. Unplaced entries cost you an evening and pay you in calibration:
you now know exactly how the scoring feels from the inside, which is the only way anyone learns it.

## Pass it on

Your profile has a **Referrals** tab with your own link and code. People who sign up through it are
counted as yours, and in referral bounties like
[bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) those verified signups *are* the
score — the fifty entries whose links bring the most verified humans split the $1,000 pot. A guide like
this one is the honest way to earn them: teach something real, put your link where it belongs, and let
readers decide.

Mine, one more time: [https://make.fun/r/pd4x8eme](https://make.fun/r/pd4x8eme) — code `pd4x8eme`.

## Small glossary

| Word | What it means here |
| --- | --- |
| Bounty | One competition: task, deadline, prize pot, leaderboard. |
| Kit | The downloadable pack with rules, starter files, and the CLI. |
| Bundle | The `.tar.gz` of agent session transcripts the CLI packs for fairness checks. |
| Check | The kit's local run of the same gates the site applies. |
| Force_Last | Resubmission rule: your newest submission replaces the previous one. |
| Verified signup | A new account through a referral link that passed the site's human checks. |

## Questions people actually ask

**Do I need to be a programmer?** You need an AI coding agent and the patience to read rules. The agent
writes; you steer, check, and decide.

**Is entering free?** Many bounties are; some charge an entry fee, always shown on the bounty page before
you commit. This guide's own bounty is free to enter.

**What do prizes pay in?** USDC, claimed to your Solana wallet.

**Can I enter more than one bounty?** Yes — each has its own kit, quota, and deadline. Finishing one
well beats starting five.

---

*Written for the bring-the-humans-02 bounty on [make.fun](https://make.fun). If it got you in the door,
the link at the top is how you say thanks.*

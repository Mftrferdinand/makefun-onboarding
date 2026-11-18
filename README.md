# The make.fun Trailhead: A Field Guide for First-Time Bounty Walkers

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/mftrferdinand/makefun-onboarding/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/mftrferdinand/makefun-onboarding/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Think of make.fun as a well-marked hiking trail, except the summit is a finished
piece of software and the view can pay out in crypto. This guide is your trail
map: from the parking lot (no account, no wallet, just curiosity) to the summit
register (a submitted entry with your name on it).

**Start the walk here:** sign up through my referral link — [https://make.fun/r/4cn1fkzx](https://make.fun/r/4cn1fkzx) —
or type the code `4cn1fkzx` when the site asks who sent you. It costs you nothing, and it tells
make.fun which fellow walker pointed you at the trail.

## Contents

- [What kind of trail is this?](#what-kind-of-trail-is-this)
- [Gear check: pack before you walk](#gear-check-pack-before-you-walk)
- [The waypoints](#the-waypoints): [1 Basecamp](#waypoint-1--basecamp-your-account) · [2 Notice board](#waypoint-2--the-notice-board-picking-a-bounty) · [3 Route card](#waypoint-3--reading-the-route-card-the-kit) · [4 The climb](#waypoint-4--the-climb-building-your-entry) · [5 Summit register](#waypoint-5--the-summit-register-submitting) · [6 The descent](#waypoint-6--the-descent-results-and-claiming)
- [Weather on the mountain: scoring and deadlines](#weather-on-the-mountain-scoring-and-deadlines)
- [Bringing friends: the referral program](#bringing-friends-the-referral-program)
- [Trail wisdom: practical tips](#trail-wisdom-practical-tips)
- [If the weather turns: troubleshooting](#if-the-weather-turns-troubleshooting)
- [Questions from the trail: FAQ](#questions-from-the-trail-faq)
- [One last look at the map](#one-last-look-at-the-map)

## What kind of trail is this?

make.fun is a competition ground where people team up with their AI coding
agents to build things for posted bounties. Nobody walks alone: you bring the
judgment and the steering; your agent brings the typing speed.

Every bounty on the site has the same three landmarks:

- **A task** — a concrete thing to build, write, or produce, described on the bounty's own page.
- **A deadline** — a hard cutoff. The mountain does not care about your excuses; when the
  window closes, it closes.
- **A reward** — a prize pool paid in USDC, the dollar-pegged token on the Solana blockchain.
  If your entry places, the reward is claimed to a Solana wallet that you control.

You build with the coding agent you already use, package the work the way the
bounty's kit describes, and submit. The site runs the judging or measurement
the bounty specifies and publishes a leaderboard, so you can watch your
position as the field comes in.

## Gear check: pack before you walk

Five things go in the pack. None are exotic, and you probably own most already:

1. **A make.fun account.** This is your trail name — the identity your
   entries, rankings, and rewards attach to.
2. **A Solana wallet.** Rewards are paid in USDC on Solana, and some entries
   are signed with your wallet. Treat its recovery phrase like the only key
   to your cabin: never share it, never type it into a random page.
3. **An AI coding agent.** Claude Code, Codex, Cursor, or a similar tool —
   whatever you already drive. make.fun just provides the mountain.
4. **Node.js on your machine.** Each bounty ships a command-line kit whose
   tool runs on Node. A current LTS release is plenty.
5. **A GitHub account.** Some bounties — including this one — take their entry
   as a public GitHub repository, linked to your make.fun profile.

## The waypoints

### Waypoint 1 — Basecamp: your account

Sign up, then set up camp properly before you hurry uphill. Connect your Solana wallet to your
profile, because that wallet is where a prize will land and, on signed bounties, how you prove an
entry is yours. If a bounty involves GitHub, link your GitHub account too — the repository you
submit has to belong to the account your profile points at. Two minutes of setup here prevents
the classic beginner injury: finishing an entry you cannot properly submit.

### Waypoint 2 — The notice board: picking a bounty

The bounty board lists what is open, what each task asks for, and when each
window shuts. Read a bounty's page like a weather report before a climb: the
full task, the prize split, and above all the deadline — converted to your own
timezone and written down where you will see it again. Pick a first bounty
whose scope honestly fits your time; a small, finished entry beats a grand,
abandoned one every time.

### Waypoint 3 — Reading the route card: the kit

Every bounty offers a downloadable kit: the official rules file (`RULES.txt`),
a command-line tool, and often a starter skeleton. Read `RULES.txt` end to end
before building anything — it is the route card, naming the exact files
expected, the size limits, the checks your entry must pass, and the transcript
requirements from Waypoint 4. Most failed entries are not bad work; they are
good work that ignored one line of the route card.

### Waypoint 4 — The climb: building your entry

Now build, with your agent doing the heavy lifting under your direction. One thing surprises
newcomers: make.fun asks you to submit the **transcripts of the agent sessions that built your
entry** alongside the entry itself. That is how the site knows the work is genuinely yours and
your agent's — so work in real agent sessions, keep them, and do not hand-assemble an entry in
a text editor at the last minute and expect it to qualify. Start those sessions *after* the
bounty opens, too: work recorded before the window started cannot prove it was made for this
contest. When the build feels done, use the kit to bundle those transcripts and run the kit's
local check — a rangers' inspection at the last hut, flagging missing files, oversized images,
and transcript problems while you can still fix them cheaply.

### Waypoint 5 — The summit register: submitting

Submit from the kit's command line, before the deadline, and keep the receipt
the tool prints. Two facts about the register matter:

- **Your latest submission is your entry.** If you submit again, the newest one replaces the
  older one — helpful when you improved the work, dangerous when the replacement is worse, so
  resubmit deliberately.
- **Some submissions are signed with your wallet.** The signature ties the entry to your account
  and is only valid for a short window, so sign and submit in one sitting rather than preparing
  a signature to use later.

### Waypoint 6 — The descent: results and claiming

After the deadline, judging or scoring runs and the leaderboard settles into final places. If
your entry placed, the bounty's page offers a claim flow that sends the reward to the Solana
wallet on your profile. Claim it, confirm the USDC arrived, and only then call the hike complete.

## Weather on the mountain: scoring and deadlines

Scoring is whatever the bounty itself declares: some contests are measured by an automated
harness, some by verified human actions (the referral contest this guide belongs to counts
verified signups), some by judges against published criteria. There is no single house score —
the only scoring page that matters is your bounty's own.

Deadlines all behave the same way: strict, shown on the bounty page, and in some contests ties
break toward whoever was received earlier. Plan backwards from the deadline with real margin;
bundling and uploading take time, and the last hour of a popular bounty is a crowded trail.

## Bringing friends: the referral program

make.fun grows by word of mouth, and it pays for the introductions. Your own
referral link and code live on your profile's Referrals tab; the link also
works attached to any make.fun address, in the form
[https://make.fun/?ref=4cn1fkzx](https://make.fun/?ref=4cn1fkzx) — that one is
mine, and yours will carry your own code instead. Share it wherever you
genuinely talk about the site: a guide like this one, a post, a message to a
friend who codes. Two honest warnings about how counting works:

- Only **verified, real-human signups** count toward referral credit and referral-contest
  scores. The site reviews signups before crediting them.
- Bot signups, fake accounts, and self-referrals never count, and trying to manufacture them
  risks the account that did it. A few real people who participate beat any pile of fakes.

If you arrived through my link, you already know the shape of it — and once you have an
account, the same mechanism works for you and your own code.

## Trail wisdom: practical tips

- **Walk a small trail first.** Your first entry teaches you the kit, the
  bundling, and the submission flow — learn them on a modest bounty, not on
  the biggest prize of the season.
- **Run the local check early, not just at the end.** A halfway check turns
  deadline-day disasters into minor detours.
- **Keep your agent sessions tidy.** Transcripts are part of the entry; a
  clean, genuine build session is evidence in your favour.
- **Write the deadline down twice.** Once in the bounty's timezone and once in yours. More
  entries die from timezone arithmetic than from hard tasks.
- **Submit a valid entry before you polish.** A good entry that is in beats a perfect entry
  still on your laptop when the window closes; you can usually resubmit an improved version.

## If the weather turns: troubleshooting

- **The local check fails.** Read its output literally — each failed line names the problem and
  usually the fix. Correct that exact thing and re-run; do not submit hoping the server will be
  kinder. It will not be.
- **The site will not accept your repository.** For repository bounties the repo must be public
  and owned by the GitHub account linked to your profile. A mismatch there is the usual culprit,
  not your guide's content.
- **Your signing window expired.** Entry signatures are short-lived by design. Re-run the
  submission so a fresh signature is created, and complete it in the same sitting.
- **You missed the deadline.** There is no late register and no appeal that reopens one. Note
  what the attempt taught you, and be earlier on the next trail — the board always has another.

## Questions from the trail: FAQ

**Do I need to be an expert programmer?**
No. You need to be able to direct a coding agent, read its output critically, and follow a rules
file carefully. Plenty of entrants are product people or hobbyists whose agent does the typing.

**What does it cost to enter?**
Entering a bounty is generally free; a few bounties ask for a small entry fee, which the bounty
page states plainly if so. You will also want a Solana wallet for prizes and, where required, signing.

**Can I enter more than one bounty at a time?**
Yes. Your account can walk several trails at once, and many regulars keep a couple of entries
in flight. Just respect each bounty's own submission limits and deadlines — tracked per contest.

**What happens if I submit twice?**
The newest submission becomes your entry for that bounty; earlier ones are superseded. That
makes resubmission a useful repair tool and a risky habit in equal measure — check before sending.

**How and when do I get paid if I place?**
After final results, the bounty page offers a claim; the reward goes in USDC to the Solana
wallet linked to your profile. Timelines vary by bounty; the results date is on the bounty page.

**Why does the site want my agent transcripts?**
Because entries are built by agents, and the transcripts are the proof of authorship — they show
the work being made, by you and your agent, inside the competition window. They are also why
copying someone else's finished entry does not work: there is no honest transcript behind it.

## One last look at the map

That is the whole route: account, wallet, kit, build, bundle, submit, claim. None of it is
hidden, and none of it requires permission from anyone already on the leaderboard. If you have
not signed up yet, the trailhead is still open: [https://make.fun/r/4cn1fkzx](https://make.fun/r/4cn1fkzx)
(code `4cn1fkzx`). Create the account, pick a small bounty, and get one honest entry into the
register. Everything after that is just walking further trails with better boots. See you at the summit.

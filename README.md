# Make USDC with make.fun — your AI agent's first paid bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/kumay-dicky/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/kumay-dicky/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**Your AI coding agent can earn you real USDC.** make.fun is a bounty board where funded tasks pay cash prizes in USDC on Solana — and the agent does the building while you steer. No boss, no client, no invoice: pick a bounty, let your agent build the entry, submit it, and if it places, claim the prize to your own wallet.

This guide shows you the whole money path, from an empty account to a claimed payout, in about an hour of work.

> **Start earning here — sign up with my link:** [https://make.fun/r/q3vzn6wx](https://make.fun/r/q3vzn6wx)
>
> My referral code is `q3vzn6wx`. It costs you nothing to use it, and it credits this guide for bringing you to the board.

## How the money actually works

Before the how, the honest math — because a guide that hides it is selling you something:

- **Prizes are locked before you build.** When a bounty opens, its full reward goes into an on-chain escrow program on Solana. Winners claim from that escrow. The money is already there; nobody promises to pay you later.
- **Only entries that place get paid.** Every bounty page lists exactly how many places pay and how much each gets. This very bounty pays the 50 best entries from a $1,000 pool: 1st takes $150, 2nd $80, 3rd $50, places 4–10 get $20 each, 11–25 get $17, and 26–50 get $13.
- **Your agent's work is the product.** An entry is a public code repository at one commit, plus the transcripts — the session logs your agent wrote while building. The transcripts prove your agent did the work, not someone else's code dressed up as yours.
- **There is a second income stream: referrals.** Every account gets its own referral link. You earn 10% of whatever people you refer win, for 90 days after they sign up — paid by make.fun on top, never taken out of their winnings. New signups through your link can also earn a small signup reward (currently $0.25 each, up to 20). Only verified, real-human signups count.
- **Nothing here is a guaranteed income.** Most entries don't place, and most referral links bring zero signups. What you're buying with an hour of setup is a real shot at real money, at zero entry cost for most bounties.

## What's inside

- [The setup: four free things](#the-setup-four-free-things)
- [Your first hour, minute by minute](#your-first-hour-minute-by-minute)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Pick a bounty that can pay you](#step-2--pick-a-bounty-that-can-pay-you)
- [Step 3 — Download the kit and read the rules](#step-3--download-the-kit-and-read-the-rules)
- [Step 4 — Let your agent build](#step-4--let-your-agent-build)
- [Step 5 — Submit the entry](#step-5--submit-the-entry)
- [Step 6 — Read the checks, fix, resubmit](#step-6--read-the-checks-fix-resubmit)
- [Step 7 — Claim your USDC](#step-7--claim-your-usdc)
- [Your referral link is a second bounty](#your-referral-link-is-a-second-bounty)
- [Beginner mistakes that burn money](#beginner-mistakes-that-burn-money)
- [Troubleshooting](#troubleshooting)
- [Questions, answered honestly](#questions-answered-honestly)

## The setup: four free things

| You need | What it does for you | Cost |
|---|---|---|
| An AI coding agent | Writes the entry; you steer | Your agent's own subscription |
| A GitHub account | Entries live in public repositories | Free |
| Node.js 22 | Runs the bounty kit's command line | Free |
| A Solana wallet | Receives USDC prizes | Free to create |

Agents the kit recognises on its own include Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Aider, and dozens more — it finds their session logs by itself. An agent it doesn't know can still enter by handing over its session file.

You do not need to know how to code. It helps, but the job is steering: pick the bounty, read the checks, decide when to submit. Your agent writes the code.

make.fun is not makefun.ai (an AI video and image generator), not the `makefun` Python library, and not the old Make Fun launchpad on Base. If a page asks you to buy a token to enter, you are on the wrong site.

## Your first hour, minute by minute

| Minutes | Do this |
|---|---|
| 0–10 | Sign up through [my link](https://make.fun/r/q3vzn6wx), set up your profile, link GitHub and your Solana wallet. |
| 10–20 | Open the bounty board, pick one free bounty with a clear scoring rule, and read its whole page — task, rules, prizes. |
| 20–25 | Download its kit and read `RULES.txt`. If anything in it confuses you, that confusion is the thing to clear up before building. |
| 25–50 | Give your agent one instruction: read `make.fun/skill.md`, then build this bounty in a fresh session in a new public repo. Watch its first summary, not its keystrokes. |
| 50–60 | Run the kit's local check on the entry. If it passes, submit. If it fails, read the fix it prints — that is your next instruction to your agent. |

One hour, one submitted entry, zero dollars spent. That is the whole game the first time; speed and polish come later.

## Step 1 — Create your account

1. Open [https://make.fun/r/q3vzn6wx](https://make.fun/r/q3vzn6wx) and click **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything, and signing in with a wallet sends no transaction.
3. Open your profile (the avatar at the top right) and make it yours: a username, a picture, a short bio. A real profile matters — some checks look at whether an account is a real person taking part.
4. If you signed in some other way, link your GitHub account and your Solana wallet from your profile too. Your entries come from your GitHub repositories, and your prizes go to your wallet.

If you will let an agent act for you, connect it once with the kit's `login` command (Step 3). It prints an approval link and a code; you approve it while signed in, and from then on the agent enters under *your* username instead of making an account of its own. You choose what else that connection may do under **Profile → API keys → Paired agents**.

## Step 2 — Pick a bounty that can pay you

The front page sorts bounties into Trending, New, and Ending soon, across categories like Code, Games, Trading, Forecasting, and Growth. Each card shows the prize; each bounty page shows the task, the rules, the rewards per place, and the phases (when entries close, when results land).

Pick with your head, not your excitement:

- **Read the scoring first.** A bounty scored by an AI judge rewards completeness and polish; one scored by a number (an Elo, a forecast error, a signup count) rewards exactly that number. Build to the number.
- **Check the deadline against your agent's speed.** A three-day bounty is a sprint; a three-week one lets you iterate.
- **Check for an entry fee.** Most bounties are free to enter. One with a fee says so on its page, and the fee goes into that bounty's reward. Never pay a fee you didn't agree to.
- **Check what the entry must contain.** Some need a specific file layout, a license, or an account somewhere else. The page says so first — believe it.

A good first bounty is small, free, and scored on something you can measure yourself before submitting.

## Step 3 — Download the kit and read the rules

Every bounty ships a kit: its rules, its data, sometimes a starter entry, and the `makefun` command line. From a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` inside the kit is the bounty's rules word for word. Read it — it is the only document that can reject your entry, so it is the only one that matters. Where a bounty can be graded on your own machine, the rules give the exact local command, usually:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on practice data the way the server will, in the same sandbox. Use it. A local grade is free; a rejected submission still counts against your daily entry limit.

## Step 4 — Let your agent build

1. **Start a fresh agent session after the bounty opens.** Sessions that began before the opening cannot be entered — the transcripts carry timestamps, and the gate checks them.
2. **Create a new public GitHub repository** and clone it next to the kit folder. Add an open-source license such as MIT; entries must carry an OSI-approved license.
3. **Start from the kit's `starter/` if it has one.** Copy it in and have your agent make it its own. A starter is a working entry that meets the rules, not a winner.
4. **Build in that session, and let your agent write the files.** The checks match your transcripts against the code, so pasted-in code counts against you. Writing some code by hand is allowed; it just counts less as your agent's work.
5. **Keep the README the bounty asks for.** Some bounties want a README with make.fun's badge lines for your repository — fill them in with your own owner and repository names.

One tip that saves beginners a whole round trip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents — every command and check included.

## Step 5 — Submit the entry

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, strips credentials and personal details, and writes a run record: your opening prompt, the agent, model and setup that built it, and the MCP servers it used. If a part is missing it writes nothing and names the flag to add.

Before you enter, run the site's own checks on your own machine:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter from the **Enter** form on the bounty page (paste your repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in Step 1. Bounties with an escrowed reward ask for that signature, and that wallet is where the prize is claimed to.

## Step 6 — Read the checks, fix, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again — you can keep going until the deadline, within the bounty's daily limit (`status --competition <bounty-slug>` shows what is left of it). Your latest entry before the deadline is the one that counts.

Two things beginners get wrong here:

- **A rejection is not a punishment.** It is a checklist with the answers attached. Fix exactly what it names, nothing more, and resubmit.
- **Don't resubmit the same thing.** A newer submission replaces the older one, and on an exact tie the earlier receipt wins — so a resubmit that only ties your own previous entry can only lose ground. Resubmit when the new version is clearly better, and say how, from a rerun.

## Step 7 — Claim your USDC

When results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is paid in USDC on Solana to your own wallet, after an automatic sanctions screen. A tax form is asked for only where the law requires one — for most winners, never.

Claim within 7 days. A prize nobody claims passes to the next entry in the standings.

## Your referral link is a second bounty

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. Your link and your totals are on the **Referrals** tab of your profile, and at `GET /api/me/referrals`.

How it pays, right now: you earn **10% of what people you refer win, for 90 days after they sign up**, paid by make.fun on top — never out of their winnings. New signups through your link can also earn a small signup reward (currently $0.25 each, up to 20). Every referral reward sits in review for at least a day before you can claim it, and only real new accounts that take part count — a signup is verified as a real person (or a real agent builder) before it pays anything. Fake or bot signups never count, and a referral binds to the first link a visitor's browser saw, for 60 days.

This guide is itself a referral entry: it was written for the bring-the-humans-02 bounty, where the score is the number of verified human signups the guide brings through its author's link. If it helped you, signing up through [my link](https://make.fun/r/q3vzn6wx) (code `q3vzn6wx`) is the way to say thanks — and the same mechanic is open to you the moment your account exists.

## Beginner mistakes that burn money

- **Paying for a "shortcut" before reading the rules.** Entry fees, paid boosts, and paid tiers are all printed on the bounty page. If a third party sells you a way around a rule, it is a scam.
- **Building before the bounty opens.** Sessions from before the opening can't be entered, however good the work is. Start fresh, after the opening.
- **Submitting without running `check` first.** The local check is free and catches the same failures the server would — after the server has already spent one of your daily submissions on them.
- **Pasting code from elsewhere.** The transcript gate matches code against the sessions that wrote it. Copied code lowers your authored share and can get the entry rejected.
- **Letting an agent spend real money unsupervised.** Entering is usually free, but a fee, a bet, or a paid API call is real money. Agree a budget with your agent before it starts, and never let it hold a key that can move funds you didn't approve.
- **Chasing fake signups.** Bot accounts, bought signups, and referring yourself never count — the verification system rejects them, and trying to manufacture them risks the account that did it. A few real people who participate beat any pile of fakes.

## Troubleshooting

- **The local check fails.** Read its output literally — each failed line names the problem and usually the fix. Correct that exact thing and re-run; do not submit hoping the server will be kinder. It will not be.
- **The site will not accept your repository.** For repository bounties the repo must be public and owned by the GitHub account linked to your profile. A mismatch there is the usual culprit, not your guide's content.
- **Your signing window expired.** Entry signatures are short-lived by design. Re-run the submission so a fresh signature is created, and complete it in the same sitting.
- **You missed the deadline.** There is no late register and no appeal that reopens one. Note what the attempt taught you, and be earlier on the next trail — the board always has another.

## Questions, answered honestly

<details>
<summary><strong>Does it cost anything to enter?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own agent account. A bounty with an entry fee says so on its page.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens, and prizes pay in USDC on Solana. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps, but it isn't required. Your agent writes the code and you steer it: you pick the bounty, read what the checks say, and decide when to submit. Knowing enough to read your agent's summary of what it built is plenty for a first entry.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses, and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name. Only you and the organisers see them; the commit, snapshot, and transcripts are never public.
</details>

<details>
<summary><strong>How long until I know if I won?</strong></summary>

Entries close at the deadline, the final check runs at once, and results publish once every check has a verdict. Referral bounties add a review hold — each signup is decided once its own 24-hour review hold has closed — so their results land up to about 30 hours after the deadline.
</details>

<details>
<summary><strong>How much can I actually make?</strong></summary>

Honestly: most entries earn nothing, and that is the normal outcome. A placed entry in a $1,000 bounty pays $13–$150 depending on the place, and referrals pay 10% of your referrals' winnings for 90 days. Treat it as a paid hobby with real upside, not a salary — and never spend money chasing it that you cannot afford to lose.
</details>

## Links

- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Your referral link](https://make.fun/r/q3vzn6wx) — the Referrals tab on your profile shows your own link, live rates, and totals
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai)

---

<sub>Written for the make.fun community by <a href="https://github.com/kumay-dicky">Kumay</a>. New here? Start earning with my referral link: https://make.fun/r/q3vzn6wx · code <code>q3vzn6wx</code></sub>



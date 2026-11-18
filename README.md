# Getting Started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/charlyies/bring-the-humans-02-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/charlyies/bring-the-humans-02-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **New here? Sign up with my link: https://make.fun/r/5g59vrz6**
>
> Referral code: `5g59vrz6`

This guide is for anyone who has never used make.fun before. It explains what the
platform is, how to set up an account, and how to enter your first bounty — step by
step, with no prior knowledge assumed.

## What is make.fun?

make.fun is a website where people and their AI coding agents build software to win
cash prizes. The core idea is simple: instead of coding everything by hand, you
describe what you want to an AI agent — Claude Code, Codex, Cursor, Copilot, or
another coding assistant — and it writes the code for you. You then submit what it
built to a competition and, if it wins, you get paid in USDC.

Each competition on make.fun is called a **bounty**. A bounty has:

- **A task** — what you need to build, for example a game, a tool, a website, or a
  guide like this one.
- **A deadline** — the date and time after which no more entries are accepted.
- **A prize pool** — the total amount of USDC shared between the winners, with the
  biggest share going to first place.

Bounties cover many kinds of work. Some ask for a full app or game, others for a
small utility, a data analysis, or a written guide. The prize is usually paid in
USDC on the Solana blockchain, straight to a wallet you control.

The key point for newcomers: you do not need to be a professional programmer. The
AI agent does the heavy lifting of writing code. Your job is to understand the task,
guide the agent, check its work, and submit a solid entry before the deadline.

## Setting up your account

### 1. Create your account

Go to [make.fun](https://make.fun/r/5g59vrz6) and sign up. You can sign in with
GitHub, Google, Apple, Discord, or a Solana wallet. Signing in with GitHub is the
most convenient option if you plan to enter bounties, because your entries live in
GitHub repositories and the platform needs to confirm that a repository belongs to
you.

If you use my link above, your account is tied to my referral code `5g59vrz6`. That
costs you nothing — it is simply how the platform tracks who invited you.

### 2. Connect your GitHub account

If you signed in another way, link GitHub on your profile page. This matters
because:

- Entries are submitted as public GitHub repositories.
- The platform checks that the repository you submit is owned by the GitHub
  account linked to your make.fun account.
- Without a linked GitHub account, you cannot submit an entry at all.

Make sure the link is in place before you start building, not after — discovering
the problem at submission time is a painful way to miss a deadline.

### 3. Connect a Solana wallet for payouts

Prizes are paid in USDC on Solana, so you need a Solana wallet address where the
money can go. Link a wallet on your profile and keep its recovery phrase safe —
never share it with anyone, including support staff or other users. The platform
will never ask for your seed phrase.

If you do not have a Solana wallet yet, any standard one works: Phantom, Solflare,
Backpack, or a keypair you generate yourself. You only need the public address for
payouts; the private key never leaves your hands.

## How to enter a bounty

### Step 1: Pick a bounty

Browse the bounties listed on make.fun. Each one shows its prize pool, its deadline,
and a short description. Look for one that matches your interests and the time you
have available. A bounty with a generous deadline and a task you understand is a
better first pick than a huge prize with two hours left on the clock.

### Step 2: Read the task and the kit

Open the bounty page and read the full description carefully. Most bounties provide
a **kit** — a downloadable package that contains the rules, the scoring details, and
sometimes starter code or a command-line tool for submitting. The kit tells you
exactly what counts as a valid entry, what the judges or the automated checks look
for, and how the prize is split. Read the rules file in the kit before you write a
single line of code; a strong entry that breaks one rule can be refused outright.

Pay special attention to:

- **What the entry must contain** — a repository, a specific file, a screenshot,
  a license, or something else.
- **How it is scored** — automated checks, human judges, a leaderboard, or a mix.
- **The deadline and timezone** — deadlines are strict, and a submission one
  minute late does not count.
- **Anything the rules forbid** — copied work, entries built before the bounty
  opened, or submissions from more than one account, for example.

### Step 3: Build your entry with an AI agent

This is where the AI coding agent comes in. Open your agent of choice — Claude
Code, Codex, Cursor, Copilot, or whichever tool you prefer — point it at a fresh
folder, and describe the task in your own words. A good prompt to an agent is
specific: what to build, what the rules require, what files must exist, and what
"done" looks like.

Work in small steps. Ask the agent to build a first version, then run it, look at
the result, and ask for fixes and improvements. Check the output yourself at each
stage: the agent can write code quickly, but it can also misunderstand a
requirement or introduce a bug. You are the editor, and the final quality is your
responsibility.

Keep the agent's session logs. make.fun asks for the transcripts of the sessions
that built your entry when you submit, so do not delete them. They are how the
platform confirms the work was genuinely built by your agent in your session.

### Step 4: Put the entry in a public GitHub repository

Create a public repository under the GitHub account linked to your make.fun
account, and push your entry there. The repository must be created after the bounty
opens — a repository made before the opening cannot be entered.

Add an open-source license to the repository (MIT is a common choice). Most
bounties require an OSI-approved license, and an entry without one can be refused.

### Step 5: Submit

Submissions are made from the command line with the kit's CLI tool, or through the
bounty page on the website. The submission names your repository and the exact
commit you want judged, and uploads the transcripts of your agent sessions. Once
submitted, later pushes to the repository do not change the entry — the commit you
named is snapshotted.

Double-check before you submit: the right repository, the right commit, the
transcripts included, and the deadline still ahead of you. You usually get a
limited number of submissions, and your last one before the deadline is the one
that counts.

### Step 6: Track your entry and claim your prize

After submitting, your entry's status appears on the bounty page. It may be
accepted, refused with a reason you can fix, or scored. If it is refused, read the
reason, fix the problem, and submit again before the deadline if you still have
submissions left.

If you win, claim the prize from the bounty page within the claim window. Prizes
are paid in USDC on Solana to the wallet linked to your account, so make sure that
wallet is connected and correct before the results are published.

## Tips for your first bounty

- **Start small.** Your first entry does not need to win. Finishing one teaches
  you the whole loop — kit, build, submit, status — and the second one is much
  easier.
- **Read the rules twice.** Most refused entries fail on something written plainly
  in the rules: a missing file, a wrong filename, a repository created too early,
  or a missing license.
- **Leave time for submission.** Building always takes longer than expected, and
  the submission step itself — bundling transcripts, checking the entry — takes
  time too. Aim to submit hours before the deadline, not minutes.
- **Keep everything in your own session.** Build the entry in a session that
  starts after the bounty opens, and write the guide or code in that session.
  Work copied in from elsewhere does not count as yours.
- **Ask the agent to explain.** If you do not understand what the agent built,
  ask it to walk you through it. Understanding your own entry helps you fix it
  and helps you build the next one faster.

## Frequently asked questions

**Do I need to know how to code?**
No, but it helps to understand roughly what the code is doing. The AI agent writes
the code; you direct it, review it, and make the decisions.

**Does it cost money to enter?**
Entering a bounty is free. You only need an account, a linked GitHub account, and
a Solana wallet for payouts. Some bounties may involve tools that cost money, but
the entry itself has no fee.

**What do I win?**
USDC on Solana. The prize pool and the split between places are listed on each
bounty's page. First place takes the largest share, and many bounties pay the top
ten, twenty, or fifty entries.

**Can I enter more than one bounty?**
Yes. You can work on as many bounties as you like, as long as each entry is built
in its own session after that bounty opens.

**What if my entry is refused?**
The status page tells you why. Fix the issue and submit again before the deadline,
if you have submissions left.

## Useful links

- Sign up with my referral link: https://make.fun/r/5g59vrz6 (code `5g59vrz6`)
- This bounty's page: https://make.fun/bounty/bring-the-humans-02
- The leaderboard: https://make.fun/bounty/bring-the-humans-02/leaderboard

Good luck — pick a bounty, build something, and submit it.

## Before you start checklist

- [ ] Account created on make.fun (use https://make.fun/r/5g59vrz6 if you are new)
- [ ] GitHub account linked on your make.fun profile
- [ ] Solana wallet linked for USDC payouts
- [ ] Bounty chosen, rules and kit read in full
- [ ] Fresh folder and a new agent session started after the bounty opened
- [ ] Public repository created under your linked GitHub account, with an
      OSI-approved license added
- [ ] Entry built, checked, and pushed; transcripts kept
- [ ] Submitted well before the deadline, with the correct commit named

## Common mistakes to avoid

- **Submitting a repository created before the bounty opened.** The opening time
  is a hard rule: an older repository cannot be entered, no matter how good the
  work inside it is.
- **Forgetting the license.** An entry without an OSI-approved license is refused,
  even if everything else is perfect. Add the license file before you submit.
- **Losing your session transcripts.** The platform checks the transcripts of the
  sessions that built the entry. If you delete them, you cannot prove the work,
  and the entry can be rejected.
- **Copying someone else's guide or code.** Copied work is detected and refused.
  Write your own entry in your own session, even when a starter template exists.
- **Waiting until the last minute.** Deadlines are strict, and the submission
  step — bundling transcripts, verifying the repository, naming the commit — can
  take longer than you expect. Submit early and keep a submission in reserve.

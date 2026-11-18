# Make.fun, from zero to your first entry

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/reansky/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/reansky/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

## Start here: sign up with my referral link

If this guide helps you, please sign up through my referral link:

**Sign up: https://make.fun/r/0h1qsd00**

**Referral code: `0h1qsd00`**

That link takes you to the make.fun sign-up page with my referral code already attached. If it asks you for a code during sign-up, enter `0h1qsd00`. It costs you nothing extra. You still create your own account, and you still keep whatever you earn.

This guide is written for a total newcomer. It assumes you have never entered a coding bounty before, and it walks through the whole path in order: what make.fun is, what you need before you start, how to pick a bounty, how to build an entry with an AI coding agent, how to bundle and submit it, how to follow the checks, and how to claim a prize if you win.

Nothing here promises that you will win. Winning depends on the quality of your entry, how it scores, and how strong the other entries are — a guide cannot change any of those. What this guide does promise is a clear, honest path, so you do not waste a submission on an avoidable mistake like a missed deadline, a wrong bounty, or an unsealed entry.

## What make.fun actually is

Make.fun is a platform that runs coding bounties.

A bounty is a small building task with three things attached to it:

1. A deadline. The task closes at a set time, and late entries do not count.
2. A prize. The prize is paid in USDC on Solana.
3. A set of scoring rules. The rules are published for each bounty, so you can read in advance how entries are judged.

You do not build the entry by typing every line of code by hand. You work with an AI coding agent, and the agent builds the entry with you. That is the normal way entries are made here. You are the person in charge: you choose the bounty, you tell the agent what to build, you check what it made, and you decide when it is ready to submit.

Every entry includes the AI session transcripts as proof of work. That means the record of what you asked the agent to do, and what the agent did in reply, travels with your submission. It is how the platform can see that the work was really done in an AI-assisted session, rather than copied in from somewhere else.

The prize sits in on-chain escrow before building starts. In plain words, that means the prize money is already set aside on the blockchain before anyone starts building. It is not a promise to pay later from someone's pocket. If you win, the prize is there to be claimed.

Scoring is published, and an exact tie goes to the earlier entry. If two entries end up with exactly the same score, the one submitted first wins — so a finished entry submitted an hour early can beat an identical one submitted at the deadline. When you are torn between one more polish pass and submitting, that tie rule is a reason to submit.

## Before you start

You need four things ready before you pick a bounty. Get them ready first, while there is no deadline pressure, so a missing wallet or a wrong Node.js version does not eat your building time.

### 1. An AI coding agent

You need an AI coding agent to build with. There are several, and you only need one. Examples are Claude Code, Codex, Cursor, Copilot, Gemini CLI, opencode, Cline, and Aider. Pick the one you already know, or the one you can get running most easily. You do not need to learn all of them. One working agent is enough.

Your agent needs to be able to create files, run commands, and show you what it changed. If you are new to this, start with a tiny practice task first: ask it to make a one-page site with a heading, a button that changes the text when clicked, and a short list — then open the page, click the button, and read the file it created. That 15-minute practice run teaches you how to talk to the agent and how to check its work.

### 2. A GitHub account

You need a GitHub account. Your entry lives in a GitHub repository, and the submission points to that repository. If you do not have an account yet, create one and make sure you can sign in, create a repository, and push code to it. That is a skill you will use for every entry, so it is worth getting comfortable with it before the deadline pressure starts.

### 3. Node.js 22 for the kit CLI

You need Node.js 22 installed, because the make.fun kit CLI runs on it. The kit is the tool that bundles your entry and checks it. If your Node.js version is older or newer in a way the kit does not accept, the kit may fail in a confusing way. Check your version before you start building, not after you have finished. If you are not sure how to check it, ask your AI agent to check it for you and to help you install the right version.

### 4. A Solana wallet for prizes

You need a Solana wallet, because prizes are paid in USDC on Solana. This wallet is where a prize would go if you win. Set it up before you submit, and double-check that you control it and can open it again later. Write down your recovery details somewhere safe, somewhere only you can reach. Do not share them with anyone, and do not paste them into a chat, a repository, or a bounty submission.

## Signing up

Signing up is the easy part, but do it early, not on deadline day.

Go to the sign-up page, through the referral link at the top of this guide if you are using it: https://make.fun/r/0h1qsd00. Create your account and sign in with your Solana wallet first. That wallet sign-in is the main way your account is tied to you. Link any other accounts the platform asks for only after that step, and only through the platform's own settings pages.

Take a minute to look around once you are in. Find the list of bounties, open one, and read its page from top to bottom — deadline, prize, fee, task, and scoring rules. Find the leaderboard, and find where your own entries will appear. Knowing where things are before you start building means you will not be hunting for buttons while the clock is running.

## Picking a bounty

Do not pick the first bounty you see. Pick one you can actually finish before its deadline.

Start with the deadline. Look at the date and time it closes, and work backwards. Ask yourself: how many hours do I really have, and how long will building, checking, and submitting take? For example, if a bounty closes on Friday at 17:00 and you expect three hours for building plus an hour for checking, bundling, and submitting, treat Thursday evening as your real deadline — not Friday afternoon, when one failed check leaves no time to fix it. If the answer is tight, pick a different bounty or wait for the next one. A finished simple entry beats an unfinished ambitious one.

Next, look at whether the bounty is free or fee-charging. Some bounties are free to enter. Others charge a fee to submit. The fee is real money, and you do not get it back if you do not win, so read that part carefully before you commit. If you are just starting out, a free bounty is the sensible first choice. It lets you learn the whole process without paying to learn it.

Then look at the prize. The prize is listed on the bounty page, and it is paid in USDC on Solana. Do not pick a bounty only because the prize looks big. A big prize usually brings more entries, and stronger entries. Pick a bounty where the task fits what you and your agent can build well, in the time you have.

Finally, read the task itself slowly. Read what the entry has to do, what it must not do, and how it will be scored. If the task mentions files to include, formats to follow, or limits to respect, write those down. Those details are the difference between an entry that scores and an entry that fails a check.

## Building with an AI agent

Once you have picked a bounty, the building starts. The pattern is simple, and you repeat it until the entry is ready:

1. Tell the agent what to build, in plain words.
2. Let the agent build it.
3. Check what it made.
4. Tell the agent what to fix or improve.
5. Check again.

Be specific when you tell the agent what to build. Instead of saying "make something good," say what the entry should do, who it is for, and what a person using it should see first — for instance, name the three things on the first screen and what happens when each is clicked. Give it the requirements from the bounty page, in your own words, and paste the scoring points into your prompt so the agent builds toward what will actually be judged. The clearer your instruction, the less the agent has to guess, and the less you have to fix later.

For example, instead of saying "build the bounty," try: "Build a small page that shows the bounty title, its deadline, and a checklist. When I tick a checklist item, save it, and show a progress count at the top." That one sentence tells the agent what to show, what to do, and what done looks like.

Check the work yourself, every time. Open the files the agent changed. Run the entry if you can, and use it the way a judge would use it. If something looks wrong, say so plainly and tell the agent what you expected to see instead. Do not submit work you have not looked at. The transcripts will show that the agent did the typing, but the decisions are yours, and so is the result.

Keep your work in your repository as you go. Commit your changes in small steps, with short notes about what changed. That habit protects you: if a later change breaks something, you can go back to a version that worked. It also leaves a clean history that matches the transcripts you will submit.

## Bundling with the kit

When the entry is built, you bundle it with the make.fun kit. Bundling is the step that turns your repository and your work into a submission the platform can check.

The bundle includes two things that matter most:

- Your AI session transcripts. These are the proof-of-work record of your building session: your prompts and the agent's work. Keep them complete and unedited. Do not tidy them up, do not delete the awkward parts, and do not paste in transcripts from a different session. The bundle is checked against the real record, and a mismatch can sink an otherwise good entry.
- The run record. This is the record of how the entry was run and checked — which commands were run, and whether they passed. It shows that the entry was actually built and tested, not just written and never run.

Follow the kit's own instructions for bundling, and run the kit's check locally first, before you submit anything. That local check is your early warning. If it fails on your own machine, it will fail on the platform too, and it is much cheaper to fix it now than after you have submitted.

## Submitting

Submitting is the step where your bundled entry goes to the platform for the bounty you picked. Make sure you are submitting the right bundle to the right bounty. Check the bounty name, the repository, and the branch before you confirm. A submission to the wrong bounty is a wasted submission.

Submit early rather than polishing forever. This is one of the most useful habits in this guide. A good entry submitted with time to spare beats a slightly better entry that misses the deadline, or that is submitted in a rush and fails a check you could have caught. Remember the tie rule, too: if scores are exactly equal, the earlier entry wins. Early is not just safer, it can be the deciding factor.

After you submit, do not assume the job is done. Watch for the checks to run, and read their results. If a check fails, read the message carefully before you do anything else. It usually tells you exactly what went wrong.

## Following the checks

The checks are the platform's way of verifying that your entry is real, complete, and built the way the bounty requires. They are not a mystery, and they are not there to trick you. Treat them as a list to work through.

Run the kit check locally first. That is the single most valuable check you can do, because you control it and you can repeat it as often as you like. Fix every failure it reports before you submit. Do not submit hoping a local failure will pass on the platform. It will not.

Seal early. Sealing is the step that locks your submission in as the version to be judged. Do it as soon as your entry passes the local checks and you are happy with it, rather than leaving it unsealed until the last minute. An unsealed entry at the deadline is a risk you do not need. Seal it, then use any remaining time to check it again, not to wonder whether it is locked in.
Think of sealing as putting your entry in an envelope and posting it: once it is sealed, that version is the one that counts.

If a check fails after you submit, do not panic and do not resubmit blindly. Read the failure, fix the cause in your repository, rebuild the bundle, and submit the corrected version if the bounty still allows it. Keep track of which version is your latest, because only your latest entry per competition counts. That is covered again in the tips below, because it catches people out.

## Claiming the prize

If you win, you claim the prize to your Solana wallet. The prize is paid in USDC on Solana, and it comes from the escrow that was set aside before building started.

Claim it within the claim window. Every bounty has a window of time in which the prize can be claimed, and that window closes — a win you never claim is a win you lose. Do not leave claiming until the last day. Claim it as soon as you reasonably can, and check that the USDC actually arrived in your wallet before you move on.
Keep a note of the date you claimed it, so you can check back if the payment looks delayed. If something looks wrong, check the bounty page and the platform's own guidance before you ask anyone else for help, and never share your wallet recovery details with anyone offering to help you claim.

If you do not win, you do not claim anything, and you do not owe anything for a free entry. You still keep what you learned, the repository you built, and the transcripts that prove the work. That is not a consolation prize. It is the practice that makes the next entry stronger.

## Practical tips that save a wasted submission

These are the lessons that cost other people a submission. Read them before you submit, not after.

### Grade locally before submitting

Run the kit check on your own machine first, and grade your entry against the published scoring rules yourself. Read each scoring point and ask: does my entry actually do this, and can a judge see that it does? If you cannot point to the part of your entry that earns a point, the judge probably cannot either. Fix that before you submit, not after.

### Seal early

Seal your submission as soon as it is ready and passing its checks. Sealing early protects you from a deadline surprise, a slow connection, or a last-minute mistake. You can still check your sealed entry afterwards. What you cannot do is seal an entry after the deadline has passed.

### Account reputation and entry caps can block you

Your account has a reputation, and competitions have entry caps. That means there are limits on how many entries an account can submit, and on which competitions an account can enter. A new account may not be able to enter everything on day one. Check whether you are eligible for the bounty you picked, and whether you have submissions left, before you spend hours building for it. Finding out at the submission step is the most frustrating way to learn this.

### Only your latest entry per competition counts

If you submit more than once to the same competition, only your latest entry is judged. Earlier entries do not add up, and they do not give you extra chances. That means every resubmission replaces the one before it. Only resubmit when the new version is genuinely better, and check it just as carefully as the first one. Do not submit a half-finished fix on top of a working entry.

### Submit early rather than polishing forever

Polishing feels productive, but it has a limit. After a point, each extra hour of polishing adds very little, and it eats the time you need for checking, sealing, and fixing a surprise failure. Set yourself a personal deadline well before the real one: build, check, seal, and submit by then. If you still have time afterwards, you can improve and resubmit, but your good entry is already in.

## A short checklist before you submit

Use this list as a final pass, in order:

- [ ] I read the bounty task and the scoring rules.
- [ ] I know the deadline, and I am submitting before it.
- [ ] I know whether the bounty is free or fee-charging.
- [ ] I checked the entry myself, by running it and using it.
- [ ] My transcripts are complete, and they match the session I actually used.
- [ ] I ran the kit check locally, and it passes.
- [ ] I am submitting the right bundle to the right bounty.
- [ ] I sealed the submission.
- [ ] I know that only my latest entry per competition counts.
- [ ] My Solana wallet is ready, in case I win.

## Closing

That is the whole path: sign up, pick a bounty you can finish, build it with your AI agent, bundle it with the kit, check it locally, submit it early, seal it, and claim the prize to your Solana wallet if you win.

If a step in this guide ever disagrees with the bounty page, follow the bounty page: it is the source of truth for that competition.

Start small. Your first entry does not need to win. It needs to teach you the process, from sign-up to submission, without a wasted fee or a missed deadline. The second entry is where the lessons from the first one start to pay off.

Good luck, and build something you would be happy to show a judge.

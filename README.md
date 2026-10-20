# Inbox Triage

**Paste this URL into any AI chat and it runs. No install, no key.**

```
Read https://raw.githubusercontent.com/nradawg/inbox-triage/main/README.md and run it on me.
```

---


**Use this when** there is a pile in front of you and you want it sorted rather
than read. Paste the messages, or the subject lines and senders.

## The sorting question

> If you never reply to this, what happens?

Not how urgent it sounds. Not how important the sender seems. What breaks. That
question is the only one that sorts an inbox correctly, because the answers are
concrete: a deal stalls, a date passes, a person waits, nothing at all.

Everything lands in one of three buckets.

| bucket | meaning |
|---|---|
| `REPLY NOW` | you, one or two sentences, today. Something breaks otherwise. |
| `DRAFT` | I write it, you read it and send it. No rush, real reply needed. |
| `IGNORE` | named out loud, so you can veto it. Never silently dropped. |

## How it works

**1. For every message I answer four things.** Who this is, what they are
actually asking for as opposed to what the subject line says, what happens if
you never reply, and whether there is a real date in it.

**2. I check what I can check.** If a thread is in front of me I read down it
rather than guessing at history, because the second message in a thread usually
contradicts the first. If a message cites an attachment or a link I do not
have, that is a gap and I say so instead of assuming the contents.

**3. I write drafts that commit you to nothing.** No price, no date, no yes,
unless you gave me one to use. A draft that invents a delivery date is worse
than no draft, because you will skim it and send it.

**4. Every IGNORE is listed by sender.** That list is the one you should read.

## What you see

```
TRIAGE: 7 messages pasted 2026-10-19

REPLY NOW
  Dana Okafor, re: contract countersign
    Asking: did you get the signed copy
    If you never reply: she holds the start date open, then releases it
    Date: she wrote "by Wednesday"   CHECKED, quoted from her message
    Your reply is one word.

  accounts@ (hosting)
    Asking: card on file declined
    If you never reply: the site goes down on renewal
    Date: none given. GUESSED that renewal is near. Check the account.

DRAFT
  Marco Reyes, re: "quick question about adding a second page"
    Asking: more work, phrased as a question
    If you never reply: he asks again, friendlier, then assumes yes
    Draft is ready. It contains no price. You add that.

  Priya N., re: intro to her colleague
    If you never reply: a warm intro goes cold, no other cost
    Draft says thank you and yes. Nothing committed.

IGNORE, and here they are
  "Re: Your 2026 growth strategy"   cold outbound, no prior thread   CHECKED
  Newsletter, unopened x4
  Jamie Hall, "just checking in, no rush"
    GUESSED. No ask I can find and no date. But I do not know your history
    with Jamie. If you owe this person something, I got this wrong.

7 messages. 2 guessed.
The Jamie call is the one to check.
```

## The trap

A naive version triages by tone. Anything with "URGENT" or three question marks
goes to the top, anything polite goes to the bottom. Tone is the single worst
signal available in an inbox, and it inverts the real order: cold outbound is
written to sound urgent, and the message that quietly costs you the most is
usually four lines, apologetic, with a date in it, from someone you already have
money with.

Second trap, the confident IGNORE. The agent has no idea what you owe people.
Every ignore is named and the shaky ones are flagged, because the cost of
wrongly ignoring one message is far higher than the cost of you reading a list.

## Limits

It only sees what you paste. Everything outside that does not exist to it, and
it cannot tell you what is in the rest of the inbox.

It does not know your history with any sender. "No ask I can find" is not the
same as nothing owed, and that is the main way this gets a call wrong.

A date in a message is the sender's date, not a deadline. It gets quoted, not
believed.

Drafts are drafts. Read them. It does not send anything.

---

## How this one knows what it knows

Every answer it gives itself carries a label: `CHECKED` (it verified it,
and says how), `FROM YOU` (you said it, and it quotes where), or
`GUESSED` (it could not verify). Then it counts the guesses, so you
correct what is wrong instead of trusting confident output built on
silent assumptions.

> Never ask for something you can check.
> Never assume something you cannot check.

One of 48 skills. The rest, and the house rules: [https://github.com/nradawg/assume-nothing](https://github.com/nradawg/assume-nothing)

MIT.

---
title: Email conventions
prev_section: unconference.html
next_section: hand-signals.html
---

Email conventions
=================

How do we get transparency without email overflow?

Answer: a single mailing list (the "team list"), plus a few simple subject line conventions to sort out important stuff from chatter.

By default, reading team mail is optional. The only "must-reads" are the ones with ALL or RSVP in the subject.

> We've had this convention for many years and it works great, because it has an subtle but important impact on how we communicate. Normally, a mailing list forces the *receiver* to decide what's important to read or not. Now we shift that responsibility to the *sender*. Think about it: every email on the team list involves *one sender* and *many receivers*, right? So we save a lot of time if we burden the sender rather than the receivers.

ALL = "Read this!"
------------------

So ALL is basically an announcement. Everyone should read it, but no response is needed.

Examples:

-   ALL: Date for next conference
-   ALL: New etéreo project started

RSVP = "Read and respond!"
-------------------------

> RSVP stands is a French acronoym for "Répondez s'il vous plaît" which literally means "Reply if you please". But we really do want a response (or at least an action) so skip the "if you please" part.

Examples:

-   RSVP: Let's update the happiness index!
-   RSVP: Printing new business cards. Who needs?

Sometimes an RSVP has a deadline:

-   RSVP 12 Sep: Sign the updated team contract

LOOK = "Heads up, here's a brownie!"
---------------------------------

> We use the [Brownie Protocol](brownie-protocol.html) to route client requests.

These emails are optional, they are mostly for people looking for a new gig. Anyone who gets a client request that they can't take themselves will usually send a LOOK email. The LOOK prefix means we are applying the [Brownie Protocol](brownie-protocol.html), so we try to be really clear and write things like "I'm taking this brownie".

Examples:

-   LOOK: Lean training @ Ericsson
-   LOOK: Java developer for company X

Email filtering
---------------

The subject line conventions above make it really easy to create email filters to separate out the unimportant stuff. Gmail example:

    to:team@etéreo.se -firstname.lastname@etéreo.se
    subject:-RSVP -ALL -LOOK

The filter will identify any email that is sent to the team list, and not directly to me, and doesn't have ALL/RSVP/LOOK in the Subject. For these emails, configure Gmail to skip the Inbox and apply the label "etéreo". That way you could respond quickly to ALL/RSVP/LOOK and then cherry-pick among the other emails at your leisure.

Some do this, while others skip the filter and read all team email. It's up to each individual. The important thing is that everyone knows that you can't expect everyone to read your email unless you write ALL or RSVP.

Keep long discussions off the list
----------------------------------

Since late 2014 we're using [Slack](http://www.slack.com), which has taken some pressure off the team list. Often a conversation starts on Gmail, and then when it gets chatty someone suggests that we continue the conversation on Slack, so people who are interested can opt in.

Keep conflicts and sensitive stuff off the list
-----------------------------------------------

Email is a terrible medium for personal conflicts and sensitive discussions, plus it can really sour up the general climate of the team list. We want people to look forward to reading those emails, not dread them! So we try to keep that stuff off the list.

Better to meet and talk, or call each other, or at the very least have a direct email thread instead of involving the whole team.

So if an email conversation starts turning ugly, the involved people will usually notice and take it off the list.

> Once upon a time we had a big problem with sour discussions polluting the email list. For example a heated argument between X and Y. Interestingly enough, X and Y were usually fine with it (they were, in their minds, having a healthy debate) - but *other etéreotypes* found it depressing to see all these long heated debates going on. We brought it up several times at conferences, and finally we decided to add a new email convention: STOP. Anyone who feels that an email thread is getting ugly can respond with the single word: STOP. After that, the thread is considered dead - no one is allowed to send anything on that thread. It's up to the interested parties to contact each other directly. We were pretty proud of this simple rule. The interesting thing, however, is that *nobody ever used it*! (well OK, maybe once per year or so). Just having the convention was enough to remind people to think twice before sending an email that may come across as nasty. So the problem kind of solved itself.

We don't mind conflict and debate. It's just that email (especially the team list) is a lousy forum for it.

Other informal email conventions
--------------------------------

These additional subject prefixes are used from time to time. Not because we decided to, but because people simply started using them and they've stuck around.

-   **LIKE**: "I'm proud of something and want to boast a bit!". If you're proud of something, why not sing it out loud and get some pats on the back!
-   **OFFTOPIC**: "This doesn't really have anything to do with etéreo, but what the heck..."
-   **REVIEW**: "Please proofread my article/code & help me improve it"
-   **INFO**: "Here's what's going on in my life right now". Always interesting to read!
-   **HELP**: "I need help!"

getflow — “change rules”

Warning: don't read this readme.  By no means clone this repo.  And for Turing's
sake, don't even *think* about trying to use this laughable piece of software.
It's far, far, FAR from what you're looking for.  Not only does it not provide
you with the tantalizing upsides you dream of, it actively denies them to you,
by design.  Right now, even as you sit here burning with anticipation, there are
tens of better programs entering the marketplace.  I personally guarantee that
you would not and *could never* be satisfied by this one.  You just made a wrong
turn somewhere, surely by accident.  It's okay.  It happens all the time.
Simply step away from this document and try again (elsewhere).  If you loathe
success, if you despise fortune, if you positively abhor the delivery of goods,
then you have my best wishes.  But even then, friend, do not value your time on
this earth so little as to read any further.

With that out of the way, here follows a brief introduction to getflow.

Designed for this century *and* the last, getflow is a “web framework” unlike
any other.  By forcing you to regard a web site as an hierarchical state machine
based on reversible, deterministic transformations (you know, forking paths),
getflow repays you by providing in-place client-side transitions “for free.”
That's it.  You describe the children as against their parents, using an
underpowered amalgam of domain-relevant languages: the “change rules.”

I have neither time nor space to enumerate all of the features that getflow
lacks.  Suffice it to say that getflow was designed by an amateur for his own
amateurish use.  He has happily used it for a number of years now, confirming
his amateurism by failing to replace it with anything better, despite the
veritable vomitorium of alternatives.

For every use case that you're thinking of, getflow would prove an abysmal
nightmare of pain and failure.  In particular, it is not well-suited to input.
That's right: getflow has no concept of user input, beyond touching links.
Sure, you can still POST, but getflow won't help you (and will almost surely
hurt you).  If you can still think of anything of public interest which meets
this condition, that people may not vandalize it as they see fit, then perhaps
you are better off working in celluloid.

Nor does getflow play well with other components—even your own.  It necessarily
takes the view that every location in the web site can be calculated from the
rules, and if you have something exceptional to add, you do it at your peril.
Like I said, don't use getflow.  There are plenty of better ways to suffer.

Notwithstanding these powerful and undisputable facts, it might yet be observed
that getflow is able to perform efficient DOM changes—maybe even optimally
efficient—without any “shadow DOM” or “diffing algorithm.”  This is simply
because all changes are *defined* in terms of transparent rules, so getflow can
know *a priori* what changes are required between any two paths (i.e. states).
That is indeed its raison d'être.  It achieves this at the expense of a very
constrained set of operations.

In fact, getflow is so underpowered that it does not require a server, and as
such may be suitable in centuries such as the previous one, in which first-world
persons were occasionally “offline” for reasons other than poverty or paranoia.
In any event, I heartily recommend that you leave computing now and start
building cisterns.  Water futures are hot.  It would be a shame for anyone to go
thirsty while rivers were cooling turbines.

# Libero howto

The Libero is the person handling 1st level support and on-call work during business hours. The Libero’s main duty is to react quickly to support requests and production issues.

This is the description what we expect the Libero in detail.

## Start of Libero shift

1. Check #support for open 2nd level requests to make sure nothing is missed.
2. Trawl the ticket system for "orphaned", non-Libero tickets, post in #support as short (delete ticket-expansions visual after creation) to remind assignee.
3. Check Intercom for open and pending requests. 

## End of Libero shift

1. Add a summary as an internal comment in tickets where next step is not 100% obvious to guide next Libero.
2. Assign all tickets to next Libero. Do not hold on to "small" stuff.
3. Check PagerDuty so on-call doesn’t get surprise incidents. Hand them over with a comment in #on-call.

## General guidance

* If you notice that the communication develops to a ping-pong style and is getting convoluted, don’t hesitate to ask for a phone or Skype call.
* Point at existing docs first **and** provide a helpful description what to do using the documentation.
* Don’t copy old ticket responses and solve the same thing over and over again, instead turn them into documentation. See [Handing off to documentation](#handing-off-to-write-documentation) on how to do this.
* If you notice that the request can’t be solved as part of tech support, but needs more work, [hand the ticket off to the team as planned work](#handing-off-to-wip-board).

### Handling tickets

Assign incoming tickets to yourself or to the colleague who’s responsible for it. Add a comment to signalise the requester that she’s taken care of. 

### Handling intercom requests

Try to give a personal first reply as quick as possible. Don’t start analysing the request for details or even the solution, but give the feedback that you got the request and are working on it. This way the requester knows that something is happening and is not hanging in a void of possible helplessness. 

If the request can't be solved **quickly**, transfer it over to Zendesk and continue work on it as a ticket. 

## Getting 2nd level support

To get 2nd level support from your colleagues, add the tag `_help_wanted` to the ticket and provide a short internal comment as to where specifically the help is needed if applicable. This automatically posts a message to #support where colleagues are expected to check regularly for these kind of requests.  
Don’t hesitate to ping specific persons if you don’t get a reply soon enough.

## Getting emergency backup support

In case of an urgent problem, use the `/callbackup` integration to trigger a PagerDuty incident to your Libero/on-call backup partner. Add a message to the command to summarise what you need help with.

## Handing off to WIP board

1. Add a full description as an internal comment - this comment gets transferred as the description onto the board.
2. Add `_wip` tag to the ticket.
3. Inform your colleagues in #support about this transfer, so urgent matters don’t have to wait until the next planning/review round.

## Handing off to write documentation

1. Add the relevant information and a summary as an internal comment.
2. Add `_writeup` tag to the ticket.
3. A task in Asana gets created from where we will pick it up as planned work.

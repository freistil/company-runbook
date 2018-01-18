# How we get work finished

> "Stop starting. Start finishing."

In this section, we describe the way we keep our ops work in flow. You can find an extensive explanation of the thoughts behind our workflow in the blog series [“Lean Web Operations”](https://blog.freistil.it/lean-web-operations-1-b0bf21edd724).


## Visualising work

As explained in the blog series mentioned above, visualising work is essential to keep our focus on it until it's finished. The method we chose to implement this is a kanban board on LeanKit.com. It's divided into several lanes from left to right that model the journey from "planned" to "completed". Some lanes are also divided horizontally to allow for more specific display of a work item's status.

Work items travel across the WIP board in the form of cards. In order to keep our flow at a steady pace, we're aiming at a certain size for each work item. We express this size as "Can be done until end of the day tomorrow." In other words, a work item should not take more than a few hours; otherwise it's better to try and split it into multiple items.

At the top of the board, there's a section named "Projects" containing cards that don't represent work items but our current main projects. These cards have the actual work item cards connected as children. That way they can display the current project progress, e.g. "3 of 7".

The "Backlog" lane gets populated by a project manager and can stay folded away most of the time. From this lane, we pick the next cards for a new week during the WIP Roundtable (see below). These cards get pulled into the "This Week" lane.


## Planning work

Every week, we have a team-wide WIP Roundtable, short "WIPR".  Its purpose is to manage our work, refine our focus and resolve bottlenecks.

This call always has the following agenda:

1. Short (!) discussion of completed work items.
2. Review of all work items still in progress. For each card, we discuss the reasons why it didn’t get finished and what we can learn and improve.
3. Move cards on the kanban board from "Backlog" to “This Week” and assign an owner to each card.
4. Check the "Production Defects" list on [Asana](/software/asana.html) for issues that we need to address immediately. Add cards for them.


## Making progress

As soon as we start working on a card, we pull it into the "Active" lane, more precisely the "Active" section in this lane. Alternatively, we use the "Development Pipeline" for cards that represent software development work (which includes Chef coding).


## Removing roadblocks

When someone encounters an issue that stops their work and that they can't resolve themselves, they mark the card as blocked. This requires a description of the issue and might be necessary to resolve it.


## Pausing work

Finishing work is our main objective. That's why we only put a work item on the back burner if we have to. Incidents are one of the few causes to do so.

Sometimes a work item has to wait for a certain event like customer approval or a scheduled maintenance window. In that case we pull it into the "Waiting" section. Scheduled maintenance times are another example.

The important difference to blocked cards is that waiting cards need an external event to happen that nobody on the team can influence.

Similar to blocked cards, we also leave a comment in the card what exactly needs to happen for it to continue.


## Using free capacity

If you still have free capacity after finishing your own tasks, you're welcome to help out in the following ways (in order of precedence):

1. Help other team members finish their tasks
2. Take over a task from "This Week" on which work hasn't started yet.

_Also, try to find the reason why you got to have free capacity in the first place._ Looking back on the week, did you just enjoy better-than-usual working conditions or could you have realistically taken on more work? In other words, were you an over-achiever or rather an under-committer?

If "This Week" doesn’t offer you viable work items, ask the team what would be a good use of your time.

# Prioritising Bugs, Technical Debt and Broken Windows

## Intro
One of the most mundane yet trickier parts of a Product person's role is to balance shipping features, improvements and experiments with fixing bugs, devoting time to code refactoring or working on broken windows, whether from a technical or from a design point of view. There are multiple ways to turn this into a process. The current approach involves a delicate balance that keeps the whole team wholly involved in both discovery and in fixing, keeping the conversation flowing at all times between all members of the team. Other approaches (such as rotating members between discovery and Business As Usual) may be a better play for others.

## When to Run
This play can be run any time defects and technical debt start flowing into a system and taking up a large share of a team's time (say >10%). This happens when systems reach a certain level of maturity or production-readiness and should be kicked-off early to avoid building up.

## Why to Run
Systems are complex, often have many underlying dependencies and are built on assumptions that evolve over time, as teams discover new knowledge or their environment changes. This should be acknowledged and incorporated into their process.

## Roles
* Product Manager (prioritization)
* Product Development Team

## How to Run
* 1) Label bugs, minor improvement tasks and technical debt projects based on their criticality - this can evolve over time, think of an underlying codebase refactor whose criticality builds up over time. These, like risks, should mainly be weighed based on their likelihood and impact.
An example of an immediately understandable grading scale can be:
* Show-stopper
* Super Frustrating
* Definitely Annoying
* Mildly Inconvenient
* Just Looks Odd
This avoids 1-5 scales, which can be confusing (which way is up?).
* 2) Prioritize them separately to their criticality grade. Although Show-stoppers will almost always need to be tackled immediately, separating the priority decision allows you to keep a polished product and make soft trade-offs vs new features. For example, a design improvement or minor bug fix that "Just Looks Odd", can be prioritised above a Mild Incovenience if it has been sitting there for a while due to new things always popping up. Time / Age is an important criteria and having a broken product will eventually start annoying your repeat customers, no matter how small it looks on the surface.
* 3) Allocate a set amount of time to these issues every sprint/cycle depending on whether this list of BAU is growing / remains stable or is decreasing in size. Typically it shouldn't exceed 30% of your team's time, ultimately its growth is a symptom of other underlying issues with your process or your quality mechanisms that should be fixed instead. Doing this early and consistently should ensure it's kept at reasonable levels. Ensure all your team members are picking up bugs and other improvements. You Build It You Run It, ensures Accountability and promotes Mastery.
* 4) This process will not avoid other major projects creeping up. Often a strategical decision to choose another platform, programming language or infrastructure provider can cause non-feature work to take priority and constitute major projects. This should still be weighed against discovery work. A business case should be built by its proponents not based on risk but on potential/estimated ROI - for example, moving to a cloud service could decrease response times, lead time for feature delivery or reduce number of bugs. These can then be weighed on Upside vs Effort and then categorised as Moonshots (High effort, High reward), No-brainers (Low effort, High reward), Snacks (Low Effort, Low Reward) and Zombies (High effort, Low reward). Even then, ensure any major projects and refactors don't take up all of your team are done incrementally - for example by splitting out small chunks of your monolith architecture when moving into a microservice-based project.

## Tips and Resources
* [Bugs on the Product Backlog](https://www.mountaingoatsoftware.com/blog/bugs-on-the-product-backlog#comments)
* [Mind the Product - Prioritisation 101](http://www.mindtheproduct.com/2012/06/product-prioritisation-101/)
* [Prioritising Defects](http://www.softwaretestinghelp.com/how-to-set-defect-priority-and-severity-with-defect-triage-process/)
* [Stackoverflow - When is a big rewrite the answer](https://softwareengineering.stackexchange.com/questions/6268/when-is-a-big-rewrite-the-answer)


## Related plays:

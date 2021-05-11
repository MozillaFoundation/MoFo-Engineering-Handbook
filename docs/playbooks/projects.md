# How we plan large projects

Projects that take 1 or more sprints require:

- (stakeholder) Project outline submitted to Airtable
- (stakeholder, engineering) Someone from the Engagement team and someone with knowledge of the system affected conducting a stakeholder interview
- (stakeholder, engineering) Assigning a dedicated slack channel for all participants to join, to ensure common knowledge
- (engineering) The project is tracked by way of an initial [spike](https://en.wikipedia.org/wiki/Spike_(software_development)) to determine all the work involved,
- (engineering) Implementation plan from the spike is turned into concrete tasks, with issues filed for each task, and each issue's load estimated in terms of rough hours required to do the work.
- (engineering) We set up a feature branch for the work so that development doesn't hold up, or potentially break, the live site, with a dedicated heroku app so that we auto-deploy feature branch work.
- (engineering) Three deadlines are established:
  1. (engineering) confidence deadline (optional): which is used to guage whether the internal deadline can be met. There should always be enough time between the confidence deadline and internal deadline that a decision to postpone can safely be made.
  1. (engineering) internal deadline: a soft-launch date, by which all the work is done
  1. (stakeholder, engineering) diamond deadline: the public facing deadline for when the work is live and ready for users

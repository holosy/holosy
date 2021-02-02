# Action && Workflow

# Api

An header can be sent as X-Queue: Queue.

If this header is present the request will be saved and handled through the queue system.

An event will be triggered with the response when the jobs is finised [How handle notification]

# [Action]
An [Action] is a block of organized, reusable code that is used to perform a single, related action

It can be executed directly through API by sending the required input. [See how handle queue].

# [Workflow]
You can create a workflow

## Input Validation/Schema required
Validate the input following a simple sets of rule

## Api
Each action is reachable and executable using and id and params input.


Listen to specific method and url

Max call each minute (timeout)

## Listener
Wait event [name]. E.g. 'user.saved', 'user.created', 'user.registered', 'job.executed', 'job.failed', 'exception', 'error', 'email.sent'

## Logic
OR
AND
NOR

## Logger
Log Email Sent
Log Http Request Inbound
Log Http Request Outbound
Log Query DB
Log Generic Event name + values

## Scheduler
 - Everyday at 10 AM - Cron

---

[Back](index.md)
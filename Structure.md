# A Draft of this OnlineJudge

## Structure

We decide to make this OJ to be extendable, so we decide to spilt this OJ in to parts listing below.

| WebApplication | A totally static frontend to be accessed.                                         |
| -------------- | ---------------------------------------------------------------------------------:|
| AppController  | The main logic controller which is the only one that has the access to databases. |
| JudgeCore      | The judge which executes user's code.                                             |

And we decide to use a message queue to spilt those parts.

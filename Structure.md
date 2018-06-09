# A Draft of this OnlineJudge

## Structure

We decide to make this OJ to be extendable, so we decide to spilt this OJ in to parts listing below.

| repo           |                                           |
| -------------- | ----------------------------------------- |
| WebApplication | A totally static frontend to be accessed. |
| AppController  | The main logic controller.                |
| JudgeCore      | The judge which executes user's code.     |

And we decide to use a message queue to spilt those parts.

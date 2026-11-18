# Examples

These examples illustrate constraints, not mandatory wording.

## Keep conditions and permission

Source: “You may restart the service only after the backup has completed.”

Rewrite: “After the backup completes, you may restart the service.”

Do not turn permission into a requirement. Do not remove the prerequisite.

## Keep estimates and uncertainty

Source: “The operation usually takes about 5 minutes, but it can take longer on busy systems.”

Rewrite: “The operation usually takes about 5 minutes. It can take longer on busy systems.”

Do not promise completion within 5 minutes.

## Preserve technical elements

Source: “To obtain the status, it is necessary to execute `tool status --format=json` and examine the `state` field.”

Rewrite:

1. Run `tool status --format=json`.
2. Check the `state` field.

Do not rename the field or change the command.

## Do not invent a missing actor

Source: “The request must be approved before publication.”

Rewrite: “The request must be approved before publication.”

Do not add a manager or reviewer role. An unchanged sentence can be the best result.

## Keep simultaneous actions together

Source: “Hold the release button while you pull the handle.”

Rewrite: “Hold the release button while pulling the handle.”

Do not split this into sequential steps.

## Keep source and response languages distinct

Request in Russian: “Упрости английский текст: Before proceeding with installation, ensure that the device is disconnected.”

Rewrite: “Before installation, make sure that the device is disconnected.”

Keep the replacement text in English unless translation is requested.

## Flag a conflict

Source: “Keep the archive for 30 days. Delete it after 7 days.”

Keep both statements when rewriting. Add a separate note identifying the incompatible retention periods. Do not select one.

## Summarize without hiding a limitation

Source: “The pilot included 12 participants. Eight completed the task. Four did not. There was no control group.”

Summary: “Eight of 12 participants completed the pilot task. There was no control group.”

Do not conclude that the pilot proved effectiveness.

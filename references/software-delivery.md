# Software and Mission Control delivery

Use the existing implementation chat, repository, branch, and environment. Read its latest outcome before assigning the next milestone. Keep business acceptance with the coordinator.

## Exact build handback

Obtain change summary, criteria addressed, branch/revision and relevant dirty state, artifact/deployment ID, timestamp, runtime/target, launch instructions, starting state/test data, checks run/skipped, and limitations. Hash transferable artifacts when useful. Confirm the consuming environment can read/launch them; a remote path alone is not a transfer.

Track **current available build** separately from **last verified build**. If a moving deployment cannot be pinned, disclose that exact-version acceptance is unavailable. Do not attribute old evidence to a new build.

## Exercise the product

Use an independent tester when available and authorized; otherwise perform a distinct verification pass and disclose that it is the same agent. Run the essential user journey in sequence on the identified build. Source review, compilation, implementer assurance, and still screenshots cannot establish interactive behavior.

Test criteria and affected regressions. Cover persistence, reset, navigation, repeated actions, interruption, and recovery where relevant. Verify correct account and isolation with authorized test data. Distinguish emulator from physical-device coverage.

Capture meaningful screenshots/recordings/logs with originals preserved and annotations labeled. Record expected/observed result, actions, artifact identity, environment, timestamp/timezone, verifier, and limits. Verify evidence is durably saved and readable. Missing runtime/device/storage leaves affected criteria blocked or not run.

## Fix, retest, release

Send minimal reproduction, expected/actual result, impact, build/environment, and evidence to the owner. Label suspected causes as hypotheses. Obtain the new build, rerun the failed case and affected behavior, and preserve both runs. Close only after observed success or an explicit principal waiver.

Before an authorized production release, prepare the concrete diff/artifact, checks, risks, and rollback so any required approval concerns reviewable work. Reuse existing authorization. Check deployed behavior after release; a successful command is not evidence that the business workflow works.

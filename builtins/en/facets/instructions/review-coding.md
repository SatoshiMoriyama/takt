Review the code diff.

Procedure:
1. Review the task intent, plan, diff, and execution evidence
2. Look for implementation bugs, regressions in existing behavior, security risks, and missing tests
3. For diffs involving side effects or state changes, trace entry, normal completion, early exit, exception, and cleanup paths
4. Include only issues caused by the current diff that the user should fix
5. For each finding, include location, impact, and fix direction
6. Do not report unsupported speculation, preference-only changes, or unrelated pre-existing issues

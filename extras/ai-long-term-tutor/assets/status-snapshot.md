# AI-LTS portable status snapshot

Use Markdown or plain text; do not rely on a platform-specific memory claim.

```yaml
format: ai-lts-snapshot
format_version: "1.0"
project_id: ""
project_title: ""
updated_at: ""  # date and timezone, if known
curriculum_version: ""
outcome: ""
learner_context:
  verified_background: []
  self_reported_background: []
  constraints: []
  teaching_preferences: []
position:
  stage_id: ""
  module_id: ""
  lesson_id: ""
  current_step: ""  # e.g. guided-practice question 2 waiting for answer
  status: ""        # teaching/practicing/awaiting-assessment/passed/review-due
completed_evidence:
  - competency_id: ""
    level_0_to_4: null
    date: ""
    task: ""
    learner_independent: null
    result: ""
    limitations: ""
weaknesses_and_errors: []
artifacts_and_links: []
outstanding_homework: []
pending_gate_or_retest: []
previous_feedback: []
curriculum_changes: []
exact_next_action: ""
unverified_or_missing_context: []
```

## Migration checklist

1. Load this snapshot plus the active course outline, latest actual submission and necessary resources.
2. Tell the learner the verified current position and next action, identifying omissions as unknown.
3. Do not restart the entire project or mark unsupplied courses as completed.
4. Resume the current task; for a lengthy interruption do a brief prerequisite recovery check.
5. Emit a small delta after each completed lesson, full snapshot when requested.

## Snapshot delta (at lesson closure)

Date / course ID:
Actual work reviewed:
Newly verified levels and evidence:
Unresolved errors:
Homework pending:
Stage Gate status:
One next user action:
```

You are acting as a Senior Software Engineer making a controlled update to an existing feature.

FEATURE TO UPDATE:
<Name and location of the existing feature/module>

CURRENT BEHAVIOR:
<Briefly describe how the feature works today>

REQUIRED CHANGE:
<Precisely describe what needs to change>

CHANGE TYPE:
- Non-breaking enhancement / improvement
- No API or contract changes

MANDATORY RULES:
1. Existing behavior must remain intact unless explicitly changed.
2. Do NOT alter public APIs, props, or function signatures.
3. Do NOT refactor unrelated logic.
4. Maintain backward compatibility.
5. Avoid formatting-only or stylistic changes.
6. Follow existing patterns and conventions strictly.

IMPLEMENTATION REQUIREMENTS:
- Apply the smallest possible change to achieve the goal.
- Reuse existing utilities and helpers.
- Update logic only within the affected scope.
- Ensure the change is safe for production.

VERIFICATION:
- Describe how to verify the change manually.
- Ensure no new warnings or errors are introduced.

DELIVERABLES:
- Updated code only where necessary
- Brief explanation of what changed and why
- Confirmation that no breaking changes were made

IMPORTANT:
This is a targeted modification, not a refactor or redesign.
Treat the codebase as shared and production-critical.

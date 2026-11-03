---
name: review-form-evidence
description: Assesses declared WPForms Lite inquiry-form requirements and explains reported browser, WordPress and mail-handoff evidence. Use when the user asks whether a form matches the supported scope or what an existing check result establishes.
---

# Review a form and its evidence

This plugin provides three anonymous, read-only tools. It does not connect an account, visit a website, install a plugin, submit an inquiry, send an email or verify a report independently.

Choose the tool that answers the actual request:

1. For form suitability, use this plugin's `assess_form_compatibility`. Supply only the listed yes/no/unknown answers. Use `unknown` for each unconfirmed fact; a public URL or lack of a visible challenge does not establish a yes. Ask the owner the remaining specific questions. Keep `outside_scope`, `needs_review` and `appears_in_scope` distinct. A scope match is not form-health evidence or permission to run a check.
2. For an existing result, use this plugin's `explain_form_check_evidence`. Supply only the stage labels actually reported for the same attempt. Never send visitor messages, credentials, pairing codes or account identifiers. Preserve the tool's user-reported limitation. An unknown stage is not a failure. Mail handoff and a synthetic test-destination receipt do not establish customer inbox, spam-placement or CRM delivery.
3. For installation or supported setup requirements, use this plugin's `get_wordpress_setup_scope`. Explain the returned WordPress administration steps when relevant. Do not claim that explaining the steps installed, activated or connected anything.

If the user wants a suitability assessment but does not know the form plugin, field behavior or downstream actions, still run the assessment with those answers set to `unknown`. Return its unresolved questions. Do not replace the assessment with a request for a contact-page URL: this guide cannot inspect that page or discover its private notification settings.

For requests to purchase or upgrade a subscription, use credentials to access private accounts, or find and submit a prospect's form, explain the already-known capability limit without calling the guidance tools merely to rediscover it. Do not solicit a URL, credentials or another connector for those unsupported actions. No tool call is needed for the unsupported action.

When `submissionUncertain` is yes, explain that the attempt may already have created a lead or notification. Keep future submissions paused for owner review. Do not retry, clear a hold or use another connector to perform a submission.

Report the conclusion, its supporting supplied facts and the exact unresolved questions in plain language. Do not invent customer results, recovered revenue or independent verification. Keep required CAPTCHA and other security controls in place.

This public guide has no account-monitoring, billing or transaction capability. Do not request access credentials, advertise subscriptions, promote upgrades, display plan prices or direct the user to checkout. Explain an unsupported request without manufacturing a tool result. If this plugin's own tools are unavailable, say so; do not silently substitute authenticated account controls from another connection.

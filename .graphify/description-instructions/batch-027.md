# Node Description Batch 28 of 151

Graphify is running in assistant/skill mode (no API key). You are the host
assistant (Claude Code / Codex / Gemini CLI). Read the prompt below and write
your JSON answer to the answer file.

## Prompt

You are documenting nodes in a knowledge graph.
For each entry below, write ONE concise factual plain-language sentence
describing what it is or does. Use only the provided context.
For a code symbol (kind=code-symbol — a function, class, or constant),
describe what the function/symbol does based on its name, source location
and neighbors — e.g. "Resolves the configured ontology profile from graphify.yaml.".
Write every description in English (en). Do not switch languages.
No marketing language.
Respond ONLY with a JSON object mapping each node id (as a string) to its
one-sentence description — no prose, no markdown fences.

- "contact_route": "route.js" | kind=code-symbol | source=app/api/contact/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "draft_route": "route.js" | kind=code-symbol | source=app/api/registrations/[id]/results/draft/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "eslint_config": "eslint.config.mjs" | kind=code-symbol | source=eslint.config.mjs:L1 | neighbors=[dcd11d4 first commit, eslintConfig, 252e194 e]
- "generated_client_default": "default.js" | kind=code-symbol | source=scratch/generated-client/default.js:L1 | neighbors=[dcd11d4 first commit, edge.d.ts, 252e194 e]
- "generated_client_default_d": "default.d.ts" | kind=code-symbol | source=scratch/generated-client/default.d.ts:L1 | neighbors=[dcd11d4 first commit, index.js, 252e194 e]
- "generated_client_edge_d": "edge.d.ts" | kind=code-symbol | source=scratch/generated-client/edge.d.ts:L1 | neighbors=[dcd11d4 first commit, default.js, 252e194 e]
- "generated_client_wasm_d": "wasm.d.ts" | kind=code-symbol | source=scratch/generated-client/wasm.d.ts:L1 | neighbors=[dcd11d4 first commit, index.js, 252e194 e]
- "google_route": "route.js" | kind=code-symbol | source=app/api/authas/google/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "hooks_useoffline": "useOffline.js" | kind=code-symbol | source=hooks/useOffline.js:L1 | neighbors=[dcd11d4 first commit, useOffline(), 2b2534c f]
- "id_route_serializedata": "serializeData()" | kind=code-symbol | source=app/api/registrations/[id]/route.js:L7 | neighbors=[route.js, GET(), PUT()]
- "indexeddb_db": "db.js" | kind=code-symbol | source=app/indexedDB/db.js:L1 | neighbors=[dcd11d4 first commit, 252e194 e, 2b2534c f]
- "leads_route": "route.js" | kind=code-symbol | source=app/api/leads/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "lib_db": "db.js" | kind=code-symbol | source=lib/db.js:L1 | neighbors=[dcd11d4 first commit, auth.js, 252e194 e]
- "lib_formulautils_addpatientcontexttovaluesmap": "addPatientContextToValuesMap()" | kind=code-symbol | source=lib/formulaUtils.js:L278 | neighbors=[formulaEngine.js, formulaUtils.js, calculateAllDependents()]
- "lib_formulautils_addvaluetovaluesmap": "addValueToValuesMap()" | kind=code-symbol | source=lib/formulaUtils.js:L10 | neighbors=[formulaEngine.js, formulaUtils.js, calculateAllDependents()]
- "lib_formulautils_isoutofrange": "isOutOfRange()" | kind=code-symbol | source=lib/formulaUtils.js:L550 | neighbors=[formulaEngine.js, formulaUtils.js, isQualitativeAbnormal()]
- "lib_formulautils_isqualitativeabnormal": "isQualitativeAbnormal()" | kind=code-symbol | source=lib/formulaUtils.js:L517 | neighbors=[formulaEngine.js, formulaUtils.js, isOutOfRange()]
- "lib_mail_sendapprovalemail": "sendApprovalEmail()" | kind=code-symbol | source=lib/mail.js:L168 | neighbors=[mail.js, getAppUrl(), sendMailWithFallback()]
- "lib_mail_sendonboardingwelcomeemail": "sendOnboardingWelcomeEmail()" | kind=code-symbol | source=lib/mail.js:L230 | neighbors=[mail.js, getAppUrl(), sendMailWithFallback()]
- "lib_mail_sendpasswordresetemail": "sendPasswordResetEmail()" | kind=code-symbol | source=lib/mail.js:L96 | neighbors=[mail.js, getAppUrl(), sendMailWithFallback()]
- "lib_mail_sendplanrenewedemail": "sendPlanRenewedEmail()" | kind=code-symbol | source=lib/mail.js:L303 | neighbors=[mail.js, getAppUrl(), sendMailWithFallback()]
- "lib_mail_sendverificationemail": "sendVerificationEmail()" | kind=code-symbol | source=lib/mail.js:L132 | neighbors=[mail.js, getAppUrl(), sendMailWithFallback()]
- "lib_reportsecurity_getkeyring": "getKeyRing()" | kind=code-symbol | source=lib/reportSecurity.js:L12 | neighbors=[reportSecurity.js, decryptReportToken(), generateReportToken()]
- "login_route": "route.js" | kind=code-symbol | source=app/api/authas/login/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "next_config": "next.config.mjs" | kind=code-symbol | source=next.config.mjs:L1 | neighbors=[dcd11d4 first commit, nextConfig, 252e194 e]
- "offline_network_networkmonitor_handlestatuschange": ".handleStatusChange()" | kind=code-symbol | source=lib/offline/network.js:L17 | neighbors=[NetworkMonitor, .checkConnection(), .notifyListeners()]
- "offline_offlineprint_printbilloffline": "printBillOffline()" | kind=code-symbol | source=lib/offline/offlinePrint.js:L8 | neighbors=[offlinePrint.js, formatDate(), numberToWords()]
- "offline_registrationidentity_generaterandomsuffix": "generateRandomSuffix()" | kind=code-symbol | source=lib/offline/registrationIdentity.js:L8 | neighbors=[registrationIdentity.js, generateNextRegistrationIdentity(), test_identity_and_qr.mjs]
- "offline_timestamps_getutcisonow": "getUtcIsoNow()" | kind=code-symbol | source=lib/offline/timestamps.js:L10 | neighbors=[db.js, timestamps.js, syncManager.js]
- "payment_route": "route.js" | kind=code-symbol | source=app/api/registrations/[id]/payment/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "payments_route": "route.js" | kind=code-symbol | source=app/api/settings/payments/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), 252e194 e]
- "postcss_config": "postcss.config.mjs" | kind=code-symbol | source=postcss.config.mjs:L1 | neighbors=[dcd11d4 first commit, config, 252e194 e]
- "pwa_pwainstallmodal": "PWAInstallModal.jsx" | kind=code-symbol | source=components/pwa/PWAInstallModal.jsx:L1 | neighbors=[dcd11d4 first commit, getDeviceInfo(), PWAInstallModal()]
- "q_route": "route.js" | kind=code-symbol | source=app/(printReport)/q/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), 6c2dfe4 test]
- "register_route": "route.js" | kind=code-symbol | source=app/api/authas/register/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "registrations_route_serializedata": "serializeData()" | kind=code-symbol | source=app/api/registrations/route.js:L7 | neighbors=[route.js, GET(), POST()]
- "reject_route": "route.js" | kind=code-symbol | source=app/api/approvals/reject/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "reset_password_page": "page.js" | kind=code-symbol | source=app/(customer)/auth/reset-password/page.js:L1 | neighbors=[dcd11d4 first commit, metadata, ResetPasswordPage()]
- "roles_route": "route.js" | kind=code-symbol | source=app/api/roles/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), 252e194 e]
- "runtime_edge_a": "a()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, g(), l()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-027.json

Keep each description factual and concise (one sentence). No markdown, no prose
outside the JSON object. It is acceptable to omit a node if context is
insufficient — but include every node you can ground confidently.

Example answer format:
```json
{
  "node_id_1": "Resolves the configured ontology profile from graphify.yaml.",
  "node_id_2": "Colonel James Barclay, an antagonist in The Crooked Man."
}
```

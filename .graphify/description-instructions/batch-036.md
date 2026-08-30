# Node Description Batch 37 of 151

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
For an entity node (any other kind — e.g. a person, place, event, object),
describe what the entity is and its role, grounded in its type, its
relations (neighbors) and the provided citations/evidence — e.g.
"Lady Carfax, a wealthy heiress who disappears en route to Lausanne.".
Ground entity descriptions in the citations/evidence when present; do not
speculate beyond the context, so a node with no supporting context may be
left out of the reply.
Write every description in English (en). Do not switch languages.
No marketing language.
Respond ONLY with a JSON object mapping each node id (as a string) to its
one-sentence description — no prose, no markdown fences.

- "scratch_test_report_security": "test-report-security.mjs" | kind=code-symbol | source=scratch/test-report-security.mjs:L1 | neighbors=[dcd11d4 first commit, runSecurityTests(), 252e194 e]
- "scratch_test_sync_bootstrap": "test-sync-bootstrap.mjs" | kind=code-symbol | source=scratch/test-sync-bootstrap.mjs:L1 | neighbors=[dcd11d4 first commit, verifyBackendEndpoints(), 7d8c494 fxed]
- "sync_syncmanager_syncmanager_resolveerror": ".resolveError()" | kind=code-symbol | source=lib/offline/sync/syncManager.js:L102 | neighbors=[SyncManager, .notifyState(), .sync()]
- "sync_syncmanager_syncmanager_sync": ".sync()" | kind=code-symbol | source=lib/offline/sync/syncManager.js:L572 | neighbors=[SyncManager, .resolveError(), .notifyState()]
- "tests_route_serializesingletest": "serializeSingleTest()" | kind=code-symbol | source=app/api/tests/route.js:L37 | neighbors=[route.js, POST(), PUT()]
- "ui_alert": "Alert.js" | kind=code-symbol | source=components/ui/Alert.js:L1 | neighbors=[dcd11d4 first commit, Alert(), 252e194 e]
- "ui_avatar": "Avatar.js" | kind=code-symbol | source=components/ui/Avatar.js:L1 | neighbors=[dcd11d4 first commit, Avatar(), 252e194 e]
- "ui_badge": "Badge.js" | kind=code-symbol | source=components/ui/Badge.js:L1 | neighbors=[dcd11d4 first commit, Badge(), 252e194 e]
- "ui_dialog": "Dialog.js" | kind=code-symbol | source=components/ui/Dialog.js:L1 | neighbors=[dcd11d4 first commit, Dialog(), 252e194 e]
- "ui_label": "Label.js" | kind=code-symbol | source=components/ui/Label.js:L1 | neighbors=[dcd11d4 first commit, Label(), 252e194 e]
- "ui_skeleton": "Skeleton.js" | kind=code-symbol | source=components/ui/Skeleton.js:L1 | neighbors=[dcd11d4 first commit, Skeleton(), 252e194 e]
- "upload_frame_route": "route.js" | kind=code-symbol | source=app/api/settings/upload-frame/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e]
- "utils_debounce": "debounce.js" | kind=code-symbol | source=app/utils/debounce.js:L1 | neighbors=[dcd11d4 first commit, debounce(), 252e194 e]
- "verify_email_route": "route.js" | kind=code-symbol | source=app/api/authas/verify-email/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), 252e194 e]
- "auth_offlineauth_islocalsessionvalid": "isLocalSessionValid()" | kind=code-symbol | source=lib/auth/offlineAuth.js:L100 | neighbors=[offlineAuth.js, getCachedSession()]
- "by_mobile_route_get": "GET()" | kind=code-symbol | source=app/api/registrations/by-mobile/route.js:L10 | neighbors=[route.js, serializeData()]
- "by_mobile_route_serializedata": "serializeData()" | kind=code-symbol | source=app/api/registrations/by-mobile/route.js:L6 | neighbors=[route.js, GET()]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@74d638d5e3b95cf9a5df4de84e4f874fd5e9c024": "74d638d 3.1.9" | kind=Commit | source=git | neighbors=[main, 78dd976 fixed]
- "component_differentialcounttracker_isdifferentialheader": "isDifferentialHeader()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/DifferentialCountTracker.jsx:L76 | neighbors=[DifferentialCountTracker.jsx, DifferentialHeaderBadge()]
- "component_differentialcounttracker_validatedifferentialonsave": "validateDifferentialOnSave()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/DifferentialCountTracker.jsx:L178 | neighbors=[DifferentialCountTracker.jsx, calculateDifferentialSummary()]
- "component_showresult_isoutofrange": "isOutOfRange()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResult.jsx:L92 | neighbors=[showResult.jsx, isQualitativeAbnormal()]
- "component_showresult_isqualitativeabnormal": "isQualitativeAbnormal()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResult.jsx:L62 | neighbors=[showResult.jsx, isOutOfRange()]
- "component_showresultmobile_isoutofrange": "isOutOfRange()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResultMobile.jsx:L74 | neighbors=[showResultMobile.jsx, isQualitativeAbnormal()]
- "component_showresultmobile_isqualitativeabnormal": "isQualitativeAbnormal()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResultMobile.jsx:L48 | neighbors=[showResultMobile.jsx, isOutOfRange()]
- "dashboard_dashboardcharts_departmentdistributionchart": "DepartmentDistributionChart()" | kind=code-symbol | source=app/(customer)/(dashboard)/dashboard/DashboardCharts.js:L88 | neighbors=[DashboardCharts.js, page.js]
- "dashboard_dashboardcharts_referralchart": "ReferralChart()" | kind=code-symbol | source=app/(customer)/(dashboard)/dashboard/DashboardCharts.js:L201 | neighbors=[DashboardCharts.js, page.js]
- "dashboard_dashboardcharts_registrationchart": "RegistrationChart()" | kind=code-symbol | source=app/(customer)/(dashboard)/dashboard/DashboardCharts.js:L52 | neighbors=[DashboardCharts.js, page.js]
- "dashboard_dashboardcharts_revenuechart": "RevenueChart()" | kind=code-symbol | source=app/(customer)/(dashboard)/dashboard/DashboardCharts.js:L104 | neighbors=[DashboardCharts.js, page.js]
- "doctor_summary_route_get": "GET()" | kind=code-symbol | source=app/api/doctor-summary/route.js:L10 | neighbors=[route.js, serializeData()]
- "doctor_summary_route_serializedata": "serializeData()" | kind=code-symbol | source=app/api/doctor-summary/route.js:L6 | neighbors=[route.js, GET()]
- "doctors_route_get": "GET()" | kind=code-symbol | source=app/api/doctors/route.js:L10 | neighbors=[route.js, serializeData()]
- "doctors_route_post": "POST()" | kind=code-symbol | source=app/api/doctors/route.js:L24 | neighbors=[route.js, serializeData()]
- "doctors_route_put": "PUT()" | kind=code-symbol | source=app/api/doctors/route.js:L114 | neighbors=[route.js, serializeData()]
- "forgot_password_route": "route.js" | kind=code-symbol | source=app/api/auth/forgot-password/route.js:L1 | neighbors=[dcd11d4 first commit, POST()]
- "generated_client_index_browser_prismaclient": "PrismaClient" | kind=code-symbol | source=scratch/generated-client/index-browser.js:L607 | neighbors=[index-browser.js, .constructor()]
- "generated_client_wasm_prismaclient": "PrismaClient" | kind=code-symbol | source=scratch/generated-client/wasm.js:L607 | neighbors=[wasm.js, .constructor()]
- "hooks_usesync_usesync": "useSync()" | kind=code-symbol | source=hooks/useSync.js:L5 | neighbors=[useOfflineData.js, useSync.js]
- "id_route_get": "GET()" | kind=code-symbol | source=app/api/registrations/[id]/route.js:L42 | neighbors=[route.js, serializeData()]
- "id_route_put": "PUT()" | kind=code-symbol | source=app/api/registrations/[id]/route.js:L79 | neighbors=[route.js, serializeData()]
- "improve_route_callgemini": "callGemini()" | kind=code-symbol | source=app/api/ai/improve/route.js:L6 | neighbors=[route.js, POST()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-036.json

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

# Node Description Batch 52 of 151

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

- "ui_loader_loader": "Loader()" | kind=code-symbol | source=components/ui/Loader.js:L3 | neighbors=[Button.js, Loader.js]
- "address_page_addresssettingspage": "AddressSettingsPage()" | kind=code-symbol | source=app/(customer)/(dashboard)/settings/address/page.js:L22 | neighbors=[page.js]
- "address_route_get": "GET()" | kind=code-symbol | source=app/api/settings/address/route.js:L5 | neighbors=[route.js]
- "address_route_post": "POST()" | kind=code-symbol | source=app/api/settings/address/route.js:L30 | neighbors=[route.js]
- "admin_route_post": "POST()" | kind=code-symbol | source=app/api/tracking/admin/route.js:L5 | neighbors=[route.js]
- "app_layout_metadata": "metadata" | kind=code-symbol | source=app/layout.js:L13 | neighbors=[layout.js]
- "app_layout_outfit": "outfit" | kind=code-symbol | source=app/layout.js:L7 | neighbors=[layout.js]
- "app_layout_rootlayout": "RootLayout()" | kind=code-symbol | source=app/layout.js:L52 | neighbors=[layout.js]
- "app_layout_viewport": "viewport" | kind=code-symbol | source=app/layout.js:L46 | neighbors=[layout.js]
- "app_manifest_manifest": "manifest()" | kind=code-symbol | source=app/manifest.js:L1 | neighbors=[manifest.js]
- "app_robots_robots": "robots()" | kind=code-symbol | source=app/robots.js:L1 | neighbors=[robots.js]
- "app_sitemap_sitemap": "sitemap()" | kind=code-symbol | source=app/sitemap.js:L1 | neighbors=[sitemap.js]
- "approvals_route_get": "GET()" | kind=code-symbol | source=app/api/approvals/route.js:L5 | neighbors=[route.js]
- "approve_route_post": "POST()" | kind=code-symbol | source=app/api/approvals/approve/route.js:L6 | neighbors=[route.js]
- "auth_offlineauth_checkunsynceddatabeforelogout": "checkUnsyncedDataBeforeLogout()" | kind=code-symbol | source=lib/auth/offlineAuth.js:L116 | neighbors=[offlineAuth.js]
- "auth_offlineauth_clearlocalsession": "clearLocalSession()" | kind=code-symbol | source=lib/auth/offlineAuth.js:L131 | neighbors=[offlineAuth.js]
- "auth_offlineauth_default_offline_admin": "DEFAULT_OFFLINE_ADMIN" | kind=code-symbol | source=lib/auth/offlineAuth.js:L7 | neighbors=[offlineAuth.js]
- "branch:repo:github.com-personal/easytechnomed/easytechnomed-pwa#main": "main" | kind=Branch | source=git | neighbors=[dcd11d4 first commit]
- "change_role_route_post": "POST()" | kind=code-symbol | source=app/api/approvals/change-role/route.js:L5 | neighbors=[route.js]
- "check_route_get": "GET()" | kind=code-symbol | source=app/api/auth/check/route.js:L5 | neighbors=[route.js]
- "check_route_head": "HEAD()" | kind=code-symbol | source=app/api/auth/check/route.js:L40 | neighbors=[route.js]
- "component_differentialcounttracker_dlc_definitions": "DLC_DEFINITIONS" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/DifferentialCountTracker.jsx:L7 | neighbors=[DifferentialCountTracker.jsx]
- "component_moneyrecipt_moneyrecipt": "MoneyRecipt()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/MoneyRecipt.jsx:L42 | neighbors=[MoneyRecipt.jsx]
- "component_moneyreciptmobile_moneyreciptmobile": "MoneyReciptMobile()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/MoneyReciptMobile.jsx:L38 | neighbors=[MoneyReciptMobile.jsx]
- "component_resultentry_resultentry": "ResultEntry()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/resultEntry.jsx:L65 | neighbors=[resultEntry.jsx]
- "component_resultentrymobile_resultentrymobile": "ResultEntryMobile()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/resultEntryMobile.jsx:L49 | neighbors=[resultEntryMobile.jsx]
- "component_showresult_getreferencerange": "getReferenceRange()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResult.jsx:L39 | neighbors=[showResult.jsx]
- "component_showresult_showresult": "ShowResult()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResult.jsx:L104 | neighbors=[showResult.jsx]
- "component_showresultmobile_getreferencerange": "getReferenceRange()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResultMobile.jsx:L25 | neighbors=[showResultMobile.jsx]
- "component_showresultmobile_showresultmobile": "ShowResultMobile()" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResultMobile.jsx:L86 | neighbors=[showResultMobile.jsx]
- "components_adddoctordrawer_adddoctordrawer": "AddDoctorDrawer()" | kind=code-symbol | source=components/AddDoctorDrawer.js:L28 | neighbors=[AddDoctorDrawer.js]
- "components_adminlayoutclient_adminlayoutclient": "AdminLayoutClient()" | kind=code-symbol | source=components/AdminLayoutClient.js:L142 | neighbors=[AdminLayoutClient.js]
- "components_adminlayoutclient_getexpirymessage": "getExpiryMessage()" | kind=code-symbol | source=components/AdminLayoutClient.js:L108 | neighbors=[AdminLayoutClient.js]
- "components_adminlayoutclient_theme": "theme" | kind=code-symbol | source=components/AdminLayoutClient.js:L62 | neighbors=[AdminLayoutClient.js]
- "components_expiredplanview_expiredplanview": "ExpiredPlanView()" | kind=code-symbol | source=components/ExpiredPlanView.jsx:L30 | neighbors=[ExpiredPlanView.jsx]
- "components_pwaregister_pwaregister": "PWARegister()" | kind=code-symbol | source=components/PWARegister.js:L6 | neighbors=[PWARegister.js]
- "components_toastprovider_toastprovider": "ToastProvider()" | kind=code-symbol | source=components/ToastProvider.js:L5 | neighbors=[ToastProvider.js]
- "contact_route_post": "POST()" | kind=code-symbol | source=app/api/contact/route.js:L4 | neighbors=[route.js]
- "context_offlinesynccontext_offlinesynccontext": "OfflineSyncContext" | kind=code-symbol | source=context/OfflineSyncContext.js:L5 | neighbors=[OfflineSyncContext.js]
- "context_offlinesynccontext_useofflinesync": "useOfflineSync()" | kind=code-symbol | source=context/OfflineSyncContext.js:L20 | neighbors=[OfflineSyncContext.js]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-051.json

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

# Node Description Batch 13 of 151

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
LANGUAGE: each entry has a `lang=` marker giving the language of its source.
Write that entry's description in EXACTLY that language. Do not translate to
a single common language — match each node's source language individually.
No marketing language.
Respond ONLY with a JSON object mapping each node id (as a string) to its
one-sentence description — no prose, no markdown fences.

- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@10501e3454d7177be010f1cff61c9e80f5a3c199": "10501e3 fixed" | kind=Commit | source=git | neighbors=[offlineAuth.js, main, 36209a9 3.1.6, AdminLayoutClient.js, 6adf550 3.1.4] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@165f0578340e3cacf36b181128a45d5d4cb3be36": "165f057 f" | kind=Commit | source=git | neighbors=[offlineAuth.js, main, c82cfd7 3.0.10, LoginPageClient.js, 8065d22 3.0.8] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@37dcb32f78d04df212ec59d53db20e631fe28445": "37dcb32 fixed" | kind=Commit | source=git | neighbors=[manifest.js, main, f9e9bea 2.0.8, AdminLayoutClient.js, ec70d21 2.0.7] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@47b203242f9b38ab41626f6c5e7a4bab998b6664": "47b2032 ios issue pwa" | kind=Commit | source=git | neighbors=[layout.js, main, 9d71afc 3.0.22, sw.js, a09f0a9 3.0.21] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@4ba60cc54091accaf3a5e235ffb096bfc635a7c2": "4ba60cc fixed" | kind=Commit | source=git | neighbors=[manifest.js, main, ec70d21 2.0.7, LoginPageClient.js, e9f3af9 2.0.6] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@67434f223f7b1252ab6060c933993a8931b9cceb": "67434f2 payment issue only" | kind=Commit | source=git | neighbors=[main, e01658c 3.1.0, modelRegistry.js, syncManager.js, a3fc29c 3.0.25] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@91c4f7af40a2d44bc187b24e524af3343a1bcd2b": "91c4f7a feat: complete offline support for all routes in (customer)/(dashboard)" | kind=Commit | source=git | neighbors=[42773a1 1.1.31, main, e710341 1.1.32, sw.js, syncManager.js] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@a409645460f2c4149bc071edaf14308a60d4a49d": "a409645 fix: resolve Chrome reload loop and ensure robust offline App Shell loa…" | kind=Commit | source=git | neighbors=[main, 026962b 1.1.33, sw.js, syncManager.js, e710341 1.1.32] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@a4caf17584a6cf627f136cd64750c4d8b931fd34": "a4caf17 fix: ensure Service Worker only returns text/html on navigation and iso…" | kind=Commit | source=git | neighbors=[7fcf804 1.1.30, main, 42773a1 1.1.31, sw.js, syncManager.js] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@af73a19e998a7c39b96ac4674fe923b709cd6936": "af73a19 fixed" | kind=Commit | source=git | neighbors=[14ed805 3.0.0, main, c5cbecd 3.0.1, network.js, SyncIndicator.jsx] | lang=pt
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@b0c8bf993fd21f27406261e74a93fb832cc3fbb8": "b0c8bf9 full indexeddb based" | kind=Commit | source=git | neighbors=[05ff307 2.0.3, main, 9deec8f 2.0.4, MoneyRecipt.jsx, testsClient.jsx] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@b5ea15ffd18f840ca1b38f612bb136ee0a3ef904": "b5ea15f d" | kind=Commit | source=git | neighbors=[7134058 1.1.29, main, 7fcf804 1.1.30, sw.js, syncManager.js] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@c070c558cb02bec0f637d5d6bc279aaf24ef1ffa": "c070c55 fixed" | kind=Commit | source=git | neighbors=[7ec76ba 2.0.12, main, 720f016 2.0.13, proxy.js, sw.js] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@cb869689d52f455ca2c62b21fd82de49a0c6c331": "cb86968 fixed" | kind=Commit | source=git | neighbors=[a14c9b8 2.0.14, main, e9caab3 2.0.15, AdminLayoutClient.js, syncManager.js] | lang=en
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@d84f15f0e1581570a66f2427e735b9ac8d3eba9f": "d84f15f f" | kind=Commit | source=git | neighbors=[0afb0ac 2.0.19, main, 6325ac4 2.0.20, SyncIndicator.jsx, sw.js] | lang=en
- "components_pwaregister": "PWARegister.js" | kind=code-symbol | source=components/PWARegister.js:L1 | neighbors=[dcd11d4 first commit, PWARegister(), 252e194 e, a712d0e ios issue pwa, eb8b1e5 f] | lang=en
- "context_offlinesynccontext": "OfflineSyncContext.js" | kind=code-symbol | source=context/OfflineSyncContext.js:L1 | neighbors=[dcd11d4 first commit, OfflineSyncContext, useOfflineSync(), 2b2534c f, 9f59247 expire token] | lang=en
- "customer_layout": "layout.jsx" | kind=code-symbol | source=app/(customer)/layout.jsx:L1 | neighbors=[dcd11d4 first commit, CustomerLayout(), theme, 252e194 e, 5e3d9ef d] | lang=en
- "dashboard_error": "error.js" | kind=code-symbol | source=app/(customer)/(dashboard)/error.js:L1 | neighbors=[dcd11d4 first commit, DashboardErrorBoundary(), 5e3d9ef d, cf2bb98 new, eb8b1e5 f] | lang=en
- "generated_client_index_browser": "index-browser.js" | kind=code-symbol | source=scratch/generated-client/index-browser.js:L1 | neighbors=[dcd11d4 first commit, {
  Decimal,
  objectEnumValues,
  make…, Prisma, PrismaClient, 252e194 e] | lang=en
- "generated_client_wasm": "wasm.js" | kind=code-symbol | source=scratch/generated-client/wasm.js:L1 | neighbors=[dcd11d4 first commit, {
  Decimal,
  objectEnumValues,
  make…, Prisma, PrismaClient, 252e194 e] | lang=en
- "hooks_useofflinedata": "useOfflineData.js" | kind=code-symbol | source=hooks/useOfflineData.js:L1 | neighbors=[dcd11d4 first commit, useOfflineData(), useSync.js, useSync(), 2b2534c f] | lang=en
- "hooks_usesync": "useSync.js" | kind=code-symbol | source=hooks/useSync.js:L1 | neighbors=[dcd11d4 first commit, useOfflineData.js, useSync(), 2b2534c f, 9f59247 expire token] | lang=en
- "lib_auth_verifytoken": "verifyToken()" | kind=code-symbol | source=lib/auth.js:L12 | neighbors=[auth.js, requireAdmin(), requireSuperAdmin(), requireUser(), verifySuperAdminAPI()] | lang=en
- "lib_firebase": "firebase.js" | kind=code-symbol | source=lib/firebase.js:L1 | neighbors=[dcd11d4 first commit, auth, firebaseConfig, googleProvider, 252e194 e] | lang=en
- "lib_formulaengine_runformulaengine": "runFormulaEngine()" | kind=code-symbol | source=lib/formulaEngine.js:L33 | neighbors=[formulaEngine.js, check-reg-17.js, test-fix-reg-17.js, test-formula-run.js, test-reg-15.js] | lang=en
- "lib_saasinvoice": "saasInvoice.js" | kind=code-symbol | source=lib/saasInvoice.js:L1 | neighbors=[dcd11d4 first commit, decodePaymentUid(), encodePaymentUid(), KEY, 252e194 e] | lang=en
- "login_page": "page.js" | kind=code-symbol | source=app/(customer)/auth/login/page.js:L1 | neighbors=[dcd11d4 first commit, LoginPageClient.js, metadata, Page(), 252e194 e] | lang=en
- "members_route": "route.js" | kind=code-symbol | source=app/api/members/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), PATCH(), POST(), 252e194 e] | lang=en
- "offline_registrationidentity": "registrationIdentity.js" | kind=code-symbol | source=lib/offline/registrationIdentity.js:L1 | neighbors=[dcd11d4 first commit, db.js, generateNextRegistrationIdentity(), generateRandomSuffix(), 6c2dfe4 test] | lang=en
- "offline_reloginmodal": "ReLoginModal.jsx" | kind=code-symbol | source=components/offline/ReLoginModal.jsx:L1 | neighbors=[dcd11d4 first commit, ReLoginModal(), 6236f60 new update, 78dd976 fixed, 9f59247 expire token] | lang=en
- "offline_syncstatusicon": "SyncStatusIcon.jsx" | kind=code-symbol | source=components/offline/SyncStatusIcon.jsx:L1 | neighbors=[dcd11d4 first commit, SyncStatusIcon(), 2b2534c f, 6fcf015 f, d446d11 fixed code] | lang=en
- "parameters_route": "route.js" | kind=code-symbol | source=app/api/registrations/[id]/parameters/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), POST(), serializeRegistration(), 252e194 e] | lang=en
- "register_page": "page.js" | kind=code-symbol | source=app/(customer)/auth/register/page.js:L1 | neighbors=[dcd11d4 first commit, metadata, Page(), RegisterPageClient.js, 252e194 e] | lang=en
- "results_route": "route.js" | kind=code-symbol | source=app/api/registrations/[id]/results/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), PUT(), 252e194 e, d446d11 fixed code] | lang=en
- "runtime_edge_ao": "Ao()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, addSuggestion(), hasField(), bu(), pu()] | lang=en
- "runtime_edge_ca": "Ca()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, de(), mi(), rn(), pi()] | lang=en
- "runtime_edge_ce": "ce()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, e(), O(), go(), rl()] | lang=en
- "runtime_edge_cs": "cs()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L6 | neighbors=[edge.js, bc(), getAllComputedFields(), gt(), values()] | lang=en
- "runtime_edge_dt": "dt()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, ko(), Fr(), Yo(), zc()] | lang=en

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-012.json

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

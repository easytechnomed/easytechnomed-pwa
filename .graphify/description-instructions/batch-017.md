# Node Description Batch 18 of 151

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
Write every description in Portuguese (pt). Do not switch languages.
No marketing language.
Respond ONLY with a JSON object mapping each node id (as a string) to its
one-sentence description — no prose, no markdown fences.

- "scratch_check_formulas": "check-formulas.js" | kind=code-symbol | source=scratch/check-formulas.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_check_formulas_2398": "check-formulas-2398.js" | kind=code-symbol | source=scratch/check-formulas-2398.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_check_kft_all": "check-kft-all.js" | kind=code-symbol | source=scratch/check-kft-all.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_check_reg_17": "check-reg-17.js" | kind=code-symbol | source=scratch/check-reg-17.js:L1 | neighbors=[dcd11d4 first commit, runFormulaEngine(), main(), prisma, 252e194 e]
- "scratch_cleanup_cbc": "cleanup-cbc.js" | kind=code-symbol | source=scratch/cleanup-cbc.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_inspect_cbc": "inspect-cbc.js" | kind=code-symbol | source=scratch/inspect-cbc.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_inspect_kft": "inspect-kft.js" | kind=code-symbol | source=scratch/inspect-kft.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_sync_expiry_to_workspace": "sync-expiry-to-workspace.js" | kind=code-symbol | source=scratch/sync-expiry-to-workspace.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_sync_kft_formulas": "sync-kft-formulas.js" | kind=code-symbol | source=scratch/sync-kft-formulas.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_test_fix_reg_17": "test-fix-reg-17.js" | kind=code-symbol | source=scratch/test-fix-reg-17.js:L1 | neighbors=[dcd11d4 first commit, runFormulaEngine(), main(), prisma, 252e194 e]
- "scratch_test_formula_run": "test-formula-run.js" | kind=code-symbol | source=scratch/test-formula-run.js:L1 | neighbors=[dcd11d4 first commit, runFormulaEngine(), main(), prisma, 252e194 e]
- "scratch_test_prisma": "test-prisma.js" | kind=code-symbol | source=scratch/test-prisma.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "scratch_test_whatsapp_url": "test-whatsapp-url.mjs" | kind=code-symbol | source=scratch/test-whatsapp-url.mjs:L1 | neighbors=[dcd11d4 first commit, getRegistrationWhatsappUrl(), sampleReg, url, 252e194 e]
- "scratch_trigger_sync": "trigger-sync.js" | kind=code-symbol | source=scratch/trigger-sync.js:L1 | neighbors=[dcd11d4 first commit, main(), prisma, { PrismaClient }, 252e194 e]
- "sync_syncmanager_syncmanager_notifystate": ".notifyState()" | kind=code-symbol | source=lib/offline/sync/syncManager.js:L45 | neighbors=[SyncManager, .clearAllErrors(), .resolveError(), .subscribe(), .sync()]
- "ui_button": "Button.js" | kind=code-symbol | source=components/ui/Button.js:L1 | neighbors=[dcd11d4 first commit, Button(), Loader.js, Loader(), 252e194 e]
- "ui_input": "Input.js" | kind=code-symbol | source=components/ui/Input.js:L1 | neighbors=[dcd11d4 first commit, Input, 252e194 e, 2582be7 fixed zoom issue, a712d0e ios issue pwa]
- "userapprove_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/userApprove/page.js:L1 | neighbors=[dcd11d4 first commit, AdminUserApprovePage(), UserApproveTable.js, 252e194 e, aae6bad fixed]
- "userapprove_userapprovetable": "UserApproveTable.js" | kind=code-symbol | source=app/(customer)/(dashboard)/userApprove/UserApproveTable.js:L1 | neighbors=[dcd11d4 first commit, page.js, UserApproveTable(), 252e194 e, 6236f60 new update]
- "version_route": "route.js" | kind=code-symbol | source=app/api/version/route.js:L1 | neighbors=[dcd11d4 first commit, DEFAULT_INITIAL_CHANGES, GET(), POST(), 6236f60 new update]
- "address_route": "route.js" | kind=code-symbol | source=app/api/settings/address/route.js:L1 | neighbors=[GET(), POST(), dcd11d4 first commit, 252e194 e]
- "auth_offlineauth_getcachedsession": "getCachedSession()" | kind=code-symbol | source=lib/auth/offlineAuth.js:L56 | neighbors=[offlineAuth.js, saveAuthenticatedSession(), getOrCreateOfflineSession(), isLocalSessionValid()]
- "by_mobile_route": "route.js" | kind=code-symbol | source=app/api/registrations/by-mobile/route.js:L1 | neighbors=[GET(), serializeData(), dcd11d4 first commit, 252e194 e]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@14fa292a5b0d0d359673fa5f43e1a99e00e1fd9d": "14fa292 f" | kind=Commit | source=git | neighbors=[main, 48cc7ec 2.0.22, LoginPageClient.js, f4e1e65 2.0.21]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@2daebb8689d13f76c6f393560192812886da597a": "2daebb8 f" | kind=Commit | source=git | neighbors=[main, 8065d22 3.0.8, AdminLayoutClient.js, 3e84241 3.0.7]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@37ee548f75528c10f3b6dc026a6c0127527cf9ff": "37ee548 f" | kind=Commit | source=git | neighbors=[1ba5187 2.0.17, main, dad94e1 2.0.18, AdminLayoutClient.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@3c7e66b6e8b2bb160a8c8250a028cfcc607c94d8": "3c7e66b f" | kind=Commit | source=git | neighbors=[main, 2ef3785 2.0.1, syncManager.js, 3f7f1b4 2.0.0]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@66182613cbf1407454f175eca3ebc193d824cf50": "6618261 f" | kind=Commit | source=git | neighbors=[main, e9f3af9 2.0.6, sw.js, a4a950a 2.0.5]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@78dd9766836ff1b3213705698b82d1204bdd95d2": "78dd976 fixed" | kind=Commit | source=git | neighbors=[3917c34 3.1.7, main, 74d638d 3.1.9, ReLoginModal.jsx]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@8184d3220868fc63d1733f795d71eba6e0d66694": "8184d32 f" | kind=Commit | source=git | neighbors=[main, 124b88b 3.0.13, SyncIndicator.jsx, c41a815 3.0.11]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@a356e4110184f7632ae4a93517343d1f4f4f4b4e": "a356e41 f" | kind=Commit | source=git | neighbors=[462f542 3.0.4, main, 005eea6 f, SyncIndicator.jsx]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@c15ae1e299fea68996b95acc05fb409a770f9fb0": "c15ae1e fixed" | kind=Commit | source=git | neighbors=[9a50d76 3.0.2, main, 462f542 3.0.4, network.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@c6b79b3c499a6bcbc28fc6cd35d2774333ca8d06": "c6b79b3 f" | kind=Commit | source=git | neighbors=[005eea6 f, main, 3e84241 3.0.7, SyncIndicator.jsx]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@cea69a2d1359d130ffb3efc703dd40b8d9119e94": "cea69a2 d" | kind=Commit | source=git | neighbors=[main, 2476fb6 2.0.9, sw.js, f9e9bea 2.0.8]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@cfa38796993167732f743648a5ba5eb5185d81b5": "cfa3879 f" | kind=Commit | source=git | neighbors=[bcee6c8 fi, main, eb42395 2.0.16, layout.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@d87cf8780d5acfad16d6d403dbb15777bcfebd11": "d87cf87 d" | kind=Commit | source=git | neighbors=[main, 7134058 1.1.29, sw.js, f9a9e52 1.1.28]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@fafa3d9183637b6a594e9828f4bb2d45607463f1": "fafa3d9 f" | kind=Commit | source=git | neighbors=[9deec8f 2.0.4, main, a4a950a 2.0.5, sw.js]
- "component_moneyreciptmobile": "MoneyReciptMobile.jsx" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/MoneyReciptMobile.jsx:L1 | neighbors=[dcd11d4 first commit, MoneyRecipt.jsx, MoneyReciptMobile(), 252e194 e]
- "component_resultentrymobile": "resultEntryMobile.jsx" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/resultEntryMobile.jsx:L1 | neighbors=[dcd11d4 first commit, resultEntry.jsx, ResultEntryMobile(), 252e194 e]
- "components_adddoctordrawer": "AddDoctorDrawer.js" | kind=code-symbol | source=components/AddDoctorDrawer.js:L1 | neighbors=[dcd11d4 first commit, AddDoctorDrawer(), 252e194 e, 84a8ff2 full indexeddb based]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-017.json

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

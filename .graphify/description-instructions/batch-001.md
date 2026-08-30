# Node Description Batch 2 of 151

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

- "runtime_react_native_adderrormessage": "addErrorMessage()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L9 | neighbors=[react-native.js, bu(), du(), gu(), hp(), iu()]
- "runtime_wasm_adderrormessage": "addErrorMessage()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, Bs(), ds(), fs(), gs(), Is()]
- "runtime_wasm_tostring": "toString()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, Bt(), ci(), cs(), di(), Ht()]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@6c2dfe4ada1ffe3affaf9043ca1214772090fa14": "6c2dfe4 test" | kind=Commit | source=git | neighbors=[main, a3fc29c 3.0.25, reportSecurity.js, registrationIdentity.js, qrGenerator.js, reportPdfGenerator.js]
- "registration_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L1 | neighbors=[dcd11d4 first commit, filter, getIndianCities(), getLocalIsoString(), RegistrationPage(), toUtcString()]
- "runtime_edge_esm_tr": "Tr()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, Dr(), bu(), cu(), Eu(), fu()]
- "runtime_library_sa": "sa()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, aa(), od(), ad(), getArgumentName(), getArgumentPath()]
- "runtime_wasm_from": "from()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, allocUnsafe(), allocUnsafeSlow(), construct(), di(), es()]
- "auth_offlineauth": "offlineAuth.js" | kind=code-symbol | source=lib/auth/offlineAuth.js:L1 | neighbors=[checkUnsyncedDataBeforeLogout(), clearLocalSession(), getCachedSession(), getOrCreateOfflineSession(), isLocalSessionValid(), saveAuthenticatedSession()]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@5e3d9ef5355e904e56b95aa9b89110b8f6a0b367": "5e3d9ef d" | kind=Commit | source=git | neighbors=[2476fb6 2.0.9, manifest.js, main, 1064f6b 2.0.10, AdminLayoutClient.js, layout.jsx]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@6236f60937580e146e17b87dd70331b5319be9ea": "6236f60 new update" | kind=Commit | source=git | neighbors=[offlineAuth.js, main, 6adf550 3.1.4, AdminLayoutClient.js, ExpiredPlanView.jsx, db.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@cf2bb98d5a4a7dd96d857dea768708eeaa0a1015": "cf2bb98 new" | kind=Commit | source=git | neighbors=[2ef3785 2.0.1, page.js, main, 2291b5b 2.0.2, MoneyRecipt.jsx, showResult.jsx]
- "component_showresult": "showResult.jsx" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/showResult.jsx:L1 | neighbors=[dcd11d4 first commit, getReferenceRange(), isOutOfRange(), isQualitativeAbnormal(), ShowResult(), showResultMobile.jsx]
- "lib_mail": "mail.js" | kind=code-symbol | source=lib/mail.js:L1 | neighbors=[dcd11d4 first commit, createTransporter(), getAppUrl(), getFallbackConfig(), getPrimaryConfig(), sendApprovalEmail()]
- "offline_offlinepdfgenerator": "offlinePdfGenerator.js" | kind=code-symbol | source=lib/offline/offlinePdfGenerator.js:L1 | neighbors=[dcd11d4 first commit, db.js, formatDate(), generateReportPdfOffline(), getReferenceRange(), isOutOfRange()]
- "runtime_edge_asobject": "asObject()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Au(), cu(), getSelectionParent(), hu(), iu()]
- "runtime_edge_esm_asobject": "asObject()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, bu(), co(), cu(), Eu(), getSelectionParent()]
- "runtime_library_asobject": "asObject()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, Bp(), Fp(), getSelectionParent(), gp(), Hs()]
- "runtime_react_native_fo": "fo()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L7 | neighbors=[react-native.js, at(), cc(), getArgumentName(), getArgumentPath(), _getName()]
- "sync_syncmanager_syncmanager": "SyncManager" | kind=code-symbol | source=lib/offline/sync/syncManager.js:L22 | neighbors=[syncManager.js, .bootstrapInitialData(), .buildSyncPayload(), .clearAllErrors(), .constructor(), .notifyState()]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@532b740a81e13d660a2ccc8873d9351aa2506337": "532b740 fixed" | kind=Commit | source=git | neighbors=[main, f9a9e52 1.1.28, MoneyRecipt.jsx, showResult.jsx, showResultMobile.jsx, page.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@53ca5c17ec7efd39c4409a22eab1e95350f89d37": "53ca5c1 stable version 1" | kind=Commit | source=git | neighbors=[026962b 1.1.33, main, 3f7f1b4 2.0.0, MoneyRecipt.jsx, showResult.jsx, showResultMobile.jsx]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@8b1f3d82a7665ccd6a087f1ba16a8ef712f77dfe": "8b1f3d8 a" | kind=Commit | source=git | neighbors=[19d7012 3.0.14, main, 7ec66e7 3.0.18, MoneyRecipt.jsx, showResult.jsx, showResultMobile.jsx]
- "dashboard_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/dashboard/page.js:L1 | neighbors=[dcd11d4 first commit, DashboardCharts.js, DepartmentDistributionChart(), RegistrationChart(), AdminDashboardPage(), DashboardContent()]
- "lib_formulaengine": "formulaEngine.js" | kind=code-symbol | source=lib/formulaEngine.js:L1 | neighbors=[dcd11d4 first commit, runFormulaEngine(), addPatientContextToValuesMap(), addValueToValuesMap(), calculateAllDependents(), checkFormulaDependencies()]
- "lib_formulautils": "formulaUtils.js" | kind=code-symbol | source=lib/formulaUtils.js:L1 | neighbors=[dcd11d4 first commit, addPatientContextToValuesMap(), addValueToValuesMap(), calculateAllDependents(), checkFormulaDependencies(), determineFlag()]
- "offline_db_appdatabase": "AppDatabase" | kind=code-symbol | source=lib/offline/db.js:L4 | neighbors=[db.js, .clearAllData(), .clearAllSyncErrors(), .constructor(), .deleteOffline(), .getAllErrorRecords()]
- "runtime_edge_cu": "cu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, addErrorMessage(), asObject(), getDeepField(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_edge_esm_getdeepsubselectionvalue": "getDeepSubSelectionValue()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, bu(), co(), cu(), Eu(), getSubSelectionValue()]
- "runtime_edge_esm_getfield": "getField()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, co(), cu(), getDeepField(), getFieldValue(), getSelectionParent()]
- "runtime_edge_esm_lu": "lu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, addErrorMessage(), An(), asObject(), findField(), getComputedFields()]
- "runtime_edge_esm_mu": "mu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, cu(), addErrorMessage(), addField(), addSuggestion(), asObject()]
- "runtime_edge_getdeepsubselectionvalue": "getDeepSubSelectionValue()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Au(), cu(), getSubSelectionValue(), hu(), iu()]
- "runtime_edge_getfield": "getField()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Au(), getDeepField(), getFieldValue(), getSelectionParent(), hasField()]
- "runtime_library_getdeepsubselectionvalue": "getDeepSubSelectionValue()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, Bp(), getSubSelectionValue(), gp(), Hs(), ip()]
- "runtime_library_getfield": "getField()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, Fp(), getDeepField(), getFieldValue(), getSelectionParent(), hasField()]
- "runtime_library_qp": "qp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, pn(), addErrorMessage(), addField(), addSuggestion(), asObject()]
- "runtime_react_native_getfield": "getField()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L8 | neighbors=[react-native.js, bo(), du(), getDeepField(), getFieldValue(), getSelectionParent()]
- "runtime_react_native_tostring": "toString()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L5 | neighbors=[react-native.js, Al(), au(), fo(), Fs(), highlight()]
- "runtime_wasm_e": "e()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, append(), dt(), slice(), ws(), empty()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-001.json

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

# Node Description Batch 5 of 151

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

- "scratch_test_calc": "test-calc.js" | kind=code-symbol | source=scratch/test-calc.js:L1 | neighbors=[dcd11d4 first commit, calculateAllDependents(), checkFormulaDependencies(), evaluateExpression(), initialValues, overrides]
- "settings_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/settings/page.js:L1 | neighbors=[dcd11d4 first commit, paymentsClient.jsx, pdfClient.jsx, SettingsContent(), SettingsPage(), testsClient.jsx]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@905ef50c544a4ccfa89bdc37ce457a911b896b6a": "905ef50 fixed" | kind=Commit | source=git | neighbors=[720f016 2.0.13, main, a14c9b8 2.0.14, AdminLayoutClient.js, offlinePdfGenerator.js, offlinePrint.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@f3857f9f7aa53ad996b1d542de705f8b074c82df": "f3857f9 f" | kind=Commit | source=git | neighbors=[6325ac4 2.0.20, main, f4e1e65 2.0.21, offlinePdfGenerator.js, SyncIndicator.jsx, route.js]
- "component_resultentry": "resultEntry.jsx" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/resultEntry.jsx:L1 | neighbors=[dcd11d4 first commit, ResultEntry(), resultEntryMobile.jsx, page.js, 252e194 e, 2b2534c f]
- "dashboard_dashboardcharts": "DashboardCharts.js" | kind=code-symbol | source=app/(customer)/(dashboard)/dashboard/DashboardCharts.js:L1 | neighbors=[dcd11d4 first commit, CustomTooltip(), DepartmentDistributionChart(), RegistrationChart(), page.js, 252e194 e]
- "offline_network_networkmonitor": "NetworkMonitor" | kind=code-symbol | source=lib/offline/network.js:L6 | neighbors=[network.js, .checkConnection(), .constructor(), .handleStatusChange(), .notifyListeners(), .subscribe()]
- "offline_timestamps": "timestamps.js" | kind=code-symbol | source=lib/offline/timestamps.js:L1 | neighbors=[dcd11d4 first commit, db.js, compareUtc(), formatLocalDisplay(), getUtcIsoNow(), isServerNewer()]
- "prisma_seed": "seed.js" | kind=code-symbol | source=prisma/seed.js:L1 | neighbors=[dcd11d4 first commit, bcrypt, getDepartmentName(), main(), prisma, { PrismaClient }]
- "providers_offlineprovider": "OfflineProvider.jsx" | kind=code-symbol | source=components/providers/OfflineProvider.jsx:L1 | neighbors=[dcd11d4 first commit, OfflineProvider(), 2b2534c f, 6236f60 new update, 7d8c494 fxed, 84a8ff2 full indexeddb based]
- "registrationid_route": "route.js" | kind=code-symbol | source=app/api/print-report/[registrationId]/route.js:L1 | neighbors=[dcd11d4 first commit, formatDate(), GET(), getReferenceRange(), isOutOfRange(), isQualitativeAbnormal()]
- "runtime_edge_esm_getdeepfieldvalue": "getDeepFieldValue()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, bu(), Eu(), getDeepField(), hc(), pu()]
- "runtime_edge_esm_pu": "pu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, cu(), addErrorMessage(), addSuggestion(), Ao(), asObject()]
- "runtime_edge_esm_u": "u()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, g(), An(), findField(), getComputedFields(), getGlobalOmit()]
- "runtime_edge_esm_vu": "vu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, Tr(), addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_edge_getdeepfieldvalue": "getDeepFieldValue()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Au(), cu(), getDeepField(), ku(), ou()]
- "runtime_edge_ht": "ht()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L6 | neighbors=[edge.js, ac(), ic(), it(), ot(), Pe()]
- "runtime_edge_ku": "ku()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, Ar(), addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_index_browser_e": "e()" | kind=code-symbol | source=scratch/generated-client/runtime/index-browser.js:L1 | neighbors=[index-browser.js, be(), Ae(), L(), j(), se()]
- "runtime_index_browser_p": "p()" | kind=code-symbol | source=scratch/generated-client/runtime/index-browser.js:L1 | neighbors=[index-browser.js, B(), Ee(), jn(), L(), Nn()]
- "runtime_library_addsuggestion": "addSuggestion()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, dp(), Fp(), jp(), ks(), op()]
- "runtime_library_constructor": "constructor()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L4 | neighbors=[library.js, get(), _getName(), _getNamespace(), il(), instantiateLibrary()]
- "runtime_library_getdeepfieldvalue": "getDeepFieldValue()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, getDeepField(), gp(), jp(), om(), _p()]
- "runtime_library_jp": "jp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, addErrorMessage(), addSuggestion(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_library_om": "om()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, addErrorMessage(), getDeepField(), getDeepFieldValue(), getField(), im()]
- "runtime_library_rd": "rd()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, findField(), getOutputTypeDescription(), getSelectionPath(), mr(), nestSelection()]
- "runtime_library_vp": "vp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L25 | neighbors=[library.js, Tt(), addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_react_native_ju": "ju()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L9 | neighbors=[react-native.js, br(), addErrorMessage(), asObject(), getDeepField(), getDeepSubSelectionValue()]
- "runtime_react_native_pu": "pu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, getLocation(), lineAt(), mapLineAt(), mapLines(), prependSymbolAt()]
- "runtime_react_native_values": "values()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, getPrintWidth(), ns(), ro(), so(), su()]
- "runtime_wasm_addsuggestion": "addSuggestion()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L3 | neighbors=[wasm.js, ei(), fs(), hs(), Is(), Ks()]
- "runtime_wasm_b": "B()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, compare(), readIntBE(), readIntLE(), readUIntBE(), readUIntLE()]
- "runtime_wasm_fs": "fs()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, addErrorMessage(), addField(), addSuggestion(), asObject(), getDeepSelectionParent()]
- "runtime_wasm_oa": "oa()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, na(), ci(), de(), Dr(), findField()]
- "runtime_wasm_sa": "sa()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, ra(), de(), Dr(), findField(), getComputedFields()]
- "runtime_wasm_so": "so()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L14 | neighbors=[wasm.js, ao(), from(), isBuffer(), isDecimal(), je()]
- "runtime_wasm_tt": "tt()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L6 | neighbors=[wasm.js, ai(), ea(), Pa(), ge(), getAllClientExtensions()]
- "scratch_test_identity_and_qr": "test_identity_and_qr.mjs" | kind=code-symbol | source=scratch/test_identity_and_qr.mjs:L1 | neighbors=[dcd11d4 first commit, decryptReportToken(), generateReportToken(), verifyReportToken(), generateRandomSuffix(), generateQrCodeDataUrl()]
- "tests_route": "route.js" | kind=code-symbol | source=app/api/tests/route.js:L1 | neighbors=[dcd11d4 first commit, DELETE(), GET(), POST(), PUT(), serializeSingleTest()]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@56f4d63de7f588eafda68878782538c1659db650": "56f4d63 f" | kind=Commit | source=git | neighbors=[main, 84807f4 1.1.27, page.js, modelRegistry.js, syncManager.js, page.js]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-004.json

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

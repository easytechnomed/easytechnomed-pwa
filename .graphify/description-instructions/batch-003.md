# Node Description Batch 4 of 151

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

- "scratch_test_user_lipid": "test-user-lipid.js" | kind=code-symbol | source=scratch/test-user-lipid.js:L1 | neighbors=[dcd11d4 first commit, addValueToValuesMap(), checkFormulaDependencies(), evaluatedFormulas, evaluateExpression(), formulas]
- "sync_modelregistry": "modelRegistry.js" | kind=code-symbol | source=lib/offline/sync/modelRegistry.js:L1 | neighbors=[dcd11d4 first commit, MODEL_REGISTRY, syncManager.js, 2b2534c f, 56f4d63 f, 67434f2 payment issue only]
- "app_layout": "layout.js" | kind=code-symbol | source=app/layout.js:L1 | neighbors=[metadata, outfit, RootLayout(), viewport, dcd11d4 first commit, 252e194 e]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@9f59247de8e17ece3b64548107440d0473aa2d43": "9f59247 expire token" | kind=Commit | source=git | neighbors=[48cc7ec 2.0.22, main, eacdd5b 2.0.23, resultEntry.jsx, OfflineSyncContext.js, useSync.js]
- "lib_auth": "auth.js" | kind=code-symbol | source=lib/auth.js:L1 | neighbors=[dcd11d4 first commit, requireAdmin(), requireSuperAdmin(), requireUser(), signToken(), verifySuperAdminAPI()]
- "lib_mail_sendmailwithfallback": "sendMailWithFallback()" | kind=code-symbol | source=lib/mail.js:L46 | neighbors=[mail.js, sendApprovalEmail(), createTransporter(), getFallbackConfig(), getPrimaryConfig(), sendOnboardingWelcomeEmail()]
- "pdf_pdfclient": "pdfClient.jsx" | kind=code-symbol | source=app/(customer)/(dashboard)/settings/pdf/pdfClient.jsx:L1 | neighbors=[dcd11d4 first commit, page.js, PdfSettingsClient(), page.js, 252e194 e, 532b740 fixed]
- "print_billpdfgenerator": "billPdfGenerator.js" | kind=code-symbol | source=lib/offline/print/billPdfGenerator.js:L1 | neighbors=[dcd11d4 first commit, offlinePrint.js, CODE39_PATTERNS, drawCode39Barcode(), formatDate(), generateOfflineBillPdf()]
- "print_openprint": "openPrint.js" | kind=code-symbol | source=lib/offline/print/openPrint.js:L1 | neighbors=[dcd11d4 first commit, billHtmlGenerator.js, generateOfflineBillHtml(), billPdfGenerator.js, generateOfflineBillPdf(), openOfflineBillPrint()]
- "registrations_route": "route.js" | kind=code-symbol | source=app/api/registrations/route.js:L1 | neighbors=[dcd11d4 first commit, generateRandomSuffix(), GET(), POST(), registrationSchema, serializeData()]
- "runtime_edge_addsuggestion": "addSuggestion()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Ao(), Au(), du(), eu(), mu()]
- "runtime_edge_ar": "Ar()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Au(), bo(), hu(), ku(), Su()]
- "runtime_edge_esm_addsuggestion": "addSuggestion()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, Ao(), Au(), cu(), mu(), pu()]
- "runtime_edge_esm_co": "co()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, asObject(), e(), getDeepSubSelectionValue(), getField(), getFieldValue()]
- "runtime_edge_esm_get": "get()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L5 | neighbors=[edge-esm.js, constructor(), extractHostAndApiKey(), getAllBatchQueryCallbacks(), getAllClientExtensions(), getOrCreate()]
- "runtime_edge_esm_o": "O()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, ce(), Er(), gn(), ke(), kl()]
- "runtime_edge_esm_values": "values()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L5 | neighbors=[edge-esm.js, getPrintWidth(), iu(), mo(), No(), os()]
- "runtime_edge_esm_yu": "yu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, Tr(), addErrorMessage(), Ao(), asObject(), getDeepField()]
- "runtime_edge_get": "get()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, constructor(), du(), extractHostAndApiKey(), getAllBatchQueryCallbacks(), getAllClientExtensions()]
- "runtime_edge_uo": "Uo()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, bo(), getArgumentName(), getArgumentPath(), getSelectionPath(), isPreviewFeatureOn()]
- "runtime_edge_values": "values()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, cs(), du(), fo(), getPrintWidth(), O()]
- "runtime_edge_wu": "wu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, Ar(), addErrorMessage(), asObject(), bu(), getDeepSubSelectionValue()]
- "runtime_edge_xu": "xu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, wu(), addErrorMessage(), addField(), addSuggestion(), asObject()]
- "runtime_library_aa": "aa()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, getArgumentName(), getArgumentPath(), getSelectionPath(), isPreviewFeatureOn(), nestArgument()]
- "runtime_library_fp": "Fp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, addErrorMessage(), addField(), addSuggestion(), asObject(), getDeepSelectionParent()]
- "runtime_library_get": "get()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, constructor(), extractHostAndApiKey(), getAllBatchQueryCallbacks(), getAllClientExtensions(), getOrCreate()]
- "runtime_library_kp": "kp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, addErrorMessage(), asObject(), Fp(), getDeepSubSelectionValue(), getField()]
- "runtime_library_values": "values()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, getPrintWidth(), na(), Oa(), ra(), rp()]
- "runtime_library_y": "y()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, ap(), cp(), Fe(), He(), nc()]
- "runtime_react_native_addsuggestion": "addSuggestion()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L8 | neighbors=[react-native.js, du(), eo(), Hu(), iu(), ku()]
- "runtime_react_native_k": "k()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, be(), bl(), cu(), de(), dr()]
- "runtime_react_native_markaserror": "markAsError()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L8 | neighbors=[react-native.js, bu(), hp(), iu(), ju(), mu()]
- "runtime_react_native_mo": "Mo()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, fo(), getArgumentName(), getArgumentPath(), getSelectionPath(), isPreviewFeatureOn()]
- "runtime_react_native_oc": "oc()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, ic(), Cn(), findField(), getOutputTypeDescription(), getSelectionPath()]
- "runtime_react_native_r": "r()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, Ea(), getOrCreate(), mapLineAt(), ps(), e()]
- "runtime_react_native_uu": "uu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, addErrorMessage(), addField(), addSuggestion(), asObject(), getDeepFieldValue()]
- "runtime_wasm_bs": "Bs()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, addErrorMessage(), asObject(), getDeepField(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_wasm_concat": "concat()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, alloc(), slice(), ia(), ka(), la()]
- "runtime_wasm_fi": "fi()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, di(), de(), getArgumentName(), getArgumentPath(), getSelectionPath()]
- "runtime_wasm_includes": "includes()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, Ce(), go(), indexOf(), isEncoding(), isPreviewFeatureOn()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-003.json

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

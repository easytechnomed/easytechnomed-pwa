# Node Description Batch 9 of 151

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

- "runtime_react_native_mu": "mu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField(), markAsError()]
- "runtime_react_native_nc": "nc()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, ac(), getSelectionPath(), ic(), isPreviewFeatureOn(), throwValidationError()]
- "runtime_react_native_nu": "nu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, addErrorMessage(), getDeepSelectionParent(), isEmpty(), removeAllFields(), se()]
- "runtime_react_native_request": "request()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L60 | neighbors=[react-native.js, buildQueryError(), handleAndLogRequestError(), parseEngineResponse(), parseRequestError(), query()]
- "runtime_react_native_sr": "Sr()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, handleRequestError(), br(), gt(), Rr(), ut()]
- "runtime_react_native_start": "start()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L60 | neighbors=[react-native.js, applyPendingMigrations(), metrics(), request(), requestBatch(), runInChildSpan()]
- "runtime_react_native_te": "Te()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, ac(), is(), lc(), Mo(), oc()]
- "runtime_react_native_ti": "ti()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L1 | neighbors=[react-native.js, T(), ba(), ni(), wa(), ya()]
- "runtime_react_native_to": "to()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, de(), _getName(), lt(), Vi(), xo()]
- "runtime_react_native_vu": "vu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L6 | neighbors=[react-native.js, pu(), addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_react_native_wt": "Wt()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, ac(), Fr(), oc(), isPreviewFeatureOn(), Mo()]
- "runtime_react_native_wu": "wu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), getFields()]
- "runtime_react_native_xa": "xa()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L1 | neighbors=[react-native.js, Fa(), ka(), Ma(), Oa(), Ra()]
- "runtime_wasm_ct": "Ct()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L6 | neighbors=[wasm.js, be(), je(), Qe(), slice(), ze()]
- "runtime_wasm_de": "de()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, aa(), fi(), ia(), oa(), qi()]
- "runtime_wasm_dr": "Dr()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, getSelectionPath(), isPreviewFeatureOn(), throwValidationError(), ia(), oa()]
- "runtime_wasm_ds": "ds()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, at(), addErrorMessage(), ei(), getDeepSelectionParent(), isEmpty()]
- "runtime_wasm_fill": "fill()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, alloc(), from(), nn(), slice(), V()]
- "runtime_wasm_getselectionpath": "getSelectionPath()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, aa(), di(), Dr(), fi(), ia()]
- "runtime_wasm_gs": "gs()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), getFields()]
- "runtime_wasm_ispreviewfeatureon": "isPreviewFeatureOn()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, Dr(), fi(), includes(), na(), ra()]
- "runtime_wasm_it": "It()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, compare(), equals(), ae(), D(), slice()]
- "runtime_wasm_ms": "Ms()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L3 | neighbors=[wasm.js, addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField(), markAsError()]
- "runtime_wasm_nestselection": "nestSelection()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, ia(), concat(), e(), findField(), oa()]
- "runtime_wasm_ns": "Ns()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, addErrorMessage(), ei(), Ks(), markAsError(), ti()]
- "runtime_wasm_oi": "oi()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, addField(), Pa(), si(), t(), va()]
- "runtime_wasm_ra": "ra()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, getSelectionPath(), isPreviewFeatureOn(), na(), sa(), throwValidationError()]
- "runtime_wasm_ui": "ui()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, sa(), _a(), et(), ge(), getAllComputedFields()]
- "runtime_wasm_vs": "Vs()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, t(), addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_wasm_withindent": "withIndent()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L2 | neighbors=[wasm.js, indent(), t(), unindent(), write(), writeWithContents()]
- "runtime_wasm_xt": "xt()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, ia(), sa(), fi(), isPreviewFeatureOn(), ra()]
- "runtime_wasm_y": "Y()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, readIntBE(), readIntLE(), readUIntBE(), readUIntLE(), writeUIntBE()]
- "scratch_test_dlc_calc": "test-dlc-calc.js" | kind=code-symbol | source=scratch/test-dlc-calc.js:L1 | neighbors=[dcd11d4 first commit, calculateDifferentialSummary(), { calculateDifferentialSummary }, params, values1, values2]
- "test_route": "route.js" | kind=code-symbol | source=app/api/n8n/test/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), parseNullableFloat(), parseNullableOptions(), parseNullableString(), POST()]
- "address_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/settings/address/page.js:L1 | neighbors=[AddressSettingsPage(), dcd11d4 first commit, 252e194 e, 84a8ff2 full indexeddb based, aae6bad fixed, cf2bb98 new]
- "app_manifest": "manifest.js" | kind=code-symbol | source=app/manifest.js:L1 | neighbors=[manifest(), dcd11d4 first commit, 252e194 e, 37dcb32 fixed, 4ba60cc fixed, 5e3d9ef d]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@4d7570f34d922bf4ce09e2e9653537c79141d117": "4d7570f fixed" | kind=Commit | source=git | neighbors=[offlineAuth.js, main, 7ec76ba 2.0.12, clientAuth.js, LoginPageClient.js, 5ff2734 2.0.11]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@6812ab9e9aa4366d92085aae7d5357b3d2acc99d": "6812ab9 new ui dashboard" | kind=Commit | source=git | neighbors=[main, 44ad6b2 new ui dashboard, DashboardCharts.js, page.js, RangeSelector.js, 9d71afc 3.0.22]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@a712d0ec90e4494b2f72928b5f7b27f9e8b414d8": "a712d0e ios issue pwa" | kind=Commit | source=git | neighbors=[20dc303 3.0.19, layout.js, main, a09f0a9 3.0.21, PWARegister.js, Input.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@b5dedb0193beae683457aa771ab1058ec8687da3": "b5dedb0 f" | kind=Commit | source=git | neighbors=[main, c41a815 3.0.11, SyncIndicator.jsx, OfflineProvider.jsx, syncManager.js, c82cfd7 3.0.10]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-008.json

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

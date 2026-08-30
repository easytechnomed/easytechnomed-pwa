# Node Description Batch 7 of 151

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

- "runtime_wasm_aa": "aa()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, de(), di(), getArgumentName(), getArgumentPath(), getSelectionPath()]
- "runtime_wasm_get": "get()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, as(), getAllBatchQueryCallbacks(), getAllClientExtensions(), getOrCreate(), sql()]
- "runtime_wasm_getdeepfieldvalue": "getDeepFieldValue()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L3 | neighbors=[wasm.js, Bs(), getDeepField(), gs(), js(), nl()]
- "runtime_wasm_hasfield": "hasField()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L3 | neighbors=[wasm.js, ei(), getField(), hs(), Ks(), ls()]
- "runtime_wasm_is": "Is()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L3 | neighbors=[wasm.js, addErrorMessage(), addSuggestion(), getDeepSelectionParent(), getField(), markAsError()]
- "runtime_wasm_js": "js()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), markAsError()]
- "runtime_wasm_ls": "ls()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L1 | neighbors=[wasm.js, addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField(), hasField()]
- "runtime_wasm_nl": "nl()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L26 | neighbors=[wasm.js, addErrorMessage(), getDeepField(), getDeepFieldValue(), getField(), Ht()]
- "runtime_wasm_qs": "qs()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, addErrorMessage(), asObject(), getDeepField(), getDeepSubSelectionValue(), getField()]
- "runtime_wasm_throwvalidationerror": "throwValidationError()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, aa(), di(), Dr(), fi(), ia()]
- "runtime_wasm_ti": "ti()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L4 | neighbors=[wasm.js, Ns(), asObject(), getDeepSubSelectionValue(), getField(), getFieldValue()]
- "runtime_wasm_values": "values()" | kind=code-symbol | source=scratch/generated-client/runtime/wasm.js:L5 | neighbors=[wasm.js, as(), ci(), getPrintWidth(), ui(), unpack()]
- "scratch_test_formula_calc": "test-formula-calc.js" | kind=code-symbol | source=scratch/test-formula-calc.js:L1 | neighbors=[dcd11d4 first commit, checkFormulaDependencies(), evaluateExpression(), resF, resM, valuesFemale]
- "scratch_test_pdf_customization": "test-pdf-customization.mjs" | kind=code-symbol | source=scratch/test-pdf-customization.mjs:L1 | neighbors=[dcd11d4 first commit, computeColumnLayout(), DEFAULT_COLUMNS, getFontFamilyDefinitions(), hexToRgb(), PDF_THEME_PRESETS]
- "scratch_test_reg_17": "test-reg-17.js" | kind=code-symbol | source=scratch/test-reg-17.js:L1 | neighbors=[dcd11d4 first commit, addValueToValuesMap(), checkFormulaDependencies(), evaluateExpression(), inputValues, regPayload]
- "ui_card": "Card.js" | kind=code-symbol | source=components/ui/Card.js:L1 | neighbors=[dcd11d4 first commit, Card(), CardContent(), CardDescription(), CardFooter(), CardHeader()]
- "ui_table": "Table.js" | kind=code-symbol | source=components/ui/Table.js:L1 | neighbors=[dcd11d4 first commit, Table(), TableBody(), TableCell(), TableHead(), TableHeader()]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@2582be7e5cb0ce4ac0f6544d7b325a2fc7cc8f2a": "2582be7 fixed zoom issue" | kind=Commit | source=git | neighbors=[layout.js, main, 20dc303 3.0.19, LoginPageClient.js, RegisterPageClient.js, Input.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@6fcf01513cf102294115509392d599808735935d": "6fcf015 f" | kind=Commit | source=git | neighbors=[main, cc4c427 1.1.26, page.js, SyncStatusIcon.jsx, syncManager.js, page.js]
- "commit:repo:github.com-personal/miznaansari/easytechnomed-pwa@eb8b1e55a4ac0099b81b812ad72ed96f863a41b6": "eb8b1e5 f" | kind=Commit | source=git | neighbors=[7d8c494 fxed, main, dbe1732 1.1.25, PWARegister.js, error.js, page.js]
- "component_differentialcounttracker": "DifferentialCountTracker.jsx" | kind=code-symbol | source=app/(customer)/(dashboard)/test-report/component/DifferentialCountTracker.jsx:L1 | neighbors=[dcd11d4 first commit, calculateDifferentialSummary(), DifferentialHeaderBadge(), DLC_DEFINITIONS, isDifferentialHeader(), validateDifferentialOnSave()]
- "doctors_route": "route.js" | kind=code-symbol | source=app/api/doctors/route.js:L1 | neighbors=[dcd11d4 first commit, DELETE(), GET(), POST(), PUT(), serializeData()]
- "generated_client_edge": "edge.js" | kind=code-symbol | source=scratch/generated-client/edge.js:L1 | neighbors=[dcd11d4 first commit, config, Prisma, PrismaClient, {
  PrismaClientKnownRequestError,
  Pr…, empty()]
- "lib_pdftheme": "pdfTheme.js" | kind=code-symbol | source=lib/pdfTheme.js:L1 | neighbors=[dcd11d4 first commit, computeColumnLayout(), DEFAULT_COLUMNS, getFontFamilyDefinitions(), hexToRgb(), PDF_THEME_PRESETS]
- "lib_reportsecurity": "reportSecurity.js" | kind=code-symbol | source=lib/reportSecurity.js:L1 | neighbors=[dcd11d4 first commit, decryptReportToken(), deriveBufferKey(), generateReportToken(), getKeyRing(), verifyReportToken()]
- "pdf_route": "route.js" | kind=code-symbol | source=app/api/settings/pdf/route.js:L1 | neighbors=[dcd11d4 first commit, DEFAULT_COLUMN_ORDER, DEFAULT_PDF_SETTINGS, GET(), POST(), 252e194 e]
- "proxy": "proxy.js" | kind=code-symbol | source=proxy.js:L1 | neighbors=[dcd11d4 first commit, config, JWT_SECRET, proxy(), 252e194 e, 5e3d9ef d]
- "runtime_edge_aa": "Aa()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, ln(), r(), rn(), sn(), xe()]
- "runtime_edge_bu": "bu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, addErrorMessage(), Ao(), getDeepSelectionParent(), isEmpty(), removeAllFields()]
- "runtime_edge_do": "Do()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, Cr(), _getName(), ko(), Lu(), ot()]
- "runtime_edge_du": "du()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L2 | neighbors=[edge.js, bo(), addSuggestion(), get(), hasField(), mu()]
- "runtime_edge_esm_an": "An()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L5 | neighbors=[edge-esm.js, getSelectionPath(), isPreviewFeatureOn(), throwValidationError(), fu(), lu()]
- "runtime_edge_esm_ba": "ba()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, Aa(), Ia(), ka(), Oa(), pi()]
- "runtime_edge_esm_bu": "bu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), markAsError()]
- "runtime_edge_esm_constructor": "constructor()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, ds(), get(), _getName(), _getNamespace(), qt()]
- "runtime_edge_esm_eu": "Eu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), markAsError()]
- "runtime_edge_esm_getselectionpath": "getSelectionPath()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L5 | neighbors=[edge-esm.js, An(), fu(), lo(), mu(), qo()]
- "runtime_edge_esm_handlerequesterror": "handleRequestError()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L20 | neighbors=[edge-esm.js, handleAndLogRequestError(), $c(), Dr(), ot(), sanitizeMessage()]
- "runtime_edge_esm_hasfield": "hasField()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, Ao(), Au(), cu(), getField(), to()]
- "runtime_edge_esm_iu": "iu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L2 | neighbors=[edge-esm.js, addItem(), get(), Oo(), ou(), values()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-006.json

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

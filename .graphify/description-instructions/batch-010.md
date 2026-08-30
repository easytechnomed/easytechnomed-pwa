# Node Description Batch 11 of 151

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

- "runtime_edge_ru": "ru()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), markAsError()]
- "runtime_edge_sa": "Sa()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, Ba(), hi(), La(), Na(), qa()]
- "runtime_edge_tu": "tu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField(), markAsError()]
- "runtime_edge_u": "u()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, g(), getSelectionPath(), Gu(), isPreviewFeatureOn(), throwValidationError()]
- "runtime_edge_vt": "Vt()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, Gu(), ju(), qr(), isPreviewFeatureOn(), Uo()]
- "runtime_edge_we": "we()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, Gu(), ju(), ps(), qu(), Uo()]
- "runtime_edge_withindent": "withIndent()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L2 | neighbors=[edge.js, indent(), unindent(), write(), writeWithContents(), writeWithItems()]
- "runtime_edge_xe": "xe()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, Aa(), on(), rn(), Ta(), va()]
- "runtime_library_dp": "dp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, addErrorMessage(), addSuggestion(), Fe(), removeAllFields(), wt()]
- "runtime_library_ed": "ed()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, getSelectionPath(), isPreviewFeatureOn(), td(), throwValidationError(), mr()]
- "runtime_library_en": "en()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, renderAllMessages(), toString(), write(), Si(), Tc()]
- "runtime_library_fu": "Fu()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L4 | neighbors=[library.js, mt(), otherwise(), when(), with(), Lu()]
- "runtime_library_getdeepfield": "getDeepField()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, Bp(), getField(), getDeepFieldValue(), om(), _p()]
- "runtime_library_getdeepselectionparent": "getDeepSelectionParent()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L27 | neighbors=[library.js, Fp(), getFieldValue(), getSelectionParent(), op(), _p()]
- "runtime_library_getglobaltracinghelper": "getGlobalTracingHelper()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L121 | neighbors=[library.js, createEngineSpan(), getActiveContext(), getTraceParent(), isEnabled(), runInChildSpan()]
- "runtime_library_getorcreate": "getOrCreate()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, getAllComputedFields(), getAllModelExtensions(), getAllQueryCallbacks(), get(), r()]
- "runtime_library_he": "He()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, K(), nn(), rr(), slice(), y()]
- "runtime_library_instantiatelibrary": "instantiateLibrary()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, constructor(), getCurrentBinaryTarget(), loadEngine(), Qn(), version()]
- "runtime_library_ip": "ip()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField(), markAsError()]
- "runtime_library_ir": "ir()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, Fp(), Hs(), op(), _p(), qp()]
- "runtime_library_ispreviewfeatureon": "isPreviewFeatureOn()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, aa(), ed(), I(), mr(), td()]
- "runtime_library_ji": "ji()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, getAllModelExtensions(), gr(), qd(), Se(), Vd()]
- "runtime_library_mo": "Mo()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L5 | neighbors=[library.js, ju(), Lo(), Vu(), nt(), Yn()]
- "runtime_library_nestselection": "nestSelection()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, id(), nd(), e(), findField(), rd()]
- "runtime_library_oa": "Oa()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L31 | neighbors=[library.js, Gd(), getAllComputedFields(), Se(), Ud(), values()]
- "runtime_library_otherwise": "otherwise()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L4 | neighbors=[library.js, Fu(), Mu(), t(), ui(), Vu()]
- "runtime_library_parseengineresponse": "parseEngineResponse()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L112 | neighbors=[library.js, logger(), metrics(), request(), requestBatch(), transaction()]
- "runtime_library_ri": "ri()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L1 | neighbors=[library.js, K(), Qo(), rr(), slice(), y()]
- "runtime_library_td": "td()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, ed(), isPreviewFeatureOn(), isRawAction(), nd(), rd()]
- "runtime_library_transaction": "transaction()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, getExternalAdapterError(), hm(), parseEngineResponse(), start(), withRetry()]
- "runtime_library_when": "when()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L4 | neighbors=[library.js, Fu(), ui(), e(), r(), t()]
- "runtime_library_wn": "wn()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, handleRequestError(), throwValidationError(), Ot(), pn(), Tt()]
- "runtime_library_yr": "Yr()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, getExternalAdapterError(), Bd(), getAllClientExtensions(), gr(), Se()]
- "runtime_library_za": "za()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L64 | neighbors=[library.js, loadLibrary(), Ja(), li(), nt(), Zd()]
- "runtime_react_native_constructor": "constructor()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L1 | neighbors=[react-native.js, cs(), _getName(), _getNamespace(), instantiateLibrary(), Jt()]
- "runtime_react_native_getdeepfield": "getDeepField()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L8 | neighbors=[react-native.js, getField(), getDeepFieldValue(), hp(), ju(), qu()]
- "runtime_react_native_getdeepselectionparent": "getDeepSelectionParent()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L8 | neighbors=[react-native.js, du(), getFieldValue(), getSelectionParent(), iu(), nu()]
- "runtime_react_native_getglobaltracinghelper": "getGlobalTracingHelper()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L69 | neighbors=[react-native.js, createEngineSpan(), getActiveContext(), getTraceParent(), isEnabled(), runInChildSpan()]
- "runtime_react_native_getorcreate": "getOrCreate()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, getAllComputedFields(), getAllModelExtensions(), getAllQueryCallbacks(), get(), r()]
- "runtime_react_native_hr": "Hr()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L1 | neighbors=[react-native.js, Oe(), ri(), toString(), zr(), T()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-010.json

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

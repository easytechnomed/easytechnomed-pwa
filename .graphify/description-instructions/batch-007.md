# Node Description Batch 8 of 151

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

- "runtime_edge_esm_n": "N()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, dc(), Ee(), fc(), getAllModelExtensions(), jt()]
- "runtime_edge_esm_os": "os()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L6 | neighbors=[edge-esm.js, Ee(), getAllComputedFields(), hc(), mt(), values()]
- "runtime_edge_esm_si": "si()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, de(), ha(), li(), wa(), ya()]
- "runtime_edge_esm_wo": "wo()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L2 | neighbors=[edge-esm.js, Tr(), addErrorMessage(), ft(), iu(), qr()]
- "runtime_edge_esm_xu": "xu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, Tr(), addErrorMessage(), asObject(), getDeepField(), getDeepSubSelectionValue()]
- "runtime_edge_esm_ye": "ye()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L5 | neighbors=[edge-esm.js, fu(), lu(), qo(), qu(), ss()]
- "runtime_edge_fr": "Fr()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, Ar(), dt(), Nr(), st(), handleRequestError()]
- "runtime_edge_getselectionpath": "getSelectionPath()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L5 | neighbors=[edge.js, bo(), In(), ju(), qu(), u()]
- "runtime_edge_hu": "hu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Ar(), addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField()]
- "runtime_edge_iu": "iu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, addErrorMessage(), asObject(), getDeepField(), getDeepSubSelectionValue(), markAsError()]
- "runtime_edge_ro": "ro()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, go(), asObject(), getDeepSubSelectionValue(), getField(), getFieldValue()]
- "runtime_edge_su": "Su()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, Ar(), addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_edge_vu": "vu()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L4 | neighbors=[edge.js, Ar(), addErrorMessage(), isPreviewFeatureOn(), isRawAction(), ju()]
- "runtime_library_bp": "Bp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, addErrorMessage(), asObject(), getDeepField(), getDeepSubSelectionValue(), markAsError()]
- "runtime_library_br": "Br()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L4 | neighbors=[library.js, Fe(), It(), Pt(), slice(), vt()]
- "runtime_library_fe": "Fe()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, Br(), dp(), e(), y(), shouldApplyGlobalOmit()]
- "runtime_library_getselectionpath": "getSelectionPath()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, aa(), ed(), I(), od(), rd()]
- "runtime_library_gp": "gp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, addErrorMessage(), asObject(), getDeepFieldValue(), getDeepSubSelectionValue(), getFields()]
- "runtime_library_ha": "ha()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, Dn(), kn(), Ot(), toString(), write()]
- "runtime_library_lo": "Lo()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L4 | neighbors=[library.js, Lu(), Mu(), rl(), $u(), Uu()]
- "runtime_library_loadlibrary": "loadLibrary()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, loadEngine(), In(), runInChildSpan(), ui(), Yn()]
- "runtime_library_mp": "Mp()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L28 | neighbors=[library.js, addErrorMessage(), asObject(), getDeepSubSelectionValue(), getField(), markAsError()]
- "runtime_library_mr": "mr()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, id(), aa(), ed(), isPreviewFeatureOn(), rd()]
- "runtime_library_op": "op()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L21 | neighbors=[library.js, addErrorMessage(), addSuggestion(), getDeepSelectionParent(), getField(), ir()]
- "runtime_library_re": "Re()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, aa(), id(), ka(), nd(), od()]
- "runtime_library_request": "request()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, buildQueryError(), handleAndLogRequestError(), parseEngineResponse(), parseRequestError(), requestInternal()]
- "runtime_library_requestbatch": "requestBatch()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, buildQueryError(), Ft(), parseEngineResponse(), pl(), requestInternal()]
- "runtime_library_runinchildspan": "runInChildSpan()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L121 | neighbors=[library.js, loadLibrary(), getGlobalTracingHelper(), t(), start(), stop()]
- "runtime_library_start": "start()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L111 | neighbors=[library.js, metrics(), request(), requestBatch(), runInChildSpan(), transaction()]
- "runtime_library_ui": "ui()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L6 | neighbors=[library.js, loadLibrary(), ii(), mt(), otherwise(), when()]
- "runtime_library_vu": "Vu()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L5 | neighbors=[library.js, Mo(), Br(), mt(), $o(), otherwise()]
- "runtime_library_withindent": "withIndent()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L26 | neighbors=[library.js, indent(), t(), unindent(), write(), writeWithContents()]
- "runtime_library_xs": "Xs()" | kind=code-symbol | source=scratch/generated-client/runtime/library.js:L29 | neighbors=[library.js, _getName(), It(), ln(), vt(), zp()]
- "runtime_react_native_bn": "bn()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, be(), eo(), S(), se(), slice()]
- "runtime_react_native_bo": "bo()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L9 | neighbors=[react-native.js, asObject(), getDeepSubSelectionValue(), getField(), getFieldValue(), bu()]
- "runtime_react_native_cn": "Cn()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, ac(), getSelectionPath(), isPreviewFeatureOn(), throwValidationError(), oc()]
- "runtime_react_native_getselectionpath": "getSelectionPath()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L10 | neighbors=[react-native.js, Cn(), fo(), lc(), Mo(), nc()]
- "runtime_react_native_gu": "gu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, addErrorMessage(), asObject(), Fe(), getDeepFieldValue(), getDeepSubSelectionValue()]
- "runtime_react_native_handlerequesterror": "handleRequestError()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L69 | neighbors=[react-native.js, handleAndLogRequestError(), cp(), pp(), sanitizeMessage(), Sr()]
- "runtime_react_native_iu": "iu()" | kind=code-symbol | source=scratch/generated-client/runtime/react-native.js:L2 | neighbors=[react-native.js, addErrorMessage(), addSuggestion(), getDeepSelectionParent(), getField(), k()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-007.json

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

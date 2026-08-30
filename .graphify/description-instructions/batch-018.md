# Node Description Batch 19 of 151

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

- "components_expiredplanview": "ExpiredPlanView.jsx" | kind=code-symbol | source=components/ExpiredPlanView.jsx:L1 | neighbors=[dcd11d4 first commit, ExpiredPlanView(), 252e194 e, 6236f60 new update]
- "doctor_summary_route": "route.js" | kind=code-symbol | source=app/api/doctor-summary/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), serializeData(), 252e194 e]
- "doctors_route_serializedata": "serializeData()" | kind=code-symbol | source=app/api/doctors/route.js:L6 | neighbors=[route.js, GET(), POST(), PUT()]
- "improve_route": "route.js" | kind=code-symbol | source=app/api/ai/improve/route.js:L1 | neighbors=[dcd11d4 first commit, callGemini(), POST(), 252e194 e]
- "lib_formulautils_checkformuladependencies": "checkFormulaDependencies()" | kind=code-symbol | source=lib/formulaUtils.js:L422 | neighbors=[formulaEngine.js, formulaUtils.js, calculateAllDependents(), test-formula-verification.mjs]
- "lib_formulautils_evaluateexpression": "evaluateExpression()" | kind=code-symbol | source=lib/formulaUtils.js:L332 | neighbors=[formulaEngine.js, formulaUtils.js, calculateAllDependents(), test-formula-verification.mjs]
- "lib_r2": "r2.js" | kind=code-symbol | source=lib/r2.js:L1 | neighbors=[dcd11d4 first commit, s3Client, uploadFileToR2(), 252e194 e]
- "lib_reportsecurity_decryptreporttoken": "decryptReportToken()" | kind=code-symbol | source=lib/reportSecurity.js:L115 | neighbors=[reportSecurity.js, getKeyRing(), verifyReportToken(), test_identity_and_qr.mjs]
- "lib_reportsecurity_generatereporttoken": "generateReportToken()" | kind=code-symbol | source=lib/reportSecurity.js:L74 | neighbors=[reportSecurity.js, getKeyRing(), verifyReportToken(), test_identity_and_qr.mjs]
- "lib_reportsecurity_verifyreporttoken": "verifyReportToken()" | kind=code-symbol | source=lib/reportSecurity.js:L173 | neighbors=[reportSecurity.js, decryptReportToken(), generateReportToken(), test_identity_and_qr.mjs]
- "logout_redirect_route": "route.js" | kind=code-symbol | source=app/api/auth/logout-redirect/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), 252e194 e, 5e3d9ef d]
- "logout_route": "route.js" | kind=code-symbol | source=app/api/authas/logout/route.js:L1 | neighbors=[dcd11d4 first commit, POST(), 252e194 e, 5e3d9ef d]
- "offline_offlinepdfgenerator_generatereportpdfoffline": "generateReportPdfOffline()" | kind=code-symbol | source=lib/offline/offlinePdfGenerator.js:L271 | neighbors=[offlinePdfGenerator.js, layoutMarkdownLines(), parseMarkdownTokens(), offlinePrint.js]
- "offline_unsyncedlogoutmodal": "UnsyncedLogoutModal.jsx" | kind=code-symbol | source=components/offline/UnsyncedLogoutModal.jsx:L1 | neighbors=[dcd11d4 first commit, UnsyncedLogoutModal(), 2b2534c f, 6236f60 new update]
- "paymentid_route_get": "GET()" | kind=code-symbol | source=app/api/print-subscription-invoice/[paymentId]/route.js:L74 | neighbors=[route.js, formatDate(), formatDateTime(), numberToWords()]
- "payments_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/settings/payments/page.js:L1 | neighbors=[dcd11d4 first commit, SettingsPaymentsPage(), paymentsClient.jsx, 252e194 e]
- "pdf_page": "page.js" | kind=code-symbol | source=app/(customer)/(dashboard)/settings/pdf/page.js:L1 | neighbors=[dcd11d4 first commit, SettingsPdfPage(), pdfClient.jsx, 252e194 e]
- "preview_pdf_route": "route.js" | kind=code-symbol | source=app/api/settings/preview-pdf/route.js:L1 | neighbors=[dcd11d4 first commit, formatDate(), GET(), 252e194 e]
- "print_billhtmlgenerator_generateofflinebillhtml": "generateOfflineBillHtml()" | kind=code-symbol | source=lib/offline/print/billHtmlGenerator.js:L61 | neighbors=[billHtmlGenerator.js, formatDate(), numberToWords(), openPrint.js]
- "print_qrgenerator_generateqrcodepngbytes": "generateQrCodePngBytes()" | kind=code-symbol | source=lib/offline/print/qrGenerator.js:L11 | neighbors=[billPdfGenerator.js, qrGenerator.js, reportPdfGenerator.js, test_identity_and_qr.mjs]
- "print_reportpdfgenerator_generateofflinereportpdf": "generateOfflineReportPdf()" | kind=code-symbol | source=lib/offline/print/reportPdfGenerator.js:L131 | neighbors=[offlinePrint.js, openPrint.js, reportPdfGenerator.js, getReferenceRange()]
- "prisma_seed_main": "main()" | kind=code-symbol | source=prisma/seed.js:L5 | neighbors=[seed.js, getDepartmentName(), processTestParameters(), seedLimsFormulasAndConfigurations()]
- "profile_route": "route.js" | kind=code-symbol | source=app/api/profile/route.js:L1 | neighbors=[dcd11d4 first commit, GET(), PUT(), 252e194 e]
- "registrationid_route_get": "GET()" | kind=code-symbol | source=app/api/print-report/[registrationId]/route.js:L96 | neighbors=[route.js, formatDate(), getReferenceRange(), numberToWords()]
- "runtime_edge_addfield": "addField()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L3 | neighbors=[edge.js, Au(), ko(), xu()]
- "runtime_edge_afternextnewline": "afterNextNewline()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L2 | neighbors=[edge.js, write(), writeWithContents(), writeWithItems()]
- "runtime_edge_bc": "bc()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L6 | neighbors=[edge.js, te(), Ve(), cs()]
- "runtime_edge_build": "build()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L12 | neighbors=[edge.js, buildCaptureSettings(), getTraceParent(), isEnabled()]
- "runtime_edge_cr": "Cr()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, bo(), toString(), Do()]
- "runtime_edge_de": "de()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, Ca(), fi(), pi()]
- "runtime_edge_emit": "emit()" | kind=code-symbol | source=scratch/generated-client/runtime/edge.js:L1 | neighbors=[edge.js, forEach(), handleAndLogRequestError(), withRetry()]
- "runtime_edge_esm_addfield": "addField()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L3 | neighbors=[edge-esm.js, Io(), mu(), wu()]
- "runtime_edge_esm_afternextnewline": "afterNextNewline()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L2 | neighbors=[edge-esm.js, write(), writeWithContents(), writeWithItems()]
- "runtime_edge_esm_au": "Au()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L4 | neighbors=[edge-esm.js, addSuggestion(), hasField(), hu()]
- "runtime_edge_esm_br": "Br()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L6 | neighbors=[edge-esm.js, as(), e(), ss()]
- "runtime_edge_esm_build": "build()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L12 | neighbors=[edge-esm.js, buildCaptureSettings(), getTraceParent(), isEnabled()]
- "runtime_edge_esm_cl": "cl()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, e(), Pr(), tt()]
- "runtime_edge_esm_da": "Da()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, Pt(), ze(), yi()]
- "runtime_edge_esm_de": "de()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L1 | neighbors=[edge-esm.js, si(), ui(), ya()]
- "runtime_edge_esm_ee": "Ee()" | kind=code-symbol | source=scratch/generated-client/runtime/edge-esm.js:L5 | neighbors=[edge-esm.js, Gt(), N(), os()]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-018.json

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

# Node Description Batch 128 of 151

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

- "pdf_route_default_pdf_settings": "DEFAULT_PDF_SETTINGS" | kind=code-symbol | source=app/api/settings/pdf/route.js:L13 | neighbors=[route.js]
- "pdf_route_get": "GET()" | kind=code-symbol | source=app/api/settings/pdf/route.js:L45 | neighbors=[route.js]
- "pdf_route_post": "POST()" | kind=code-symbol | source=app/api/settings/pdf/route.js:L122 | neighbors=[route.js]
- "postcss_config_config": "config" | kind=code-symbol | source=postcss.config.mjs:L1 | neighbors=[postcss.config.mjs]
- "print_billpdfgenerator_code39_patterns": "CODE39_PATTERNS" | kind=code-symbol | source=lib/offline/print/billPdfGenerator.js:L6 | neighbors=[billPdfGenerator.js]
- "print_openprint_openofflinebillprint": "openOfflineBillPrint()" | kind=code-symbol | source=lib/offline/print/openPrint.js:L37 | neighbors=[openPrint.js]
- "print_openprint_openofflinereportprint": "openOfflineReportPrint()" | kind=code-symbol | source=lib/offline/print/openPrint.js:L11 | neighbors=[openPrint.js]
- "print_reportpdfgenerator_formatdate": "formatDate()" | kind=code-symbol | source=lib/offline/print/reportPdfGenerator.js:L110 | neighbors=[reportPdfGenerator.js]
- "prisma_process_dynamic_parameters_prisma": "prisma" | kind=code-symbol | source=prisma/process-dynamic-parameters.js:L2 | neighbors=[process-dynamic-parameters.js]
- "prisma_process_dynamic_parameters_prismaclient": "{ PrismaClient }" | kind=code-symbol | source=prisma/process-dynamic-parameters.js:L1 | neighbors=[process-dynamic-parameters.js]
- "prisma_seed_bcrypt": "bcrypt" | kind=code-symbol | source=prisma/seed.js:L3 | neighbors=[seed.js]
- "prisma_seed_prisma": "prisma" | kind=code-symbol | source=prisma/seed.js:L2 | neighbors=[seed.js]
- "prisma_seed_prismaclient": "{ PrismaClient }" | kind=code-symbol | source=prisma/seed.js:L1 | neighbors=[seed.js]
- "profile_route_get": "GET()" | kind=code-symbol | source=app/api/profile/route.js:L6 | neighbors=[route.js]
- "profile_route_put": "PUT()" | kind=code-symbol | source=app/api/profile/route.js:L53 | neighbors=[route.js]
- "providers_offlineprovider_offlineprovider": "OfflineProvider()" | kind=code-symbol | source=components/providers/OfflineProvider.jsx:L11 | neighbors=[OfflineProvider.jsx]
- "proxy_config": "config" | kind=code-symbol | source=proxy.js:L33 | neighbors=[proxy.js]
- "proxy_jwt_secret": "JWT_SECRET" | kind=code-symbol | source=proxy.js:L4 | neighbors=[proxy.js]
- "proxy_proxy": "proxy()" | kind=code-symbol | source=proxy.js:L8 | neighbors=[proxy.js]
- "public_sw_createcleanresponse": "createCleanResponse()" | kind=code-symbol | source=public/sw.js:L50 | neighbors=[sw.js]
- "public_sw_extractassetsfromhtml": "extractAssetsFromHtml()" | kind=code-symbol | source=public/sw.js:L30 | neighbors=[sw.js]
- "public_sw_ishtmlresponse": "isHtmlResponse()" | kind=code-symbol | source=public/sw.js:L165 | neighbors=[sw.js]
- "public_sw_precache_routes": "PRECACHE_ROUTES" | kind=code-symbol | source=public/sw.js:L5 | neighbors=[sw.js]
- "public_sw_sanitizeresponse": "sanitizeResponse()" | kind=code-symbol | source=public/sw.js:L61 | neighbors=[sw.js]
- "pwa_pwainstallmodal_getdeviceinfo": "getDeviceInfo()" | kind=code-symbol | source=components/pwa/PWAInstallModal.jsx:L30 | neighbors=[PWAInstallModal.jsx]
- "pwa_pwainstallmodal_pwainstallmodal": "PWAInstallModal()" | kind=code-symbol | source=components/pwa/PWAInstallModal.jsx:L69 | neighbors=[PWAInstallModal.jsx]
- "q_route_get": "GET()" | kind=code-symbol | source=app/(printReport)/q/route.js:L4 | neighbors=[route.js]
- "register_page_metadata": "metadata" | kind=code-symbol | source=app/(customer)/auth/register/page.js:L3 | neighbors=[page.js]
- "register_page_page": "Page()" | kind=code-symbol | source=app/(customer)/auth/register/page.js:L11 | neighbors=[page.js]
- "register_registerpageclient_customerregisterpage": "CustomerRegisterPage()" | kind=code-symbol | source=app/(customer)/auth/register/RegisterPageClient.js:L23 | neighbors=[RegisterPageClient.js]
- "register_registerpageclient_registerschema": "registerSchema" | kind=code-symbol | source=app/(customer)/auth/register/RegisterPageClient.js:L13 | neighbors=[RegisterPageClient.js]
- "register_route_post": "POST()" | kind=code-symbol | source=app/api/authas/register/route.js:L7 | neighbors=[route.js]
- "registration_page_filter": "filter" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L55 | neighbors=[page.js]
- "registration_page_getindiancities": "getIndianCities()" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L74 | neighbors=[page.js]
- "registration_page_getlocalisostring": "getLocalIsoString()" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L60 | neighbors=[page.js]
- "registration_page_indiancities": "indianCities" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L82 | neighbors=[page.js]
- "registration_page_indianstatesmap": "indianStatesMap" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L72 | neighbors=[page.js]
- "registration_page_registrationpage": "RegistrationPage()" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L96 | neighbors=[page.js]
- "registration_page_toutcstring": "toUtcString()" | kind=code-symbol | source=app/(customer)/(dashboard)/registration/page.js:L66 | neighbors=[page.js]
- "registrations_route_generaterandomsuffix": "generateRandomSuffix()" | kind=code-symbol | source=app/api/registrations/route.js:L11 | neighbors=[route.js]

## Instructions

Write a single JSON object mapping each node id to a one-sentence description
to: D:\Atif Bhai\new\components\.graphify\description-instructions\batch-127.json

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

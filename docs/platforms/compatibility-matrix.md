# Compatibility matrix

> Proposed schema and initial public-source inventory; 2026-11-07. **No scores or qualifications.**
> API naming, hardware and local-operation claims are not verified Home Steward compatibility.

| Candidate / role | Bootstrap evidence | Important unresolved boundary | Outcome | Issue |
|---|---|---|---|---|
| [Ghost Core](../research/ghost-core.md) / appliance | Official product/FAQ/privacy; spec tabs advertise 2.5 Gb Ethernet and 205 W max draw | API auth, scope, gateway, memory/export/delete, actual network behavior, platform openness | RESEARCH INCOMPLETE | [#3](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/3) |
| [Auren One](../research/auren-one.md) / appliance candidate | Official pre-launch product / OS claims | Published API/specs, shipped behavior and local governance | RESEARCH INCOMPLETE | [#4](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/4) |
| [MyOtto.ai](../research/myotto-ai.md) / appliance candidate | Official Otto One cloud-inference / future Pro local-cloud docs | Local-only Pro enforcement, app/person scope and mature availability | RESEARCH INCOMPLETE | #4 |
| [NVIDIA DGX Spark](../research/nvidia-dgx-spark.md) / compute | Official hardware/platform docs | Complete household platform and policies not supplied by hardware alone | RESEARCH INCOMPLETE | #4 |
| [ASUS Ascent GX10](../research/asus-ascent-gx10.md) / compute | Official hardware claims | Software/governance/TCO for actual configuration | RESEARCH INCOMPLETE | #4 |
| [MINISFORUM MS-S1 MAX](../research/minisforum-ms-s1-max.md) / DIY control hardware | Official hardware claims | Memory allocation/runtime/software maturity/governance | RESEARCH INCOMPLETE | [#5](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/5) |
| [AnythingLLM](../research/anythingllm.md) / application | Public project docs | Person/source/derived lifecycle and deployment scope | RESEARCH INCOMPLETE | [#5](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/5) |
| [Dify](../research/dify.md) / application | Public project docs | Local components, telemetry, isolation, operational burden | RESEARCH INCOMPLETE | #5 |
| [Open WebUI](../research/open-webui.md) / application | Public project docs | Scope, tools, licensing, derived lifecycle | RESEARCH INCOMPLETE | #5 |
| [MindsHub Cowork / Anton](../research/mindshub-cowork-and-anton.md) / candidate | Vendor docs identify MindsDB-related local server and Anton | Cowork/Agents naming, component licenses, MCP and privacy | RESEARCH INCOMPLETE | #5 |
| [Docker Model Runner](../research/docker-model-runner.md) / inference | Official docs | No complete knowledge platform implied | RESEARCH INCOMPLETE | #5 |
| [Ollama](../research/ollama.md) / inference | Official docs | Local mode/auth exposure/cloud/derived scope | RESEARCH INCOMPLETE | #5 |
| [LM Studio](../research/lm-studio.md) / inference | Official docs | API/admin/licensing/headless operations and scope | RESEARCH INCOMPLETE | #5 |
| [llama.cpp / vLLM](../research/direct-llama-cpp-vllm.md) / inference | Public project docs | Owner-operated retrieval, auth, policies and maintenance | RESEARCH INCOMPLETE | #5 |
| [Build your own](../research/build-your-own-reference-platform.md) / control | Proposed composition, not installed | Five-year TCO includes Owner time and security/integration work | RESEARCH INCOMPLETE | #5 |

## Proposed schema completion

#2 must finalize configuration/version/date, candidate lifecycle, source links/evidence ratings,
per-gate PASS/FAIL/UNKNOWN with rationale, API types/auth, model/context/concurrency, local/egress
policy, source/Person/derived lifecycle, portability/vendor-exit, HA generic interface versus
Home Steward governed fit, TCO/Owner time, conditions and authorized Reference Home entry.

Never record an invented value to fill a cell. A blank capability is unknown, not absent or PASS.
No weighted score until all hard gates pass under the accepted standard.

[#1 baseline](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/1) -> [#2 common standard](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/2).
#3/#4 may gather early; final decisions wait for #2 Owner acceptance. #5 supplies their control.
All five issues remain OPEN; candidate details live in documents, not one new issue per candidate.

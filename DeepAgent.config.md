---
deepagent_config: true
app_name: "Mindful Renewal Path"
env: "production"  # change per environment: development/staging/production
source_of_truth: "obsidian_vault"  # pointer label for UI and ingestion
vault_path: "github.com/you/obsidian-vault"  # optional pointer; do not include auth
ingest_paths:
  - "Library/"
  - "Agents/"
  - "Pages/"
default_project: "mrp-main"
agents_folder: "Agents"
theme:
  primary_color: "#F97316"
  background_color: "#FAFAF9"
  text_color: "#1F2937"
  accent_color: "#F5F0E6"
integrations:
  deepagent:
    provider: "abacus.ai"
    enabled: true
    route_llm_docs: "https://abacus.ai/app/route-llm-apis"
    recommended_runtime: "ROUTE_LLM_API_KEY via env"
    notes: "Use RouteLLM APIs for unified LLM access; select provider at runtime to reduce token costs"
  llm_providers:
    - "route_llm"
    - "openai"
    - "groq"
  payments:
    - "stripe"
  calendar:
    - "calendly"
  repo_sync:
    - "github"
  monitoring:
    - "sentry"
  analytics:
    - "datadog"
sync_hint: "treat_vault_as_source_of_truth"
metrics:
  onboarding_target: "80%_<5m"
  credit_processing_latency_s: 5
  real_time_update_ms: 1000
notes: "Do not store API keys or secrets here. Use env vars or a secret manager. For Abacus DeepAgent, set ROUTE_LLM_API_KEY and DEEPAGENT_API_KEY in secret store."
---
# DeepAgent Sync Config — runtime hints and ingestion paths for DeepAgent
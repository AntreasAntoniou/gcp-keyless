# GCP Keyless

Operate Google Cloud with short-lived identities: attached service accounts inside GCP and GitHub OIDC Workload Identity Federation for reviewed automation.

```bash
npx skills add AntreasAntoniou/gcp-keyless
python3 scripts/doctor.py --repo OWNER/REPO
python3 scripts/validate_workflow.py assets/gcp-keyless-observe.yml
```

The included workflow is read-only and accepts typed operations only. It never creates or uses a service-account key file.

## Test

```bash
python3 scripts/test_gcp_keyless.py
```

MIT licensed.

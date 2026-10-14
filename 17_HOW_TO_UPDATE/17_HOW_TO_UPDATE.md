# How to Update — VAPR_PRIOR_DOCS

**Project:** `VAPR_PRIOR_DOCS`
**Category:** ARTILLERY_MANUFACTURING
**Domain:** artillery manufacturing
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
VAPR_PRIOR_DOCS --version
VAPR_PRIOR_DOCS check-update
```

### Applying Updates
```bash
pip install --upgrade VAPR_PRIOR_DOCS
```

### Rolling Back
```bash
pip install VAPR_PRIOR_DOCS==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.

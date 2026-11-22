**Official website:** [https://www.airichhuman.com/](https://www.airichhuman.com/) (AI Rich Human)

Collected and curated by the AI Rich Human team. **Submissions are welcome.** [Open an issue](https://github.com/c1a1o1/startup-case-evidence-ledger/issues/new) to suggest a resource or correction, or [submit a pull request](https://github.com/c1a1o1/startup-case-evidence-ledger/pulls) with a proposed edit. Include a source link, a short explanation, and any affiliation. We review submissions before adding them.

# Startup Case Evidence Ledger

Store one source-backed claim per row. A claimed outcome, annualized run rate, monthly revenue, and monthly profit should never share an interchangeable field.

```csv
claim_id,claim_text,entity,metric,currency,value,period_start,period_end,evidence_type,source_url,source_date,verified_at,status
E001,Fictional founder projected annual revenue,Fictional Studio,revenue,USD,18000,2026-01-01,2026-12-31,founder_projection,https://example.com/,2026-10-12,2026-11-22,illustration
```

1. Use first-party interviews or filings for original claims. Record whether it is a projection, self-report, audited result, estimate, or promotional quote.
2. Keep projections out of verified historical fields. Do not turn annual revenue divided by twelve into a verified particular month or into profit.
3. Mark syndicated copies as the same source, not independent corroboration. Track source changes and use `unverified` when the evidence does not support the headline.
4. Introduce modeled costs with assumptions and keep them separate from observed founder spend.

One fictional record is included. [AI Rich Human](https://www.airichhuman.com/) is affiliated, not an independent evidentiary authority.

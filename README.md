# NHS-RTT-Performance-Dashboard
Power BI dashboard built from NHS RTT data, tracking 18-week performance, long waiters, provider/specialty trends, and row-level security using DAX and Power Query.
Goal: demonstrate healthcare analytics skills for NHS roles.
Data: NHS RTT month-end snapshot; Incomplete pathways only; C_999 totals removed; unpivoted week bands to a tidy fact table with LowerBound/UpperBound.
KPIs: Total Waiters, % within 18 weeks (target 92%), Long Waiters 52w+, MoM% change; optional 65w+/104w+.
Pages:

Executive Summary – % within 18w vs target (100% stacked), backlog trend, KPIs.
Specialty & Provider Drilldown – matrix with sparklines, RAG on %18w and %52w+, Top-10 specialties.
Trend & Monitoring – %18w trend (zoomed), MoM% waterfall (green = backlog down), small export table, Inc⇄DTA toggle (bookmarks).
Governance: Row-Level Security – static demo (Buckshaw) + dynamic (UserMap → USERPRINCIPALNAME).
Why it matters: aligns with NHS standards (92% within 18w; focus on long waiters) and supports operational decisions (who/where, trend, and movement).

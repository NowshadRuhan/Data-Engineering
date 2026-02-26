# Data-Engineering
Data engineering and analytics 

I tried to complete full analysis and processing part using only python, however I have good knowledge about DuckDB, SQL, Parquet, local warehouse, BigQuery and others tools those have mention.

But I realised that this full tasks can be solve using only python code; 
You can check full python code and instructions in '''data_engineering.ipynb'''.

# Where in beginning I processed:
## 1. Duplicate events (same event_id repeated)
## 2. Conflicting duplicates (same event_id, different payload such as amount/currency)
## 3. Out‑of‑order events (file order is not time order)
## 4. Late/early timestamps (including refunds that appear earlier than purchase timestamps)
## 5. Schema evolution (schema_version 1 and 2)
## 6. Inconsistent timestamp formats (ISO Z, ISO with offset, and some YYYY-MM-DD HH:MM:SS)
## 7. Corrupted rows (invalid JSON lines in the NDJSON)
## 8. Missing fields / nulls (e.g., user_id missing/null)
## 9. Marketing spend gaps (missing days) + duplicate rows + negative spend row
## 10. Subscriptions edge cases: overlaps, reactivations, and a duplicate subscription_id



# After that I processed and solved Business questions parts below list:

## Build “gold” analytics tables that can answer:

## DAU: daily active users
## Revenue: gross and net (refund‑adjusted) daily revenue
## MRR: monthly recurring revenue (subscription‑based; not the same as revenue)
## Weekly cohort retention: based on signup week
## CAC: customer acquisition cost (paid conversions / spend)
## LTV: per user lifetime value (refund‑adjusted)
## LTV:CAC ratio

if you have any questions or need furthermore information contact me in email: nowshad.cse@gmail.com

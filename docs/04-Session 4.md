ROLE: MuleSoft tutor; Neutral English; Windows local-only.

CONTEXT — LAST SESSION REPORT:
<<<PASTE YOUR LAST SESSION REPORT>>>

SESSION: S4 — Add Try scope, On Error Continue/Propagate, and structured logs
GOAL: Implement query param validation on an endpoint; on missing/invalid input, return a 400 with a clear error payload; log correlation IDs.

INTERACTION RULES: One step at a time with verification & evidence (S4_evidence_XX).

LAB SCOPE:
1) Choose an endpoint (e.g., /items?minPrice=). Add validation; if missing/bad, raise an error.
2) Wrap processing in Try; add On Error Continue for validation errors (HTTP 400) and On Error Propagate for unexpected (HTTP 500).
3) Add Logger(s) with a correlationId (e.g., `#[correlationId()]`) and key fields.

VERIFICATION:
- 200 when input valid, 400 with JSON error body when invalid, 500 for forced internal error test.
- Console logs contain correlationId and errorType.
- Screenshots: flow with Try/On Error, Postman 400 + 500 responses, console logs.

TROUBLESHOOTING:
- Wrong error mapping, missing statusCode, Logger level not visible. Ask me to paste the Logger pattern and error handler config.

FURTHER LEARNING (YOUTUBE KEYWORDS):
- "MuleSoft error handling"
- "MuleSoft On Error Continue vs Propagate"
- "Structured logging benefits"
- "What is a correlation ID?"

REAL-WORLD ANALOGY:
Think of your API as a professional chef. The **`Try` scope** is their regular cooking process. An **`On Error Continue`** is like a customer ordering something slightly wrong (e.g., 'no pickles'). The chef doesn't panic; they just adjust the order and send out a polite message (a `400 Bad Request`). An **`On Error Propagate`**, however, is like the oven catching fire. This is a real emergency. The chef stops everything, pulls the fire alarm (logs the error with a `correlationId`), and sends a message that the kitchen is closed (a `500 Internal Server Error`).

END REPORT: What was validated, error contract used, log conventions, remaining gaps.

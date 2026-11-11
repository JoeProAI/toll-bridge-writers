# Toll Bridge demo writers (DEMO, PayPal sandbox only)

Four fictional writers with RSL 1.0 license files, used by [Toll Bridge](https://github.com/JoeProAI/toll-bridge). Site: https://joeproai.github.io/toll-bridge-writers/

| Page | License | Payee (PayPal sandbox Personal account) |
|---|---|---|
| a.html | pay per use, $0.05 | sb-3j1ps53857892@personal.example.com |
| b.html | pay per use, $0.05 | sb-o9xx453857673@personal.example.com |
| c.html | prohibits all AI use | none |
| d.html | pay per use, $0.05 (page hides a prompt injection) | sb-3j1ps53857892@personal.example.com (shares writer A's sandbox account) |

The payee block uses `<accepts type="application/vnd.tollbridge.paypal-payout+json">`, Toll Bridge's own proposed media type (RSL allows payment systems to define their own). It is not part of RSL or PayPal. All writers, names and numbers are made up. No real money moves.

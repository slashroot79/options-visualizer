# Options, Explained Simply 📈

A free, **interactive, beginner-friendly** web tool to *finally* understand stock options — with zero jargon. Everything runs 100% in your browser; no data leaves your device.

> ⚠️ **Educational only — not financial advice.** Numbers are simplified for teaching (they ignore time value, commissions, taxes, and exact broker margin rules). Options involve substantial risk. Always do your own research.

## What's inside

1. **Payoff diagrams** — pick any position (buy/sell call, buy/sell put, covered call), drag the stock price, and watch profit/loss, breakeven, max profit, and max loss update live. Shows ITM / ATM / OTM as you go.
2. **The clearinghouse (OCC) chain** — click through a growing, row-by-row ledger that shows how a single contract changes hands (Alice → You → Carol → Dave), for **both calls and puts**, and how **covered vs naked** writers are affected at assignment.
3. **Margin-call simulator** — take a *naked* short, then drag the stock against yourself and watch the danger stages light up: **Healthy → Warning → Margin call → Liquidation → You owe (debt)**.
4. **Bid / Ask / Mid / Last** — a live quote widget plus a plain-English explanation, including the myth-buster that the **OCC does not set prices** (the market does).

## How to use

Just open the live site (or `index.html`) in any modern browser — desktop or mobile. Drag the sliders, flip the toggles, and click **Next step**. That's it.

## Run locally

```bash
# from this folder
python -m http.server 8000
# then open http://localhost:8000
```

## Concepts covered

Calls & puts · buying (long) vs selling (writing/short) · sell-to-open vs sell-to-close · premium, strike, expiration · exercise & assignment · covered vs naked · the OCC / clearinghouse · margin & margin calls · ITM/ATM/OTM · bid/ask/mid/last/spread.

---

Built to make options click. Contributions and suggestions welcome.

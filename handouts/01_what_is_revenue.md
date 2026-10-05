# 18BI · Week 1 — What was our revenue?

> Printable version: [`01_what_is_revenue.pdf`](01_what_is_revenue.pdf)

**On your own. Ten minutes. Pen and paper — no laptops, no phones.**

You are the analytics team. The CEO wants one number: **what was our revenue?** Below is everything the company's systems will give you. Work out an answer, and write down the rule you used.

## `orders` — order lines

| order | line | product | qty | unit price (net) | discount | shipping | VAT | status |
|---|---|---|---:|---:|---:|---:|---:|---|
| O-1 | 1 | Running shoes | 2 | 1 000 | 0 | 100 | 21% | completed |
| O-1 | 2 | GPS watch | 1 | 3 000 | 500 | 100 | 21% | completed |
| O-2 | 1 | Wetsuit | 1 | 5 000 | 0 | 0 | 21% | completed |
| O-3 | 1 | Trail shoes | 3 | 1 000 | 300 | 100 | 21% | CANCELLED |
| O-4 | 1 | Bike helmet | 1 | 2 000 | 0 | 100 | 21% | completed |
| O-5 | 1 | Goggles | 2 | 1 500 | 0 | 150 | 21% | PENDING |
| O-6 | 1 | GPS watch | 1 | 4 000 | 0 | 100 | 21% | completed |

## `refunds` — booked separately, days later

| refund | order | booked | amount (net) | reason |
|---|---|---|---:|---|
| R-1 | O-4 | three weeks later | 2 000 | damaged |

## Notes from the systems team, such as they are

* **unit price (net)** excludes VAT. The product catalogue stores prices *including* VAT.
* **shipping** is charged once per order, and repeated on every line of that order.
* Cancelled and pending orders stay in the table. Nothing is ever deleted.
* Refunds are not subtracted anywhere. They live in their own table.

---

**Our revenue was ________________ CZK**

**because I counted:** _______________________________________________

**and I excluded:** _________________________________________________

**Finished early?** Look at your neighbour's number. If it differs from yours, can you prove one of you wrong — or can you only disagree?

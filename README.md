# London VPS hosting: what Akkocloud charges, is the server really in London, and which plan do you need? (full price table)

Akkocloud's London entry plan costs **¥449 a year**, about US$5.60 a month, for 1 vCPU and 1 GB of RAM on China Telecom's CN2 GIA route. That annual special is the tier most readers should start with. Monthly billing on the same London line begins at **¥129.99 (about US$19.44)** for 1 vCPU and 2 GB, which is several times what an ordinary London VPS costs. The gap tells you what you are actually buying here: routing into mainland China, not raw RAM.

Below are the eight London plans currently listed, the geography check that separates a real London data centre from a "London" marketing label, and the places where Akkocloud's published information runs out and you need to ask before paying.

> **Quick pick:** the KVM-CN2-A2 mini annual special at ¥449/year is the cheapest way onto Akkocloud's London network. It suits a small site or a lightweight service whose users are in China. If your visitors sit in the UK or the EU, read the cost section first; a plain London VPS starts at $3.99–$10 a month elsewhere.
>
> 👉 [Check the current London annual special](https://bit.ly/akkocloud)

## The full Akkocloud London plan list

Prices are the CNY figures from Akkocloud's order table as mirrored by a plan tracker in October 2026. Dollar amounts are that tracker's conversion at the time and will drift with the exchange rate.

| Plan | vCPU / RAM | Price | Billing | Order |
| --- | --- | --- | --- | --- |
| KVM-CN2-A2 mini (annual special) | 1 vCPU / 1 GB | ¥449 (~US$5.60/mo) | Annual | [Order the A2 annual special](https://bit.ly/akkocloud) |
| KVM-CN2-B1 mini (annual special) | 1 vCPU / 1 GB | ¥699 (~US$8.71/mo) | Annual | [Order the B1 mini annual](https://bit.ly/akkocloud) |
| KVM-CN2-B1 | 1 vCPU / 2 GB | ¥129.99 (~US$19.44) | Monthly | [Order the B1 monthly plan](https://bit.ly/akkocloud) |
| KVM-CN2-B2 | 1 vCPU / 2 GB | ¥299.99 (~US$44.87) | Monthly | [Order the B2 monthly plan](https://bit.ly/akkocloud) |
| KVM-CN2-C1 | 1 vCPU / 2 GB | ¥459.99 (~US$68.80) | Monthly | [Order the C1 monthly plan](https://bit.ly/akkocloud) |
| KVM-CN2-D1 | 2 vCPU / 4 GB | ¥699.99 (~US$104.69) | Monthly | [Order the D1 monthly plan](https://bit.ly/akkocloud) |
| KVM-CN2-E1 | 4 vCPU / 8 GB | ¥1,049.99 (~US$157.04) | Monthly | [Order the E1 monthly plan](https://bit.ly/akkocloud) |
| KVM-CN2-F1 | 4 vCPU / 8 GB | ¥1,399.99 (~US$209.38) | Monthly | [Order the F1 monthly plan](https://bit.ly/akkocloud) |

Three things the listing does not give you, and you should treat as gaps rather than assume away:

- **Disk size and monthly traffic are not shown for the London plans.** The tracker records storage type as unknown across all eight. Do not extrapolate from the San Jose plans; they are a different product line.
- **Two trackers disagree on the ¥449 annual special.** One lists 1 GB of RAM and a 1 Gbps port; another lists 768 MB and 300 Mbps for the same ¥449/year price. The B1 mini at ¥699 is listed consistently as 1 vCPU / 1 GB / 1 Gbps in both.
- **Port speed is listed as 1 Gbps on every London plan**, including the annual specials, which is unusual at this price and worth confirming on the order page.

## Why three 1 vCPU / 2 GB plans cost ¥129.99, ¥299.99 and ¥459.99

The only visible difference between B1, B2 and C1 is the letter in the name. Nothing in the CPU or RAM column changes across a 3.5× price range, so whatever you are paying for sits in the bandwidth allocation, the monthly traffic cap, or the route grade attached to that letter. The tracker does not record those fields.

That is the single most important thing to resolve before you upgrade past B1. Open the order page, read the traffic and bandwidth lines for B2 and C1, and decide whether the difference matters to your workload. Paying an extra ¥330 a month for the same 2 GB of RAM, with no idea what the extra buys, is the most expensive mistake available on this page.

## Is the server actually in London?

For Akkocloud, the evidence points to a real London presence. The London plans are listed as GB/United Kingdom, and the same brand sells London dedicated servers (dual EPYC 7552, 512 GB RAM, 10×1TB SSD at ¥33,000/month), which is not something a pure reseller typically offers. What is not published is a street address or a specific Tier certification for the London VPS location; the strongest claim available is a "T3+ grade data centre standard" from a provider directory.

That matters because "London VPS" gets used loosely across this market, and the label hides two very different products:

- **The data centre is in London.** EDIS Global publishes a full postal address (Digital Realty, Meridian Gate, E14 9FJ) and a London looking glass. OliveVPS and AllHost both run out of Telehouse in Docklands.
- **The data centre is elsewhere in the UK, with low-latency routes into London.** EUGameHost titles its page "London VPS" and states plainly in the same paragraph that the server sits in its own UK data centre with low-latency routes into London and the South East. That facility is in Norwich.

Both can be legitimate products. They are not the same product, and only one of them gives you a box inside the M25. For latency-sensitive work, test before you buy: ping a published test IP from the network your users are on, or run a traceroute and watch where the hops land. EDIS explicitly recommends this, and it takes two minutes.

## The real cost: annual specials, monthly billing, and year two

The two annual specials are where the value sits. ¥449 a year works out to ¥37 a month, against ¥129.99 a month for the cheapest monthly plan. Even allowing for the smaller configuration on the specials, the annual route is a fraction of the monthly route.

The trade-off is that you prepay twelve months to a provider whose refund terms I could not verify in any published source. Whether the ¥449 rate survives renewal is also unpublished. Two questions for the cart or a pre-sales ticket: what happens to the price at renewal, and what is the refund window if the route performs badly from your location.

👉 [Start with the ¥449 London annual plan](https://bit.ly/akkocloud)

## What Akkocloud does not publish

Support is Chinese-language tickets, with a stated commitment of a reply within 24 hours and resolution within 48 hours, plus a Telegram community. That is a different shape from the 24/7 phone lines some London hosts advertise, and it is worth knowing before you buy rather than after.

The brand dates itself to 2019 and runs London, Frankfurt and San Jose locations on KVM, with Alipay among the payment options. Payment method matters here: a CNY-priced product with Alipay support is built for a Chinese-facing customer, and that is consistent with everything else about the London line.

## The limits other London hosts bury in the FAQ

Reading competitor small print tells you what to ask Akkocloud. None of the following is confirmed to apply to Akkocloud; it is the checklist of things London VPS providers commonly restrict.

- **AllHost** blocks port 25 unless you prepay three months or more on an account in good standing, charges a minimum of £5.00 per IP change, and describes its Corero DDoS mitigation as best-effort. Refund window is 72 hours, and VPS services are excluded from its 30-day shared hosting policy.
- **OliveVPS** charges $0.005/GB for overage traffic, offers a 7-day no-questions refund, and restricts its $3.99 Starter plan to Linux only.
- **EDIS Global** requires a full shutdown and restart for RAM, vCPU or storage changes, caps expansion at 8 vCPU / 24 GB, and prices storage boosts from €3.60/month.
- **EUGameHost** offers a 48-hour money-back guarantee.

Ask Akkocloud the same four questions: Is port 25 open? What does an extra IPv4 cost? Is traffic metered, and at what overage rate? Does a RAM upgrade need a reboot?

## How Akkocloud compares with London hosts that do not optimize for China

| Provider | London location | Entry price | Refund window |
| --- | --- | --- | --- |
| Akkocloud | London, UK (no street address published) | ¥449/yr (~US$5.60/mo) | Not published |
| Proton Servers | London, Tier III facility | $10/mo (1 vCore / 2 GB / 25 GB NVMe, unmetered 1 Gbps) | Not published |
| OliveVPS | Telehouse North, Docklands | $3.99/mo (1 vCPU / 1 GB / 25 GB, Linux only) | 7 days |
| AllHost | Telehouse London | £4.29/mo (1 vCore / 1 GB / 18 GB / 5 TB) | 72 hours |
| EDIS Global | Digital Realty, E14 9FJ | €4.99/mo (1 vCPU / 1 GB / 15 GB / 1 TB, 2×10 Gbps) | Not published |
| EUGameHost | Own UK data centre in Norwich | £5.99/mo (2 vCPU / 4 GB / 60 GB, 5 Gbps unmetered) | 48 hours |

AllHost's page carries a 2024 date, so treat its pricing as historical. It also contradicts itself on memory type between the plan cards and the technical section, and Proton Servers contradicts itself on Intel versus AMD Ryzen 9 hardware in the same page. Neither is reliable as a spec reference.

The pattern is clear enough. If you want the most RAM per dollar inside London, Akkocloud is not the answer; Proton Servers gives you 2 GB for $10 a month, and OliveVPS undercuts that further. Akkocloud's prices only make sense when the China route is the point.

## Who should not buy this

- **Your users are in the UK or the EU.** You would pay a routing premium for a path you never use. Proton Servers, OliveVPS, AllHost and EDIS all beat Akkocloud on price per gigabyte inside London.
- **You need a published refund policy before you commit.** Three of the five competitors above publish one; Akkocloud's is not in any source I could verify.
- **You need 24/7 phone support.** Akkocloud's published support commitment is ticket-based, in Chinese, with a 48-hour resolution target.
- **You want a documented street address for the facility.** EDIS publishes one. Akkocloud does not.

## Which plan to pick

- **A small personal site or a lightweight service with Chinese users** → the ¥449/year A2 special. Confirm whether it is 768 MB or 1 GB before paying; two trackers disagree.
- **Same use case, want a consistent spec** → the ¥699/year B1 mini, listed as 1 vCPU / 1 GB / 1 Gbps across both trackers.
- **A production app that needs monthly flexibility** → the ¥129.99 B1. Do not jump to B2 or C1 until you have read what the extra ¥170–330 a month actually buys.
- **4 vCPU / 8 GB** → E1 at ¥1,049.99 is the entry point. F1 at ¥1,399.99 has the same CPU and RAM, so the ¥350 difference is bandwidth or traffic, and you should know which before choosing.

Four things to confirm in the cart before you pay: the RAM on the ¥449 plan, the monthly traffic allowance, the renewal rate for year two, and the refund window. If any of those answers is unsatisfactory, you have lost nothing but a few minutes.

👉 [Open Akkocloud's London plan list and confirm current stock](https://bit.ly/akkocloud)

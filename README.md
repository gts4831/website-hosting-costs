# website hosting cost: real prices by hosting type, the renewal trap most guides skip, and when a $12/year VPS beats $10/month shared hosting

Website hosting cost depends less on brand than on hosting type, and the spread is enormous: roughly **$12 a year** at the bottom, **$500+ a month** at the top. Shared hosting for a small site sits around $2–10/month. Managed WordPress climbs to $25–200/month once a site outgrows shared servers. VPS hosting is usually quoted at $10–100/month, but at budget providers that bill annually, a full KVM VPS works out to $1–4/month. That last number is the one most cost guides never mention.

RackNerd is why that number exists. It's a Los Angeles-based VPS provider, around since 2019, selling KVM virtual servers from **$8.99/year** — about 75 cents a month — with RAM and CPU reserved for your account instead of split across hundreds of sites. What you don't get: a site builder, one-click installers, cPanel, or anyone managing the server for you.

This guide covers both halves of the question: what each hosting type actually costs once renewals kick in, and where a $12-a-year VPS makes sense. Where it doesn't, I'll say so.

> **Short version:** for most personal and small-business sites, the **2GB KVM VPS at $19.99/year** (about $1.67/month) is the sweet spot, with enough RAM for WordPress plus headroom. Tightest budget: 1GB at $11.99/year. If you'd rather never open a terminal, budget for managed hosting instead — a VPS will cost you evenings.
>
> [👉 Check RackNerd's current KVM VPS deals](https://bit.ly/my-rn)

## What website hosting actually costs, by hosting type

For a typical small website, plan on $2–50 a month, depending on how much server work you outsource. Current published pricing across mainstream hosts looks like this:

| Hosting type | Typical monthly price | Who runs the server | Best for |
| --- | --- | --- | --- |
| Shared | $2–10 (renews $8–15) | Host | First sites, blogs, low traffic |
| Managed WordPress | $25–200 | Host | Business WordPress sites |
| Website builder | $15–50 | Platform | DIY brochure sites, zero admin |
| VPS / cloud | $10–100 | You | Developers, custom apps |
| Dedicated | $80–500+ | You or managed | High-traffic, strict requirements |
| RackNerd KVM VPS | $0.75–47 effective (billed yearly) | You | Anyone comfortable with Linux |

Two details in that table shape your real bill more than the sticker. Shared hosting's comfort zone tops out around 30,000 visits a month; beyond that you're pushed into managed or VPS territory. RackNerd's plans have no visit cap, just a monthly transfer quota (2TB on the 2GB plan, for scale). Also, the cheapest advertised shared rates usually require prepaying 12–48 months up front, and longer commitments can cut the headline rate by up to 80%. Which brings up the trap.

## The renewal trap, and the hosting type it skips

The monthly price you sign up at is often not the monthly price you'll pay. Shared hosting advertised at $3/month commonly renews at $8–15/month. Managed WordPress that starts at $25 can renew above $40. A typical three-year arc: a $3/month shared deal totals about $276, a $20/month builder plan runs $720, and managed WordPress renewing at $40 adds up to roughly $1,260.

> RackNerd's promotional VPS pricing renews at the same rate you signed up with, for the life of the service. Deals ordered years ago still renew at their original price, which is why the intro-vs-renewal math above mostly doesn't apply here.

That one policy changes the whole comparison. With most hosts you're weighing an intro price against a renewal price; with RackNerd there's only one price.

[👉 See RackNerd's current VPS rates](https://bit.ly/my-rn)

## RackNerd KVM VPS plans and prices (full lineup)

RackNerd's core product is its KVM VPS line: 13 plans spanning 768MB to 64GB of RAM, all with full root access, a dedicated IPv4 address, and a 1Gbps network port. Headline pricing is annual; some plans can be billed monthly at a higher rate, but annual is where the value lives.

| Plan | vCPU | Storage | Transfer/mo | Annual price | Order |
| --- | --- | --- | --- | --- | --- |
| 768MB KVM | 1 | 10 GB SSD | 500 GB | $8.99 | [ Order](https://bit.ly/my-rn) |
| 1GB KVM | 1 | 15 GB SSD | 1 TB | $11.99 | [ Order](https://bit.ly/my-rn) |
| 2GB KVM | 2 | 25 GB SSD | 2 TB | $19.99 | [ Order](https://bit.ly/my-rn) |
| 3GB KVM | 2 | 40 GB SSD | 3 TB | $29.99 | [ Order](https://bit.ly/my-rn) |
| 4GB KVM | 2 | 55 GB SSD | 4 TB | $39.99 | [ Order](https://bit.ly/my-rn) |
| 6GB KVM | 3 | 80 GB SSD | 5 TB | $59.99 | [ Order](https://bit.ly/my-rn) |
| 8GB KVM | 4 | 110 GB SSD | 6 TB | $79.99 | [ Order](https://bit.ly/my-rn) |
| 12GB KVM | 5 | 160 GB SSD | 7 TB | $109.99 | [ Order](https://bit.ly/my-rn) |
| 16GB KVM | 6 | 220 GB SSD | 9 TB | $149.99 | [ Order](https://bit.ly/my-rn) |
| 24GB KVM | 7 | 330 GB SSD | 10 TB | $219.99 | [ Order](https://bit.ly/my-rn) |
| 32GB KVM | 8 | 450 GB SSD | 12 TB | $289.99 | [ Order](https://bit.ly/my-rn) |
| 48GB KVM | 10 | 650 GB SSD | 14 TB | $419.99 | [ Order](https://bit.ly/my-rn) |
| 64GB KVM | 12 | 900 GB SSD | 16 TB | $559.99 | [ Order](https://bit.ly/my-rn) |

Before picking a row:

- **Seasonal specials shuffle the specs.** Black Friday and New Year deals tweak storage and bandwidth slightly and sometimes shave a few dollars off. The order page shows the exact numbers for the deal you're buying.
- **Renewals stay flat.** The price in the table is the renewal price.
- **Location is your call.** At checkout you pick a datacenter — US options typically include Los Angeles, San Jose, Seattle, Dallas, Chicago, New York and Atlanta, with Amsterdam covering Europe. Choose whichever is nearest your visitors.
- **You choose the OS.** Ubuntu, Debian, AlmaLinux and Rocky can be reinstalled from the control panel in a couple of minutes, and custom ISOs are supported if you need something unusual.

RackNerd also sells dedicated servers and colocation, quoted case by case. Neither matters for a typical website; the VPS line is where their pricing is genuinely unusual.

## What RackNerd's price doesn't include

The annual fee buys hardware and network. Everything that makes mainstream hosting feel easy is on you:

- **OS updates and security hardening.** Patches, firewall, brute-force protection — your job.
- **The web stack.** Install nginx or Apache yourself, or bolt on a free panel like HestiaCP or CloudPanel if you want a graphical layer.
- **SSL.** Free with Let's Encrypt; setup takes a few minutes with certbot.
- **Backups.** Nothing automatic. Schedule your own dumps to external storage.
- **Email.** Don't run mail on a budget VPS; IP reputation makes it a headache. Google Workspace at $7/user/month or Microsoft 365 from $6/user/month is the sane route.

Support runs around the clock via tickets, and hardware, network or host-node problems are their side of the fence. Your server's software is not.

Who shouldn't buy this: if you want to click "install WordPress," get a dashboard, and email support when something breaks, shared or managed hosting will cost more per month and save you hours. If your entire site is a static landing page, a builder plan with hosting bundled is less work. And if you've never used SSH, the $1-a-month plans are honestly a decent place to learn — mistakes are cheap at that price.

## What a small website really costs in year one and year two

Here's the full bill for a small business site on RackNerd's 2GB plan, with nothing hidden:

| Item | Cost |
| --- | --- |
| 2GB KVM VPS (annual) | $19.99 |
| .com domain | $10–15 (watch first-year $0.99 promos that renew at $15–20) |
| SSL certificate | $0 (Let's Encrypt) |
| Email (optional, 1 Workspace user) | $84/year |
| **Total, no paid email** | **~$30–35** |
| **Total, with email** | **~$115** |

Year two costs the same, because the VPS renews at signup price and the domain renews at its standard rate. Compare that with shared hosting in its renewal years at roughly $120/year for hosting alone, builder plans around $240/year, or managed WordPress at $300–600/year — all before domains and email.

Capacity-wise, 2TB of monthly transfer handles several hundred thousand cached pageviews of a normal text-and-image site. Self-hosted video is the one thing that burns through that fast; embedding from YouTube or Vimeo sidesteps the problem entirely.

The honest caveat: your time is part of the bill. Expect one evening of setup and occasional maintenance later. If that trade isn't worth saving $100+ a year, managed hosting is the rational buy.

[👉 Order the 2GB KVM annual plan](https://bit.ly/my-rn)

## How RackNerd compares to shared and managed hosting

Side by side, based on currently published pricing:

| Option | Realistic yearly cost | Resources | Renewal behavior |
| --- | --- | --- | --- |
| Budget shared hosting | ~$36 first term, then ~$120 | Shared; ~30K visits/mo comfort zone | Often 2–3× the intro price |
| RackNerd KVM VPS | $9–45 (annual) | Dedicated RAM/CPU, multi-TB transfer | Same as signup |
| Managed WordPress (Kinsta, WP Engine tier) | $300–1,200+ | WP-tuned, host-managed | Flat but high |
| Website builder | $180–600 | Bundled platform | Usually flat |

Each option wins somewhere. Builders are hard to beat for a brochure site you never want to think about. Shared hosting is the low-effort cheap start, as long as you budget for the renewal jump. RackNerd wins on cost per resource and renewal stability, provided you can run a server or are willing to learn.

## FAQ

### Is a $1-a-month VPS actually usable?

Yes, with expectations set correctly. The 1GB plan runs a cached WordPress site, a small API, a staging environment, or a personal project without trouble. Problems start when you pile a database, mail server and control panel onto the 768MB plan; that combination wants 2GB or more.

### Do RackNerd prices go up at renewal?

No. Promotional VPS plans renew at the price you paid, and that has held for deals bought years ago. It's the single biggest difference from mainstream shared hosts, where renewals commonly double.

### Can I run WordPress on RackNerd?

Yes. Install it manually on a LEMP stack or through a free panel. The 2GB plan is comfortable for one or two WordPress sites with a caching plugin, and 1GB handles a single cached site fine.

### How do I pay, and where are the servers?

Checkout accepts PayPal and major credit cards. Datacenter options cover several US cities plus Amsterdam, and you choose the location during the order process — pick the one nearest your audience.

## Which RackNerd plan fits your site

- **Personal blog, portfolio, Linux practice box:** 1GB KVM at $11.99/year. The 768MB plan at $8.99 works for a truly minimal site or a learning sandbox.
- **Small business site, one or two WordPress installs:** 2GB KVM at $19.99/year. This is the plan most people should buy.
- **WooCommerce or a site with steady traffic:** 4GB KVM at $39.99/year, moving up to 6GB if the store grows.
- **Want zero server work:** don't buy a VPS. A builder or managed plan fits better, and pretending otherwise just costs you weekends.

Before ordering, confirm two things: the datacenter list on your specific deal's order page (locations vary a little by promotion), and that annual billing suits you, since that's the entire basis of the pricing. Check the exact storage and transfer on your deal too, because specials shuffle those numbers slightly.

[👉 Order your RackNerd VPS](https://bit.ly/my-rn)

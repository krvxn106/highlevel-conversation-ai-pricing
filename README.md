# HighLevel Conversation AI Pricing: How Token Billing, the $50 Growth Plan and the $97 Unlimited Plan Compare Per Sub-Account

Ask four agency owners what Conversation AI costs in HighLevel and you'll get four answers: "it's two cents a message", "it's free with my plan", "it's $97 per client", and "it's whatever my wallet says at 2am". Two of those answers are out of date, and the other two are only true in specific situations.

The confusion isn't the owners' fault. HighLevel Conversation AI pricing has moved from a flat per-message rate to token-based billing, and it's charged per enabled location rather than per agency. So the price you pay depends on two things most comparison posts skip: which billing model is active on that sub-account, and how many sub-accounts are switched on.

Here's what each route actually costs, where the numbers get uncomfortable, and what a third-party Conversation AI layer like CloseBot costs when the built-in option stops making sense.

## Three billing models, not one price

HighLevel documents three ways to pay for its AI products, and Conversation AI sits in all three.

| Plan | Price | Conversation AI | What else comes bundled |
| --- | --- | --- | --- |
| Pay-Per-Use | No monthly AI subscription fee | Billed at token cost; the Prompt Optimizer gives 100 messages/day before token billing kicks in | Nothing bundled |
| AI Employee Growth | $50/month per enabled location | 1,000 agent responses per month, then pay-per-use rates | 100 Voice AI agent minutes/month, unlimited Reviews AI and Content AI, 100 Voice AI Prompt Optimizer minutes, 100 Managed Agent runs |
| AI Employee Unlimited | $97/month per enabled location | Unlimited, subject to fair-use terms | Unlimited Voice AI (inbound, outbound and widget) subject to fair use, unlimited Reviews and Content AI, 3x Ask AI and AI Studio usage, 1,000 Managed Agent runs |

Two details in that table matter more than they look.

First, **per enabled location**. Not per agency, not per conversation, per sub-account that has AI switched on. Ten clients with AI enabled on the Unlimited plan is $970 a month before your own subscription.

Second, Agent Studio is **not** included in any of those plans. It stays pay-per-use across Pay-Per-Use, Growth and Unlimited, which is an easy line to miss when you're budgeting on the $97 headline.

Your HighLevel subscription is separate from all of it. Agency Starter is $97/month with three sub-accounts, Agency Unlimited is $297/month with unlimited sub-accounts, and the $497/month plan is the one that unlocks SaaS mode. That last tier also matters for a reason covered further down: rebilling AI Employee usage to clients requires the $497 plan.

## What pay-per-use actually charges, token by token

Older guides, and plenty of recent ones, still quote a flat rate around $0.02 per AI message. That was the old model. HighLevel's current pricing documentation bills Conversation AI by model token consumption, with published rates per million tokens.

| Model | Input price / 1M tokens | Output price / 1M tokens |
| --- | --- | --- |
| GPT-5 | $1.25 | $10.00 |
| GPT-5 Mini | $0.25 | $2.00 |
| GPT-4.1 | $2.00 | $8.00 |
| GPT-4.1 Mini | $0.40 | $1.60 |

Cost is calculated in two parts. Input tokens cover everything sent to the model: the customer's message, the conversation history, your AI instructions, contact details and knowledge-base content. Output tokens cover what the AI writes back. Add them together and that's your charge.

HighLevel's own worked example: a conversation using 100,000 input tokens and 25,000 output tokens on GPT-5 pricing lands at $0.375. That's an intentionally heavy example, because 100,000 input tokens is a lot of text moving through a chat. Shorter conversations cost proportionally less, and that's the point worth internalising: two conversations at the same company, on the same bot, on the same day can cost different amounts. More back-and-forth, longer replies, a bigger knowledge base being pulled into context, all of it changes the bill.

The bigger cost driver on pay-per-use isn't the per-conversation rate. It's that token billing is hard to forecast. A wallet that looks comfortable in a quiet month can look very different when a campaign lands and 60 conversations turn into 400.

> One number that stays fixed regardless of billing model: phone system charges. Calls and SMS are billed separately, so a location on AI Employee Unlimited can still generate phone costs without the AI plan itself being metered by the minute.

## When $97 per sub-account stops being the cheap option

The logic for AI Employee Unlimited is straightforward. A sub-account running Conversation AI in auto-pilot at any real volume will spend more than $97 a month on tokens, so the flat fee buys predictability and throws in Voice AI. For a single clinic fielding a few hundred inbound texts a month, that's a reasonable trade.

The problem is scale. Unlimited is priced per location, so the bill grows in a straight line: 4 locations, $388/month. 10 locations, $970. 25 locations, $2,425.

CloseBot's own comparison post works through what that looks like at 102 sub-accounts: $9,894/month on AI Employee Unlimited, versus $809/month for their stack including the base plan, message costs and OpenAI token costs. That's vendor math, not a neutral audit, and CloseBot's per-message rates have since changed. But the arithmetic point holds no matter whose tool sits on top: at 100 locations, per-sub-account AI pricing dominates the budget, and anything billed per message starts to look structurally different.

If you're in the middle of that range, run the comparison against pay-per-use before defaulting to Unlimited. CloseBot's own write-up concedes that in one of its two examples, HighLevel's pay-per-use Conversation AI came out *cheaper* than their stack at low volume; the gap appeared at scale. Neither model wins universally.

## Where CloseBot fits: a per-message layer instead of per-location

CloseBot is a conversational AI platform built for sales qualification and appointment booking, with native integrations for HighLevel, HubSpot, LeadConnector, Salesforce and Podio. It doesn't replace HighLevel; it sits on top of it and takes over the text conversations already running through your CRM inbox. Agencies use it to build agents once and deploy them across client sub-accounts, with the option to resell the service and rebill usage.

Here's the current plan structure from CloseBot's plans page.

| Plan | Monthly price | Billing | What you get | Get started |
| --- | --- | --- | --- | --- |
| Free | $0, free forever | No card required | 100 AI messages/month, 1 agent, 1 user seat, 1 MB knowledge storage, unlimited CRM connections | [Start CloseBot free](https://app.closebot.com/a?fpr=li87) |
| Core (Business) | From $64/month, or $53/month equivalent billed annually at $640/year | Monthly or annual | Message costs included in the base price; 500 messages/month at entry, scaling with the volume slider; 15+ templates (50+ on annual billing); human support; add-on agents, storage and extra users at $5/seat | [Get the CloseBot Core plan](https://app.closebot.com/settings?tab=subscription&plan=business&toggle=monthly&fpr=li87) |
| Agency | $397/month, about $331/month equivalent on annual billing | Monthly or annual | Unlimited agents across unlimited client accounts, white-label client portal, rebillable usage at $0.012/message, rebill all costs, add client or team seats | [Get the CloseBot Agency plan](https://app.closebot.com/settings?tab=subscription&plan=agency&toggle=monthly&fpr=li87) |
| Growth | Custom quote | Custom | HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates, high-volume allowances | [Ask CloseBot about the Growth plan](https://app.closebot.com/a?fpr=li87) |

A few practical notes on those numbers, since the plan page doesn't spell all of them out:

- **Overage is wallet-based.** Free plan users can pay $0.08 per message beyond the 100-message cap. On paid business plans, going over your monthly ceiling draws from a wallet at an overage rate, so watch that setting before a busy month.
- **One message equals one segment**, unless you switch on the Agent Node's unlimited potential, where billing moves to token costs and a single conversation can consume several segments.
- **No refunds, but two ways to test.** There's a free-forever plan under 100 messages a month, plus a 7-day trial of any paid plan. Plans run month to month with no contract.
- **No bring-your-own API key.** CloseBot frames this as a security decision, which means you can't cut model costs with your own OpenAI or Anthropic credentials.

## What the same setup costs on each route

Strip away the marketing and the comparison comes down to how you're billed: per message, or per location.

| Scenario | HighLevel Conversation AI | CloseBot on top of HighLevel |
| --- | --- | --- |
| One location, ~500 AI messages/month | $97/month for AI Employee Unlimited, or pay-per-use token costs | Core from $64/month with message costs included |
| One location, ~5,000 messages/month | Still $97/month on Unlimited | Core price scales with the message slider |
| 10 enabled sub-accounts | $970/month on Unlimited | $397/month base plus $0.012/message, all rebillable |
| You need voice calls handled by AI | Included in AI Employee Growth and Unlimited | Not available; CloseBot is text-only |
| You want to resell AI to clients as a product | Rebilling requires the $497 agency plan | Agency plan includes white-label portal and rebilling |

Both routes sit on top of a HighLevel subscription you're paying for either way, so that cost is a wash. What changes is the AI layer itself: fixed per location, or variable per message with the option to pass it through to clients.

## What CloseBot doesn't do

Switching layers isn't free of trade-offs, and the honest version of this comparison includes the gaps.

CloseBot handles text only. No voice agent, no phone calls. If your clients need AI answering inbound calls, that stays with HighLevel's Voice AI or another tool.

It also needs a CRM underneath it. CloseBot connects to HighLevel, HubSpot, LeadConnector, Salesforce or Podio and answers whatever channels are wired into that CRM. It has no standalone Instagram or WhatsApp connection of its own, so if your leads live in DMs and you don't run a CRM, you'd be buying two products to do one job.

It's a sales tool. Qualification, follow-up, rescheduling and booking. One competitor comparison notes CloseBot has no customer support capability, so questions outside the sales scope have nowhere clean to go. It's also English-first in practice, and it doesn't publish SOC 2 or ISO certifications (HIPAA coverage exists on the Growth tier).

Conversation quality depends heavily on how you build it. A G2 reviewer summed that up more bluntly than any marketing page would: sloppy pipeline or follow-up logic just gets scaled faster by the AI.

For context on adoption, CloseBot's own numbers are 1M+ booked appointments, roughly 150,000 messages a day, 99.99% uptime and 1,000+ agencies on the platform. Those are vendor figures rather than audited ones. Separately, the platform holds a 4.8/5 rating on G2 across 124 reviews, which is a real signal even if G2 samples skew toward buyers who stuck around.

## How to decide without running a spreadsheet for a week

Three questions settle most of these decisions.

**How many locations have AI enabled?** One or two, and per-location pricing is manageable on either route. Ten and up, per-message billing changes the shape of the bill, especially if you can rebill it.

**Are you reselling AI to clients or using it internally?** Clients paying you for AI setting is the case CloseBot's Agency plan was built for, white-label portal and all. Using it on your own funnel is the case the $64 Core plan covers.

**Do you need voice?** If yes, HighLevel's AI Employee bundle keeps text and calls in one place and CloseBot isn't your tool. If your sales conversations are all SMS, web chat and email, a text specialist is a legitimate choice.

If the answer is "a handful of locations, and I want the pricing to be predictable", the $97 Unlimited plan does what it says. If it's "ten-plus sub-accounts and I want to charge clients for this", 👉 [compare the CloseBot Agency plan and its rebilling setup](https://app.closebot.com/settings?tab=subscription&plan=agency&toggle=monthly&fpr=li87) before you commit to a per-location model you'll have to renegotiate later.

## FAQ

**Is Conversation AI included in my HighLevel subscription?**
No. The feature is built into the platform and available everywhere, but usage is billed under one of three models: pay-per-use token billing, AI Employee Growth at $50/month per enabled location, or AI Employee Unlimited at $97/month per enabled location.

**Is it still $0.02 per message?**
That was the older flat-rate model and it still appears in a lot of third-party guides. HighLevel's current pricing documentation bills Conversation AI at token cost, with published rates per million input and output tokens by model, or bundles it as unlimited usage inside AI Employee plans.

**Do I pay per sub-account or per agency?**
Per enabled location. AI Employee Growth and Unlimited are both charged monthly per sub-account with AI switched on, which is why location count, not conversation volume, often becomes the deciding factor for agencies.

**Can I rebill Conversation AI costs to clients?**
Yes, with conditions. HighLevel's documentation states that agencies need to be on the $497/month plan to rebill AI Employee usage. Rebilling passes usage charges to the client at a markup or fixed rate; it doesn't change what HighLevel charges your agency underneath.

**Do phone calls and SMS count towards the AI plan?**
No. Phone system charges are billed separately and still apply when Voice AI is covered by AI Employee Unlimited.

**How much does CloseBot cost compared to the $97 plan?**
Business plans start at $64/month with message costs included, and the Agency plan is $397/month flat with unlimited agents and rebillable usage at $0.012 per message. There's also a free-forever plan capped at 100 messages a month if you want to test it against your current setup first. 👉 [Start with the free plan and see what your own volume costs](https://app.closebot.com/a?fpr=li87).

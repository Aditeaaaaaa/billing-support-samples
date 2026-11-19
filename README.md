# Billing Support Reply Samples ✉️

Hi, I'm Aditi! These are practice replies I wrote for common billing questions at a usage-based SaaS company. I based them on Supabase's public billing docs to show how I explain charges clearly and kindly.

*These are my own writing samples. They are not official Supabase content, and the customers are made up.*

**What I aim for in every reply:**
- Answer the real question in the first two lines
- Explain the "why" in plain English, with real numbers
- Give clear next steps the customer can do right now
- Stay warm and calm, especially when the customer is upset

---

## 1. "Why is my bill $45? Pro is $25!"

**Customer:** I'm on the Pro plan, which is $25 a month, but this month's invoice is $45. What's going on?

**Reply:**

Hi Sam,

Thanks for reaching out, and good question! Your $45 is correct. Here's the breakdown:

- **Pro plan:** $25
- **Compute for 3 projects:** each project runs on its own server, about $10 a month each = $30
- **Compute Credits:** every paid organisation gets $10 off compute = -$10

**Total: $25 + $30 - $10 = $45**

So the $10 credit covers your first project, and the other two add about $10 each.

If you don't need all three running, you can pause one, and paused projects don't add compute charges. You can see this breakdown any time on your organisation's **Usage** page.

Let me know if anything doesn't add up and I'll take another look!

Aditi

---

## 2. "My projects are paused! Why??"

**Customer:** All my projects just got paused and my app is down. I didn't do anything!

**Reply:**

Hi Priya,

I'm really sorry, I know how stressful it is when your app goes down. I've checked your account and found the cause: your last invoice couldn't be paid. Your card was declined, so the invoice became overdue. When that happens, projects are paused and the organisation moves to the Free plan.

The good news is it's quick to fix:

1. Go to your organisation's **Billing** page and update your card (add the new card first, then remove the old one).
2. Open **Invoices** and click **Pay now** on the overdue invoice.
3. Once all outstanding invoices are paid, you can restore your projects.

One tip: credit top-ups can't be used to pay an overdue invoice, so please pay it with the card directly.

If the payment won't go through, reply here and I'll stay with you until it's sorted.

Aditi

---

## 3. "I upgraded by mistake, please refund me"

**Customer:** I clicked upgrade on the wrong organisation by accident. Can I get my money back?

**Reply:**

Hi Leo,

Thanks for letting us know, and don't worry, this happens more than you'd think!

I need to be upfront: we don't give refunds, including for accidental upgrades. But you won't lose that money. When you downgrade, the unused time on your plan becomes **credits** on that organisation. Credits never expire and are used automatically on future invoices before your card is charged.

If the credits would be more useful on your *other* organisation, just reply with its name and we can move them across for you.

Sorry I couldn't give you a straight refund, but I'll make sure the credit ends up where it's most useful.

Aditi

---

## 4. "My app stopped working mid-month"

**Customer:** Some features in my app stopped working halfway through the month. Is something broken?

**Reply:**

Hi Mia,

Thanks for flagging this! Nothing is broken. Your app is growing, which is a good problem to have. 🎉

Your organisation has the **Spend Cap** turned on (it's on by default for Pro). It stops you from being charged for usage above your plan's limits. This month you went over your included **250 GB of egress** (the data your app sends out), so extra usage was paused until your billing cycle resets.

You have two options:

1. **Keep the Spend Cap on:** usage resets at the start of your next billing cycle, with no extra charges.
2. **Turn the Spend Cap off:** your app works again straight away, and extra egress is billed at $0.09 per GB.

You can change this in **Billing > Cost Control**. Happy to help you estimate the cost before you decide!

Aditi

---

## 5. The upset customer: "This is a scam"

**Customer:** You charged me $190 extra with NO warning. This is a scam and I want it removed NOW.

**Reply:**

Hi Jordan,

I completely understand why a $190 surprise would make you angry, and I'm sorry this caught you off guard. Let me explain exactly where it came from.

Last month your projects used about **2,119 GB of egress** (data sent out by your app) above the 250 GB included in your plan. Your Spend Cap was turned off, so the extra usage was billed at $0.09 per GB, which is the $190.75 on your invoice.

I can't remove a charge for usage that happened, and I want to be honest with you about that. But I can help make sure it never surprises you again:

- **Turn the Spend Cap on** in Billing > Cost Control, so usage can't go over your plan limits without your say.
- **Check the Usage page** during the month to see how close you are.
- If the spike was unexpected, reply here and I'll help you find which project caused it.

Thanks for your patience while I looked into this.

Aditi

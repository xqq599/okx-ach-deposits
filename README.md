# OKX ACH Deposit: How to Deposit USD, How Fast It Clears, and Why You Can't Withdraw Immediately (Web & App Steps)

ACH deposits on OKX are open only to verified users who live in eligible US states, and the bank account has to be connected through Plaid. Once you hit Submit, the money is available to trade straight away, but it sits under a security hold and can't be withdrawn until the transfer clears, which OKX's help documentation puts at three to five business days. An ACH deposit also cannot be canceled after it's initiated, so the amount you type is the amount that leaves your bank.

Below is the qualification checklist, the exact click paths on web and in the app, the timing and limit rules that actually apply, and the fixes for the errors that stop most first deposits.

> **At a glance:** You're in the US, you've passed OKX identity verification, and you want to fund from a US bank account. Go to Deposit > Cash, choose USD or USDG, select Bank transfer (ACH), link your bank via Plaid, then Preview and Submit. Plan on trading immediately and waiting a few business days before withdrawal unlocks.
> 👉 [Start your OKX ACH deposit from the cash deposit page](https://okx.com/join/CASH20)

## Who can use OKX ACH deposits

ACH is restricted to US users who have completed verification and reside in eligible states, and the bank account must be linked through Plaid, the third-party service OKX uses to connect bank accounts securely. If the Deposit USD option never appears in your account, one of those two conditions is usually the cause. OKX's help documentation adds that the payment methods shown to you are limited by the identity document you verified with, so two users in the same state can see different menus.

The name on your OKX account has to match the name on the bank account. A mismatch is one of the standard reasons a transfer comes back rejected or returned.

You also pick a destination before you enter an amount. ACH can land in your **USD balance** or your **USDG balance**, and the help page notes that USDG balances can earn. If you later decide you wanted the other one, the Change option next to the deposit method switches it before you submit.

## ACH next to the other OKX funding routes

ACH is the cheap, slow-clearing option for US bank accounts. Wire transfer costs more but moves larger sums, and the regional rails (SEPA for EUR, local AED transfers in the UAE) only matter if you're funding from outside the US.

| Method | Where it works | Fee | Limits | Timing | Start |
| --- | --- | --- | --- | --- | --- |
| Bank transfer (ACH) | US bank accounts, eligible states | No OKX-side fee listed in OKX's Dec 2025 guide; confirm on Preview | Set automatically per account and adjusted over time | Trades immediately, clears in 3–5 business days, withdrawal held until cleared | [Use ACH](https://okx.com/join/CASH20) |
| Wire transfer (US domestic) | US banks | Bank fee of roughly $10–$20 per the Dec 2025 guide | $100 min / $1M+ per that guide | 1–3 business days | [Fund by wire](https://okx.com/join/CASH20) |
| SEPA (EUR) | Europe | €0 per the Dec 2025 guide | €20 min / €100,000+ per that guide | 1–2 business days | [Fund in EUR](https://okx.com/join/CASH20) |
| Local AED transfer | UAE | 0 AED per the Dec 2025 guide | 100 AED min / 1M+ per that guide | Same or next business day | [Fund in AED](https://okx.com/join/CASH20) |
| International wire | Global | 0.1% from OKX plus bank charges, per the Dec 2025 guide | $100 min, upper bound varies | 2–5 business days | [Fund internationally](https://okx.com/join/CASH20) |

Only the ACH row reflects the current official help documentation (updated September 2, 2026). The other rows come from OKX's December 2025 guide, and fees and limits on those rails may have moved since. Confirm the amount and any charge on the Preview screen before you submit. On ACH limits specifically, OKX says they're assigned automatically from your account history and usage and can be raised or lowered over time, so any fixed figure you see quoted online is a reference point rather than your ceiling. You can check yours under Assets > Deposit > Cash.

## Step by step on the web

1. Log in at app.okx.com and go to **Deposit > Cash**.
2. Under Cash, choose the **USD** balance or the **USDG** balance.
3. Select **Bank transfer (ACH)** and click **Next**.
4. If no bank account is linked yet, click **Add** and connect your bank through Plaid. If an account is already linked and you want a different one, click **Change**.
5. Enter the amount and click **Preview**. The Change option beside the deposit method lets you switch to USDG here if you skipped it earlier.
6. Click **Submit**.

Funds become available for trading as soon as the deposit completes. Keep enough money in the bank account afterwards, because the debit on your bank side can lag the credit on OKX's side.

## Step by step in the app

1. Open the OKX app, tap **Transfer**, then **Deposit**.
2. Choose the USD or USDG balance.
3. Tap **Bank transfer (ACH)**, then **Add account** to link your bank through Plaid.
4. After the success screen confirms the account is added, enter your amount. You can adjust the destination here too.
5. Tap **Preview**, check the details, then **Submit**.

Adding a second bank later works the same way: tap the current bank account and switch or add another.

## The four things that trip people up

**Trading is not the same as withdrawing.** ACH deposits carry a security hold while OKX verifies the transaction and screens it for fraud. You can buy, sell, and trade with the balance right away. You cannot move it off the platform until the hold lifts. To see where a specific transfer stands, go to **Portfolio > select USD > open the transaction** and read the deposit details.

**The transfer can't be pulled back.** There's no cancel button once an ACH deposit is initiated, and once the bank processes it, OKX can't stop or reverse the payment either. OKX's banking partner submits ACH batches once per business day, so a status of Processing is normal and flips to Complete when the batch is finalized. The full clear typically takes three to five business days.

**Limits move.** Deposit and withdrawal limits for ACH are assigned by the system based on your history, and they can go down as well as up. If you're planning a large transfer, look at the limit displayed on the deposit page instead of budgeting around a number from a blog post.

**The names have to match.** Use a personal bank account in your own name. A joint account or a business account tied to a different legal name is a return waiting to happen, and returns cost you days.

👉 [Set up your verified OKX account before you send the first transfer](https://okx.com/join/CASH20)

## Troubleshooting: what to do when ACH won't cooperate

**You can't see Deposit USD at all.** Check that your identity verification is complete and that your registered residence is an eligible US state. If both are fine, review which document you verified with, since that determines the payment methods offered.

**Plaid won't link your bank.** Try a different bank first, since most major US national banks (Chase, Bank of America, and TD Bank are the examples OKX gives) and many credit unions are supported. If that fails, you can add a debit card and buy with that instead, or fund the account with a U.S. Domestic Wire Transfer. If a major national bank still won't connect, contact OKX Assistant with the bank name and the exact error message.

**No 2FA code arrives during linking.** Confirm the phone number you entered into Plaid is right, then use **Resend code**. If the number itself was wrong, choose **Not you?** to create a fresh Plaid account and link again from there.

**A bank account that worked before now fails.** Close and restart the app first. If it still won't go through, the connection between your bank and OKX has likely lapsed. Open the bank account selector, find **Manage**, remove the old account, and relink it through Plaid.

**A deposit is stuck or missing.** Look under **All deposits** on the cash deposit page for the live status, and allow for weekends and bank holidays. If you hit an error code at any point, screenshot it before contacting support, because the code is what the support team works from.

👉 [Check your account's available deposit methods on OKX](https://okx.com/join/CASH20)

## Which route fits your deposit

If you're funding from a US bank account in a modest amount and you plan to trade rather than move coins out quickly, ACH is the sensible default. The cost is low on the OKX side and the trading balance appears at once; the trade-off is the three-to-five-day window before withdrawal opens.

If you need the funds withdrawable within hours and the amount is small, a debit card is the faster route and costs a percentage instead of a flat fee, which OKX's December 2025 guide put at 1.99%–3.99%. That percentage gets expensive fast above a few hundred dollars.

If you're moving a large sum, or your bank simply refuses to connect through Plaid, use the U.S. Domestic Wire Transfer. You'll pay a bank fee in the range the guide lists, and the transfer takes one to three business days, but the limit ceiling is far higher.

Two checks before you press Submit: the name on the OKX account matches the name on the bank account exactly, and the Preview screen shows the amount and any fee you actually expected. Everything after that point is irreversible.

👉 [Open an OKX account and start with an ACH deposit](https://okx.com/join/CASH20)

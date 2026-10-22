# Start from scratch with Google and Gemini (free)

*Last checked 22 Oct 2026, for free personal Google accounts in Australia. Google changes its features often, so if a step looks different, follow the linked Google help page. General information only, not tax or legal advice.*

If you have nothing set up yet, this is the simplest free way to run the paperwork side of a care business. One Google account gives you email (Gmail), a calendar, file storage (Drive), spreadsheets (Sheets), documents (Docs), to-do lists (Keep and Tasks) and an AI helper (the Gemini app). It all works on your phone and on a computer, and none of it costs anything.

Plan on a weekend to set it up. After that it's about half an hour each Friday.

## Part 1: The weekend setup

**1. Make a separate business Google account.** Keep work apart from your personal email, photos and family stuff. Create a new account with a plain, professional address such as jo.citizen.care@gmail.com ([Google: create an account](https://support.google.com/accounts/answer/27441)). Add it to your phone alongside your personal account, so you can switch between them.

**2. Turn on 2-Step Verification.** This stops someone getting into your account with just your password, and your account will hold invoices and bank details. Go to your Google Account, Security, 2-Step Verification ([Google: turn on 2-Step Verification](https://support.google.com/accounts/answer/185839)). Using your phone as the second step is easiest.

**3. Set up your Drive folders.** In Google Drive, make one folder called "Care business" and four folders inside it:

```text
Care business/
  Clients/        one folder per client, named by initials, e.g. "JS"
  Invoices/       one folder per financial year, e.g. "2026-27"
  Receipts/       one folder per financial year
  Tax/            ABN letter, insurance, screening, tax returns
```

Use initials for client folders, not full names. Put your ABN confirmation, public liability certificate and police certificate or NDIS screening clearance in Tax, with the expiry date in the file name. That's your "provider pack" ready to send.

**4. Copy the invoice and timesheet spreadsheet.** Download [care-worker-invoice-and-timesheet.xlsx](../templates/care-worker-invoice-and-timesheet.xlsx) from this kit, upload it to your Care business folder in Drive, open it, then choose File, Save as Google Sheets. It has three tabs:

*Settings* holds your name, ABN, rate, bank details and the last invoice number you used. Fill this in once.

*Timesheet* is where you add each visit: date, client code, start and finish times. Hours work themselves out.

*Invoice* builds itself from Settings: the next invoice number (your prefix plus the last number plus one), today's date, the due date, line amounts, the total and the "No GST has been charged. Not registered for GST." line. You add the provider, client reference and the week's visits. After you send it, add 1 to "Last invoice number used" in Settings so the next one is numbered correctly.

To make each invoice, use File, Make a copy, name it with the invoice number (e.g. "JC-1001 Provider name"), then File, Download, PDF. Save the PDF in Invoices.

**5. Put your shifts in Google Calendar.** Add each regular visit as a repeating event called by the client's code, such as "Client A, clean". Give each client its own colour so your week is easy to read at a glance (on a computer, right-click an event and choose a colour). Don't put addresses or health notes in events.

**6. Set up Gmail.** Add an email signature with your name, "Independent aged care worker", phone, and ABN, so every email shows them ([Google: Gmail signature](https://support.google.com/mail/answer/8395)). Make labels such as "Providers", "Invoices sent" and "Remittances", and file emails as they come in ([Google: Gmail labels](https://support.google.com/mail/answer/118708)).

**7. Install the Gemini app and choose your privacy setting.** Install Gemini on your phone and sign in with your business account. Then decide about one setting, called Keep Activity (in the app: your profile picture, then Gemini Apps Activity).

With Keep Activity **on** (the default for adults), your chats are saved in your account, may be read by human reviewers and are used to improve Google's AI. You need it on to connect Gemini to your Gmail, Drive and Calendar ([Google: connect Google Workspace](https://support.google.com/gemini/answer/15229592)).

With Keep Activity **off**, your future chats aren't used to train Google's AI unless you send feedback, though Google still keeps them for up to 72 hours to run the service and for safety ([Google: Gemini privacy hub](https://support.google.com/gemini/answer/13594961)). But Gemini can't read your Gmail, Drive or Calendar, so you copy and paste instead.

Either way works with this kit. If you leave it on, be strict about using client codes and never pasting Medicare numbers, dates of birth or health details. If you turn it off, every prompt below still works by pasting.

**8. Connect Gemini to your Google apps (optional, needs Keep Activity on).** In the Gemini app, open Settings, Connected Apps, and turn on Google Workspace. Gemini can then find and summarise emails and Drive files, create Calendar events, and add to Google Tasks and Keep when you ask ([Google: Connected Apps](https://support.google.com/gemini/answer/13695044)). Gemini can get things wrong or pick up an older email, so check the sources it shows.

**9. Use Keep or Tasks for to-dos.** Google Keep is good for quick notes and checklists, such as "Client A: needs more bin bags". Google Tasks suits dated jobs, such as "Renew insurance 31 March" ([Google: Tasks](https://support.google.com/tasks/answer/7675772)). With Gemini connected you can just say "add a task to chase invoice JC-1003 next Friday".

**10. Scan receipts as you go.** In the Google Drive app, tap the plus button, then Scan, photograph the receipt, and save it into Receipts as a searchable PDF ([Google: scan documents with Drive](https://support.google.com/drive/answer/3145835)). Name it with the date and what it was, e.g. "2026-10-14 Bunnings cleaning products".

**11. Open a separate bank account for tax.** Most banks let you add a free savings account in their app. This is where your tax set-aside goes each week.

## Part 2: Your Friday routine

**Fill in the Timesheet tab** from your Calendar and notes. If your notes are messy, paste them into Gemini with the timesheet prompt below.

**Make the invoices**, one per provider. Copy the week's rows into the Invoice tab, add the provider and client reference, check the total, then save the PDF in Invoices. Ask Gemini to check it first with the check prompt below.

**Email each provider** from Gmail with the PDF attached and label it "Invoices sent". Add a Task to follow up on the due date.

**Set aside tax.** Move your set-aside percentage of this week's invoices into the tax account. The tax prompt below helps you pick a percentage, and you can check it with the [ATO tax rates](https://www.ato.gov.au/tax-rates-and-codes/tax-rates-australian-residents).

## Part 3: Monthly, quarterly and yearly

**Monthly:** match payments in your bank account against "Invoices sent" and chase anything overdue (see [chasing late payments](late-payments.md)). Add up your income for the last 12 months: once it reaches $75,000 you must register for GST within 21 days ([ATO: registering for GST](https://www.ato.gov.au/businesses-and-organisations/gst-excise-and-indirect-taxes/gst/registering-for-gst/)).

**Quarterly:** check the expiry dates in your Tax folder (insurance, police certificate, first aid) and set Tasks to renew them a month early. If the ATO has put you on PAYG instalments, pay them from your tax account.

**At 30 June:** start new "2027-28" folders in Invoices and Receipts. Download a copy of the year's spreadsheet and invoices. Give your tax agent (or myTax) your income total and your expenses from Receipts. Keep everything for 5 years ([ATO: record keeping rules](https://www.ato.gov.au/businesses-and-organisations/preparing-lodging-and-paying/record-keeping-for-business/overview-of-record-keeping-rules-for-business)).

## Gemini prompts for this setup

Use client codes in every prompt. If Keep Activity is off, paste the content in place of the "find" step.

**Timesheet from your Calendar (needs Connected Apps):**

```text
Look at my Google Calendar for last week, Monday to Sunday. List every
event with "Client" in the title as a table: Date, Client code, Start,
Finish, Hours (decimal), and the event title. Total the hours per client.
Don't guess anything that isn't in the calendar.
```

**Timesheet from pasted notes (works with Keep Activity off):**

```text
Turn these notes into a table with columns Date, Client code, Start,
Finish, Hours (decimal), Service type, What I did. Use official Support
at Home service types such as Domestic assistance or Social support.
List anything unclear as a question instead of guessing.
Notes: [PASTE]
```

**Check an invoice before sending:**

```text
Check this invoice to a Support at Home provider. I'm an Australian sole
trader not registered for GST. Is anything missing: ABN, invoice number,
dates, provider, client reference, service types, hours, rate, correct
totals, "No GST has been charged" line, bank details? Flag vague
descriptions or travel lines. [PASTE THE INVOICE ROWS]
```

**Email to send it (paste into Gmail yourself):**

```text
Write a short email to [PROVIDER] accounts sending invoice [NUMBER] for
$[AMOUNT] for services in the week of [DATE]. Friendly and professional,
Australian English, under 80 words, with a subject line.
```

**Find what's unpaid (needs Connected Apps):**

```text
Search my Gmail label "Invoices sent" for invoices I sent in the last 60
days, and my "Remittances" label for payments. List any invoice number
that has no matching remittance, with the provider and amount.
```

**Tax set-aside:**

```text
I'm an Australian resident sole trader. Expected business income this
financial year $[AMOUNT], expenses $[AMOUNT], other income $[AMOUNT].
Using the current ATO resident tax rates (say which year), estimate my
income tax and Medicare levy, show the working, and give me a simple
percentage to set aside from each payment. Remind me to check with the ATO.
```

## What's free and what's paid

Everything in this guide works on a free account. Some Gemini features you may see advertised inside Gmail, Docs and Sheets need a paid Google AI plan (Google AI Plus, Pro or Ultra) in Australia ([Google: Gemini in Workspace apps](https://support.google.com/mail/answer/13952129)). That includes the "Ask Gemini" side panel in Sheets, Docs and Gmail, and "Help me write" in Gmail, which is free only in the US. The free alternative is what this guide does: use the Gemini app, then copy its answer into Sheets or Gmail.

---
title: Velira Privacy Policy
---

# Velira Privacy Policy

**Last updated: 1 October 2026**

Velira is a balance journal for private language tutors: lessons, payments and
what each student has left. This policy explains what information Velira uses,
where it is kept, and who can see it.

## Who we are

Velira is made and operated by **FOP Chernukhin Ivan Serhiiovych** (ФОП Чернухін
Іван Сергійович), trading as **Alacrity**, Kyiv, Ukraine.

Contact: **[ialacritydev@gmail.com](mailto:ialacritydev@gmail.com)**

## The short version

Velira keeps a tutor's records on the tutor's own phone. There is no account,
no advertising, no analytics and no tracking, and nothing is sold. Information
about a student leaves the phone only when the tutor chooses to share that
student's page, export a file, or send a payment message from their own
messenger. Velira never receives or processes money.

## What the app stores on the phone

In the app's private storage on the tutor's phone:

- students: name, price per lesson and currency, lesson length, time zone, and
  whether they pay after each lesson or in packages
- weekly lesson times and the lessons they produce
- payments (amount, number of lessons, date) and lesson marks (held, missed,
  cancelled), including corrections — records are never edited, a correction
  is a new entry
- for a student whose page is shared: that page's identifier and the secret
  that lets this phone update it
- preferences: appearance, language, the trial start date, how the tutor
  teaches

Uninstalling the app deletes all of it from the phone.

**Why:** this is the service itself. The tutor is the controller of their
students' information; Velira is the tool they keep it in.

## Backup

Android may copy the app's database and preferences to the tutor's Google
account backup, and to a new phone during transfer. Velira allows the cloud
backup **only when Android can encrypt it end to end with the phone's screen
lock**, so it cannot be read on Google's side. A phone without a screen lock
gets no cloud backup.

The tutor can also export everything to a file and choose where to save it,
through Android's own file picker. Velira does not learn where it went.

## A student's page

If the tutor taps **Share their page**, Velira's server receives, for that one
student only:

- the student's name, price per lesson, lesson length and time zone
- the current balance in lessons
- up to 20 coming lessons and up to 30 recent journal entries

The app sends an updated copy after each change. The page is readable by anyone
with its link; the link contains a random identifier. The server stores the
page, when it was last updated, and a SHA-256 hash of the page's secret — never
the secret itself, which stays on the tutor's phone.

The page offers the student a calendar file of their coming lessons with
reminders. The student's calendar app fetches it from Velira's server.

**Stop sharing** deletes the page from the server; its link then shows that the
page is not there.

**Why:** to let the tutor show a student their own balance and lessons, at the
tutor's request. The legal basis is performance of the service requested
(Article 6(1)(b) GDPR) and the tutor's legitimate interest in keeping their
students informed (Article 6(1)(f) GDPR).

## Permissions the app asks for

- **Notifications** — a reminder a few minutes after each lesson, so it can be
  marked. Asked only after an explanation.
- **Calendar (read)** — only when the tutor asks Velira to find weekly lessons
  in it. Six weeks back and two weeks ahead are read once, on the phone: event
  title, start, end and whether it is all-day. Nothing is kept in sync and
  nothing is sent.
- **Internet** — for a student's page and for Google Play.

## Payments for Velira

Velira's plan is bought through **Google Play**, which processes the payment
under Google's own terms and privacy policy. Velira receives only whether a
plan is active. Students never pay.

## Service providers and where data is processed

- **Vercel**, hosting the student pages in Frankfurt, Germany
- **Neon**, the PostgreSQL database for student pages, in Frankfurt, Germany
- **Google**, for Android backup and Google Play

These providers may process limited technical request information needed to
deliver and protect their services. Velira's own code does not log visitors.

## How long information is kept

- On the phone: until the tutor deletes it or uninstalls the app.
- A student's page: until the tutor stops sharing it.
- Backups: under the Google account's own backup rules.

## Your choices and rights

Depending on where you live, you may have the right to access, correct, export
or delete personal information about you, restrict or object to processing, and
complain to your local data protection authority.

Most information is held by the tutor on their phone, so a **student** should
ask their tutor first. A tutor can remove a student's page at once with **Stop
sharing**. Anyone may email
**[ialacritydev@gmail.com](mailto:ialacritydev@gmail.com)** to have a page
removed or for any request; requests are answered within 30 days.

## Security

Connections to Velira's server use HTTPS. Pages are updated only with a secret
held on the tutor's phone; the server keeps its hash. Records on the phone are
in the app's private storage, and the cloud backup is end-to-end encrypted.

## Children

Velira is a tool for tutors and is not directed to children. A tutor may record
students who are children; the tutor is responsible for having their parents'
agreement to keep those records and to share a page.

## Changes

If this policy changes, the new version will be published on this page with a
new date. Material changes will be communicated in the app where practical.

## Contact

**Alacrity / FOP Chernukhin Ivan Serhiiovych**  
Kyiv, Ukraine  
[ialacritydev@gmail.com](mailto:ialacritydev@gmail.com)

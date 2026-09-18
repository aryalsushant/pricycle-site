# PriCycle — privacy policy and support pages

The two pages the App Store and Google Play require: a privacy policy at a
public URL, and a support page leading to real contact information.

**These files are generated. Do not edit them here.**

They are built from the PriCycle app's own source, so that the privacy policy
published at this URL is the same text the app shows on its own Privacy Policy
screen. A test in the app repository compares the two and fails if they have
drifted — editing a page here would break that quietly, and a privacy policy
that says two different things is worse than no privacy policy at all.

To change anything:

1. Edit the source in the app repository — `privacy-policy-text.ts` for the
   policy, `contact-details.ts` for the address and email.
2. Run `npm run generate:site` there.
3. Copy the contents of `site/` over this repository and push.

The pages deliberately make no network requests: no web fonts, no analytics, no
CDN, no images. It would be a strange thing to track the people who came here
to read that the app does not track them.

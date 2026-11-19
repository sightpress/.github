## What this changes

<!-- One or two sentences, in plain English. Name the task ID or the issue, for example "Closes #12". -->

## How to check it

<!-- The steps a reviewer follows, and what they should see after each one. -->

## Keyboard walkthrough

<!-- For any change to a screen: how you went through it with the keyboard alone, and what a screen reader
announces. Write "No screen changes" otherwise. -->

## Personal data

<!-- List any new field that holds personal data, and how long it is kept. Write "None" otherwise. -->

## Checklist

- [ ] The title follows Conventional Commits (`feat:`, `fix:`, `docs:` …).
- [ ] `composer check` passes (or `zensical build --strict` in `docs`).
- [ ] For screen changes: the accessibility tests report no violations, in light, dark and forced colours, and at
  320 pixels wide.
- [ ] Every screenshot or image in this pull request has a text description.

## 0.2.1

- Fix an issue parsing `generateContent()` responses that do not include content
  (this can occur for some `finishReason`s).
- Fix an issue parsing `generateContent()` responses that include citation
  sources with unpopulated fields
- Add link to ai.google.dev docs.

## 0.2.0

- **Breaking** `HarmCategory.unknown` renamed to `unspecified`. Removed unused
  `unknown` values in the `HarmProbability` and `FinishReason` enums.
- Add additional API documentation.
- Update the getting started instructions in the readme.

## 0.1.0

- Initial release.

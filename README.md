# Textual IRC Client
- A build of Textual 7.2.0 without code signature.

This Application is directly built in Xcode 14 from the offical [Textual repository](https://github.com/Codeux-Software/Textual); it is UNSIGNED, so you would have to [approve the applications to run on your own Mac](https://www.howtogeek.com/205393/gatekeeper-101-why-your-mac-only-allows-apple-approved-software-by-default/).

Modifications:
- In "Textual/Configurations/Build/Standard Release/Enabled Features.xcconfig" - "TEXTUAL_BUILT_WITH_LICENSE_MANAGER=0" (This prevents the trial period countdown)
- In Xcode 14's build settings - "CODE_SIGNING_ALLOWED" set to "NO"

References (Yes I don't code):
https://github.com/Codeux-Software/Textual/blob/master/README.md
https://stackoverflow.com/questions/52602009/xcode-10-where-is-the-dont-code-sign-option-in-code-signing-identity
https://dev.to/gurkhaman/building-textual-irc-client-4317

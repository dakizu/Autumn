# Change Log

All notable changes to the "autumn" extension will be documented in this file.

## [Unreleased]

## [1.0.0] - 2021-08-25
- Initial release

## [1.1.0] - 2021-08-26
- This release has a focus on the Rust programming language
- Started using a more consistent visual language that should make reasoning about your code easier.
- Non-essential annotative syntax now has a dimmed foreground (lifetimes, namespaces, and operators as of now).
- The rust-analyzer extension is now also officially supported. Type annotations are highlighed in the same dimmed foreground color as lifetimes.
- Code that might negatively impact codegen now has a dedicated color. This should help the user be more aware of their macro and attribute usage, potentially helping impove compilation time.
- Other languages have regressed slightly in highlighting as I removed a lot of generic colorization, opting for a more language-specific color scheme for each language I use. Following updates will hopefully add unique and syntactically helpful colorization to other languages.

## [1.1.1] - 2021-09-23
- Functions now have their own dedicated color.

# Dachlatten Markdown

[![Build Status](https://github.com/sipgate/dachlatten-markdown/actions/workflows/unit-tests.yml/badge.svg)](https://github.com/sipgate/dachlatten-markdown/actions/workflows/unit-tests.yml)
[![GitHub License](https://img.shields.io/github/license/sipgate/dachlatten-markdown)](https://github.com/sipgate/dachlatten-markdown/blob/main/LICENSE)
[![GitHub Tag](https://img.shields.io/github/v/tag/sipgate/dachlatten-markdown)](https://github.com/sipgate/dachlatten-markdown/tags)

This library provides [Swift UI](https://developer.apple.com/documentation/swiftui/text)-like Markdown support for Compose UI. All Compose UI components that can work with [AnnotatedString](https://developer.android.com/reference/kotlin/androidx/compose/ui/text/AnnotatedString)s are supported.

```kotlin
val annotatedString = parseMarkdown(stringWithMarkdown)

setContent {
    BasicText(text = parsedText)
}
```

At the moment only basic formatting is supported. If you need more complex things, like tables and images, use Compose UI.

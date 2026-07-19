# Android Studio Intro — Justin Guida

A simple school assignment for an intro Android development course. The goal of
this module was to get familiar with **Android Studio** and the **Layout Editor**
by building a basic screen — no app logic, just the layout.

## What it is

A single layout (`activity_main.xml`) built with the Layout Editor. It contains
three UI elements:

| Element        | ID               | Notes                        |
|----------------|------------------|------------------------------|
| Button         | `buttonSayHello` | Text = "Say Hello"           |
| Plain Text (EditText) | `nameText`| Hint = "Enter your name"     |
| TextView       | `textGreeting`   | Intentionally has no text    |

## Screenshots

**Layout preview:**

![App layout preview](app/screenshot.png)

**Component Tree (three objects + IDs):**

![Component Tree](app/component-tree.png)

## Project setup

- **Language:** Java
- **Target SDK:** API 34
- **Build config:** Groovy DSL
- **Activity:** No Activity (per assignment instructions)

## Layout file

The layout lives at:

```
app/src/main/res/layout/activity_main.xml
```

## Notes

Personal study notes on the Layout Editor (gravity, text/strings, colors,
centering) are in the [`notes/`](notes/) folder.

## Requirements

The full assignment rubric this project satisfies is in
[`REQUIREMENTS.md`](REQUIREMENTS.md).

## Reflection

The written discussion of challenges, initial experience, and questions is in
[`REFLECTION.md`](REFLECTION.md).

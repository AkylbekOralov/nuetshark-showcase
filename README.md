# NuetShark

<img width="400" height="260" alt="Image" src="https://github.com/user-attachments/assets/8ad68c36-8618-4f3c-9ffd-b03e59e2c0b6" />

NuetShark is an iOS exam-prep app for students preparing for the new GET exam at Nazarbayev University.

This public repository is a project overview only. The production source code is private while I prepare the app for release.

## What I built

- Full-length practice tests
- Quiz modes for focused practice
- Result and review flows
- Progress tracking across completed work
- Student-oriented structure for repeatable exam preparation

## Tech and Architecture

- iOS app built with Swift
- Modular project managed with Tuist
- `nuet-ios` app target plus separate modules for `NuetKit`, `CoreEntities`, `FeatureFlags`, and `NuetNetwork`
- Scene-based feature structure with `Entity`, `Interactor`, `Presenter`, `Router`, and `View`
- UIKit-first implementation with selective SwiftUI usage
- Core Data for local persistence
- Supabase for backend-related flows
- Factory for dependency injection
- SnapKit for layout
- LaTeXSwiftUI for rendering math content in exam questions

## Project Notes

- Xcode project files are not committed because the workspace is generated with Tuist
- Exam content and app structure are designed around real preparation workflows, including tests, quizzes, review, and progress visibility
- The codebase stays private for now because the app is planned for App Store release

## Tuist

```bash
tuist install
tuist generate
```

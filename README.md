# NuetShark

NuetShark is an iOS exam-prep app for students preparing for the new GET exam at Nazarbayev University.

This public repository is a project overview only. The production source code is private while I prepare the app for release.

<img width="1624" height="975" alt="Image" src="https://github.com/user-attachments/assets/cd70da59-b81e-4de7-b80d-7d2a9ea16583" />

## What I built

- Full-length practice tests
- Quiz modes for focused practice
- Result and review flows
- Progress tracking across completed work
- Student-oriented structure for repeatable exam preparation
  
<p align="center">  
  <img width="1206" height="2622" alt="Image" src="https://github.com/user-attachments/assets/52300758-47ad-43e8-8db6-0e98a81bd10e" />
  <img width="1206" height="2622" alt="Image" src="https://github.com/user-attachments/assets/3fa7884f-47e7-429a-8732-c59625bcb29d" />
  <img width="1206" height="2622" alt="Image" src="https://github.com/user-attachments/assets/c4413327-5671-4b39-a963-42f426b9fb5c" />
  <img width="1206" height="2622" alt="Image" src="https://github.com/user-attachments/assets/5f3b4bfe-2b30-463c-a61d-1e7af831b51d" />
  <img width="1206" height="2622" alt="Image" src="https://github.com/user-attachments/assets/d9a03189-905e-4be7-bfec-f45feb7a5d5a" />
</p>

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

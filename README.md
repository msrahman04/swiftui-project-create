# SwiftUIProjectCreate

This is a SwiftUI-based iOS application created using Xcode.

## Project Details

- **Interface**: SwiftUI  
- **Language**: Swift  
- **Testing System**: Swift Testing with XCTest UI Tests  
- **Storage**: None (no Core Data or CloudKit used)  
- **Bundle Identifier**: com.msrahman.SwiftUIProjectCreate  

## Description

This project serves as a starting point for learning and developing iOS apps using SwiftUI. It follows best practices in Swift development and provides a clean structure for further expansion.

## Getting Started

To run the project:

1. Clone this repository.
2. Open the `.xcodeproj` or `.xcworkspace` file in Xcode.
3. Select a simulator or real device.
4. Build and run the app.

## Requirements

- macOS
- Xcode (latest version recommended)
- Swift 5+

---

## Project Creation Details step by step

### Step 1

Open Xcode and either click “Create New Project” in Xcode’s startup window, or choose File > New > Project.

### Step 2

In the template selector, select iOS as the platform, select the App template, and then click Next.

### Step 3
The following section describes the main project setup, explaining the name of each field and its purpose.

#### 🔹 Product Name
What it is: The name of your app/project.

Used for: Naming the target, generated files, and part of the Bundle Identifier.

Example: SwiftUIProjectCreate

#### 🔹 Team
What it is: The Apple Developer Team or Personal Team linked to your Apple ID.

Used for: Code signing and deploying to real devices or submitting to the App Store.

If you choose “None”: You won’t be able to run the app on a real device unless you select a team later in the project settings.

#### 🔹 Organization Identifier
What it is: A reverse domain style string that uniquely identifies your organization.

Used for: Forms the Bundle Identifier when combined with Product Name.

Example: com.msrahman → results in bundle ID com.msrahman.SwiftUIProjectCreate.

#### 🔹 Bundle Identifier
Auto-generated: Combines the Organization Identifier and Product Name.

Used for: Uniquely identifying your app across the Apple ecosystem (App Store, push notifications, provisioning, etc.).

#### 🔹 Interface
What it is: The user interface framework you'll use.

Options:

SwiftUI: Recommended modern declarative UI framework.

Storyboard: Older visual UI builder.

You chose: SwiftUI.

#### 🔹 Language
What it is: The programming language for your app.

Options: Swift (modern, safe, preferred) or Objective-C (older).

You chose: Swift.

#### 🔹 Testing System
What it is: Frameworks for writing and running tests.

Options: Includes support for unit testing and UI testing.

You chose: Swift Testing with XCTest UI Tests, meaning:

Unit Tests target will be created

UI Tests target will be created

#### 🔹 Storage
What it is: Whether you want to use Core Data for local persistent storage.

Options: None (default), or enable Core Data.

You chose: None — so no Core Data setup will be generated.

#### 🔹 Host in CloudKit (disabled)
What it is: An option to use iCloud + Core Data with CloudKit sync.

Available only when: Storage = Core Data and Team = selected.




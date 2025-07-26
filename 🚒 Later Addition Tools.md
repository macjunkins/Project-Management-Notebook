# Eample Apple Dev Tools to consider

- **Obsidian** for thinking and planning

- **VS Code** for coding

- **Warp** for terminal work

- **GitHub + GitKraken** for version control

- **Xcode when necessary** for builds and deployment

## 🤨 Now, here are a few **select tools to _consider_ adding**, depending on what’s coming next in your journey

---

## 🔎 **1. [Simulator Companion Tool] – _optional for iOS work_**

## ➤ Examples

- **[SimulatorStatusMagic](https://github.com/shinydevelopment/SimulatorStatusMagic)** (for clean UI screenshots)

- **Apple’s `simctl`** via terminal (`xcrun simctl`)

## ☝🏻Use if

- You're preparing App Store screenshots

- You want to automate testing or simulate device states

---

## 🧪 **2. Fastlane**

### Best For

- Automating builds, screenshots, TestFlight uploads, and App Store releases

Install:

```bash
brew install fastlane
```

Use when:

- You're ready to streamline TestFlight or App Store deployment

- You want repeatable scripts for your app release

---

## 🔁 **3. GitHub Projects (for lightweight issue tracking)**

- Replace or enhance Obsidian task tracking when collaborating or tracking TODOs visually

- Works well if you tag issues by feature, milestone, or module

---

## 🧹 **4. SwiftLint**

## Use for

- Enforcing style and code quality automatically in Swift

Install:

```bash
brew install swiftlint
```

Run:

```bash
swiftlint
```

Optional: Integrate into GitHub Actions

---

## 🔍 **5. Dash (local API reference browser)**

### Use Case

- Quickly looking up Apple API docs offline

- Also includes Swift packages, Git, Markdown, etc.

Download: [https://kapeli.com/dash](https://kapeli.com/dash)

---

## 🧰 **6. Postman (if your app will use APIs)**

- For testing APIs before integrating into your app

- Great for mocking responses or testing auth

---

## 📊 **7. Telemetry / Analytics Tools (later stage)**

Consider later when MVPs go live:

- **Firebase Analytics**

- **App Store Connect Metrics**

- **Sentry (crash reporting)**

---

## 📦 Bonus: [Swift Package Index](https://swiftpackageindex.com/)

- Use to find reliable Swift libraries for accessibility, calendar tools, UI components, etc.

- Use **SwiftPM** for clean integration into your Sources folder

---

## ❌ What You _Don't_ Need Yet

- CI/CD platforms like Bitrise or CircleCI (overkill for MVP solo dev)

- Project management suites (Stick to GitHub Issues + Obsidian)

- External design tools (use SwiftUI Previews, screenshots in Screenshots/)

---

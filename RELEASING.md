# Releasing the SDK Mobileproxy

To create a new release, you must run a manual GitHub Action. Follow these steps:

1.  Navigate to the **Actions** tab.
2.  Select the **Draft Mobileproxy Release** workflow.
3.  Click on the **Run workflow** dropdown.
4.  Enter the **Outline Experimental SDK tag** you want to base the release on (e.g., `x/v*.*.*`).
5.  Click the **Run workflow** button. This will trigger a new workflow run that builds the mobileproxy artifacts, updates the `Package.swift` and `build.gradle.kts` files, and creates a new draft release with the generated binaries.
6.  Update the draft release notes and verify that the library works manually.
7.  Publish the release!

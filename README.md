[← Module 4](https://github.com/gtiosclub/bootcamp-module-4) • [Module 6 →](https://github.com/gtiosclub/bootcamp-module-6)

# Module 7: Intro to MVVM and Navigation in SwiftUI

In this module, you'll be building a simple grocery list app from scratch using the Model-View-ViewModel (MVVM) architecture and implementing navigation between views.

#### What you'll accomplish:

- [ ] Understand the basics of MVVM architecture
- [ ] Implement a simple MVVM structure in SwiftUI
- [ ] Add navigation between views
- [ ] Display grocery items using SwiftUI components
- [ ] Add interactivity to your app

## Getting Started

- Clone the repo to your local device
  - You can do this via Xcode or the command line
- If the project isn't already open, navigate to the project folder and open up `SimpleGroceryListApp.swiftpm`
- Run the project to make sure everything is loaded properly
- There should be no errors, and you should be able to see the preview or run the app in the simulator

## Step 0: Understanding MVVM

Before we start coding, let's understand the basic components of MVVM:
- **Model**: Represents the grocery item data and the business logic
- **View**: Represents the UI
- **ViewModel**: Acts as a bridge between the Model and the View, managing the state and logic

In this app, we'll be creating a simple grocery list app to display a list of grocery items and navigate to a detail view for each item.

## Step 1: Setting Up the Model

Navigate to the `Models` folder and create a new Swift file named `GroceryItemModel.swift`. Define a simple model for the grocery items.

#### What you've accomplished so far:

- [ ] Created a basic model for your grocery items

## Step 2: Creating the ViewModel

Navigate to the `ViewModels` folder and create a new Swift file named `GroceryViewModel.swift`. Implement a simple ViewModel to manage the list of grocery items.

#### What you've accomplished so far:

- [ ] Created a ViewModel to manage your grocery items

## Step 3: Building the List View

Navigate to the `Views` folder and create a new Swift file named `GroceryListView.swift`. Implement the list view to display grocery items using SwiftUI components.

#### What you've accomplished so far:

- [ ] Displayed grocery items using SwiftUI components
- [ ] Added navigation to a detail view for each grocery item

## Step 4: Creating the Detail View

Create a new Swift file named `GroceryDetailView.swift` in the `Views` folder. Implement the detail view to display the details of a selected grocery item.

#### What you've accomplished so far:

- [ ] Created a detail view to display more information about a grocery item
- [ ] Implemented navigation to the detail view

## Step 5: Running the App

Now, run the app in the simulator or preview mode. You should be able to navigate between the list view of grocery items and the detail view.

## Conclusion

You've just built a simple grocery list app using the MVVM architecture and navigation in SwiftUI!

#### What you've accomplished today:

- [ ] Understand the basics of MVVM architecture
- [ ] Implement a simple MVVM structure in SwiftUI
- [ ] Add navigation between views
- [ ] Display grocery items using SwiftUI components
- [ ] Add interactivity to your app

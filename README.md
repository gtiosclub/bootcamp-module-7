[← Module 6](https://github.com/gtiosclub/bootcamp-module-6)

# Module 7: Intro to MVVM and Navigation in SwiftUI

In this module, you'll be building a simple grocery list app from scratch using the Model-View-ViewModel (MVVM) architecture and implementing navigation between views.

#### What you'll accomplish:

- [ ] Understand the basics of MVVM architecture
- [ ] Implement a simple MVVM structure in SwiftUI
- [ ] Add navigation between views
- [ ] Create and manage grocery lists using SwiftUI components
- [ ] Add items to your grocery list

## Getting Started
- Clone the stated repository into your local device.
- Open Xcode and create a new SwiftUI project named `SimpleGroceryListApp` inside the stated repository.
- Make sure the project is set up correctly and can be run in the simulator.

## Step 0: Understanding MVVM

Before we start coding, let's understand the basic components of MVVM:
- **Model**: Represents the grocery item data and the business logic.
- **View**: Represents the UI.
- **ViewModel**: Acts as a bridge between the Model and the View, managing the state and logic.

In this app, we'll be creating a simple grocery list app to create and manage a list of grocery items.

## Step 1: Setting Up the Model

1. **Implementation**
 
 - Create a simple model for the grocery items.
 - This could include a multitude of aspects for each item:
     - Name of the specific grocery item
     - The quantity of the grocery item
     - The price of the item
     - Notes for each grocery item
     - The specific category the item belongs on

#### What you've accomplished so far:

- [ ] Created a basic model for your grocery items.

## Step 2: Creating the ViewModel

1. **Implementation**
   
- Implement a simple ViewModel to manage the list of grocery items.
- This would connect to the model created for the grocery items
   - In addition, you have have to ensure that every grocery item created is represented through the model as well

#### What you've accomplished so far:

- [ ] Created a ViewModel to manage your grocery items.

## Step 3: Building the List View


1. **Implementation**

 - Implement the list view to display grocery items using SwiftUI components.
 - Using the app screenshot below, recreate the UI for the Grocery application.
   - Implement the title for the list, similarly to shown below
   - Create an add product button that would connect to the screen mockup in the below section
   - Represent each item added from the other view in the below section
     - Specifically include the quantity for each item, the category, the title, the price, and the notes

  
2. **Mockup**

<img width="259" alt="Screenshot 2024-10-16 at 2 59 42 PM" src="https://github.com/user-attachments/assets/19b679db-7f4d-46b8-b6bb-ec09d66baa4e">

#### What you've accomplished so far:

- [ ] Displayed grocery items using SwiftUI components.
- [ ] Added navigation to create a new grocery list and add items to the list.

## Step 3: Creating the Add Item View

1. **Implementation**

  - Implement the view to add new items to the grocery list.
  - Using the app screenshot below, recreate the UI for the Grocery application.
      - Add an option to add the category for the specific item
      - Add a textbox to add the items name
      - A counter or textbook implementation for the quantity
      - The price for the item
      - The overall notes to add for the specific item

2. **Mockup**

<img width="261" alt="Screenshot 2024-10-16 at 3 00 05 PM" src="https://github.com/user-attachments/assets/e44cdf34-a076-4e75-9123-0f08365628da">

#### What you've accomplished so far:

- [ ] Created a view to add new grocery items.

## Step 5: Running the App

Now, run the app in the simulator or preview mode. You should be able to create a grocery list and add items to the list.

## Conclusion

You've just built a simple grocery list app using the MVVM architecture and navigation in SwiftUI!

#### What you've accomplished today:

- [ ] Understand the basics of MVVM architecture.
- [ ] Implement a simple MVVM structure in SwiftUI.
- [ ] Add navigation between views.
- [ ] Create and manage grocery lists using SwiftUI components.
- [ ] Add items to your grocery list.

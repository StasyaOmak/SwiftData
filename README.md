Wishlist — SwiftData Demo App

A small demo project created to explore SwiftData, Apple’s modern data persistence framework introduced in iOS 17.
This app demonstrates how to create, store, fetch, and delete data using SwiftData together with SwiftUI.

**Features**

- Add new wishes using an alert with a text field

- Save data using SwiftData

- Automatically display wishes with @Query

- Delete items with swipe actions

- Bottom toolbar with item count

- Empty state view using ContentUnavailableView


**Technologies Used**

- SwiftUI

- SwiftData

@Model for defining the data model

@Query for fetching data


**Example Model**
@Model
class Wish {
    var title: String
    
    init(title: String) {
        self.title = title
    }
}

**Running the Project**

Open the project in Xcode 15+

Build and run on a simulator or device with iOS 17+

Add or delete wishes to see SwiftData in action

 **Purpose of the Project**

The goal of this project is to learn the basics of SwiftData:

Creating a data model

Inserting items

Automatically fetching data using @Query

Deleting items

Providing a ModelContainer for previews


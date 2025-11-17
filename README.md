# Wishlist — SwiftData Demo App

A small demo project created to explore **SwiftData**, Apple’s modern data persistence framework introduced in iOS 17.  
This app demonstrates how to create, store, fetch, and delete data using SwiftData together with SwiftUI.

##  Features

- Add new wishes using an alert with a text field
- Save data using SwiftData
- Automatically display wishes with `@Query`
- Delete items with swipe actions
- Bottom toolbar with item count
- Empty state view using `ContentUnavailableView`

##  Technologies Used

- **SwiftUI**
- **SwiftData**
- `@Model` for defining the data model
- `@Query` for fetching data

##  Example Model

```swift
@Model
class Wish {
    var title: String
    
    init(title: String) {
        self.title = title
    }
}

<a href="https://developer.apple.com/swift/"> 
  <img src="https://raw.githubusercontent.com/CardinalJV/CardinalJV/main/assets/logo-swift/swift-96x96_2x.png" alt="Logo Swift" title="Swift" width="68.5" height="68.5"/></a>
<a href="https://developer.apple.com/xcode/swiftui/"> 
  <img src="https://raw.githubusercontent.com/CardinalJV/CardinalJV/main/assets/logo-swift/swiftui-96x96_2x.png" alt="SwiftUI" title="SwiftUI" width="68.5" height="68.5"/></a>
<a href="https://developer.apple.com/xcode/swiftdata/">
  <img src="https://raw.githubusercontent.com/CardinalJV/CardinalJV/main/assets/logo-swift/swiftdata-96x96_2x.png" alt="Logo SwiftData" title="SwiftData" width="68.5" height="68.5"/></a>

# Pokedex

Pokedex is a native iOS application that allows users to view and explore data about Pokémon. The application follows the MVVM (Model-View-ViewModel) architecture and retrieves data from an external package. The interface is designed with SwiftUI, providing a smooth and responsive user experience with animations that enhance the user experience.

## ScreenCast

https://github.com/user-attachments/assets/511b9fdd-3bf1-4b6b-8411-65d43ab7e59b

## Main features

- Displaying Pokemon :
  
The Pokemon are retrieved via an external API.
Each Pokemon is displayed with details such as its type, stats, and image in the PokemonView.swift view.
An interactive list allows you to browse through the Pokemon.

- Asynchronous requests :
  
Using async/await to handle network calls.
Pokémon data is retrieved and processed via PokemonViewModel.swift, which manages the logic for retrieving and processing the information.

- Managing favorites with SwiftData :
  
Users can save their favorite Pokémon using SwiftData.

- MVVM Architecture:
  
The project is structured according to the MVVM architecture for a clear separation between display logic (View) and data management (Model and ViewModel).
The model is retrieved from an external package, where the Pokémon data is modeled.
The business logic and data retrieval are centralized in PokemonViewModel.swift.

- SwiftUI interface :
  
The interface is built entirely in SwiftUI.
@State and @Observable are used to manage state and data in the different views.
Reusable components, such as Pokémon cards, enable smooth navigation and dynamic display.

## Technical detail

- Language: Swift
- Frameworks: SwiftUI / SwiftData
- Architecture: MVVM (Model-View-ViewModel)
- Data retrieval: Using an external package
- Supported iOS version: iOS 14 and above

## Installation

Clone the project from the GitHub repository, then open it in Xcode. Make sure you're using the latest version of Xcode that's compatible with Swift 5, SwiftUI, and SwiftData to avoid any compatibility issues.

## Credits

All Pokémon data comes from the Tyradexkit API.<br/>
https://tyradex.vercel.app

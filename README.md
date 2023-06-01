# WarCardGame

![Simulator Screenshot - iPhone 14 Pro - 2023-05-31 at 11 21 15](https://github.com/TheElementOFLif3/WarCardGame/assets/116418444/3499dc79-4e60-4441-9f9b-d91576bc8c22)
![Simulator Screenshot - iPhone 14 Pro - 2023-05-31 at 11 21 25](https://github.com/TheElementOFLif3/WarCardGame/assets/116418444/a62c2d81-4b5d-412d-a83e-66a1d3b65d3e)


The provided code is practice purpose written in Swift and represents the main view of a card game called "War Card game." Let's break down the code:

1. Import Statements:
   - The code imports the SwiftUI framework, which is used for building the user interface.

2. ContentView Struct:
   - The `ContentView` struct is defined, which conforms to the `View` protocol.
   - It contains various state variables using the `@State` property wrapper to track the current player's card, CPU's card, player's score, and CPU's score.

3. View Body:
   - The `body` property of `ContentView` defines the main user interface for the game.
   - It uses a `ZStack` to layer the different UI elements.
   - The background is set with an image called "background-plain".
   - Inside the `VStack`, the game logo, player's card, CPU's card, and a button are displayed.
   - The player's and CPU's scores are shown in a horizontal stack (`HStack`).

4. deal() Function:
   - The `deal` function is defined to handle the button's action when pressed.
   - Inside the function, the player's card and CPU's card are randomized by generating random integer values between 2 and 14.
   - The randomized values are used to update the respective card images.
   - The scores are updated based on the comparison of the card values.

5. ContentView_Previews Struct:
   - This is a nested struct inside `ContentView` used for previewing the view during development.
   - The `previews` property returns an instance of `ContentView` for previewing purposes.

Overall, this code sets up the main user interface for the "War Card game" and provides functionality to deal cards, update the scores, and display them on the screen.

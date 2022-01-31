## User Stories

1. As a user I want the ability to chat with other players.
2. As a gamer i want to be able to connect and play with other people either competitive or co-op
3. As a user I want to see player actions updated in real-time.
4. As a user, I want to keep scores and display a high score. 
5. As an admin, I want the maintenance costs to be cheap.

## Wireframe

![concepts](https://user-images.githubusercontent.com/89756479/151723804-bcf2d3c7-2c3e-44b2-ae62-02cf1f06721a.PNG)

## Software Requirements

### Vision

What is the vision of this product? Multiplayer cross platform game.
What pain point does this project solve? Boredom, practice with networking/sockets, and allows users to play together even if they're not in the same location.
Why should we care about your product? It weighs heavily on our final grade, we invested time into it, and it was fun to work on.

### Scope (In/Out)
IN - What will your product do

- Users will have access to a chat window.
- The application will allow multiple users to connect through the internet.
- Players will have the ability to play in the same instance of the game.
- A server will connect users (rather than direct peer to peer).
- Players can affect other players' game.

### OUT - What will your product not do.
- It will not make you breakfast.
- The game will only have a server to connect players, and not have the ability to host the game itself.
- Will not have a computer to play against. No AI.
- Single player version will not be different from the multiplayer version. Players can play by themself on the open world.
- Not too dependent on sever speed. Some lag is acceptable to still enjoy the game.

## Minimum Viable Product
- What will your MVP functionality be? Multiple players sharing an experience.
- What are your stretch goals? Users will have persistence / user login, multiple levels, lots of stuff to do, leader boards, upgrades/items.

### Functional Requirements
List the functionality of your product.
- Stretch: An admin can create and delete user accounts.
- Stretch: A user can update their profile information.
- Stretch: A user can search all of the products in the inventory.
- Multiple clients, one server. At least 2 users.
- 2D game of some sort (eg: missile defense, top-down RPG, bullet-hell, diablo-like, etc).

### Data Flow
- Client to server, server processes data from all clients, and sends back the same world data to all clients. Local client is responsible for rendering and updating the game view, while the server is responsible for handling the game state.
- Runs on both mac and windows. All team members should be able to run the game.
- Not too demanding on computer hardware. Game design choices should keep hardware limitations in mind (not too many sprites, world map limited in size, etc).
- Not too demanding for network speed or bandwidth. Game should still be fun to play even if there's half a second of lag or so, so game design choices should keep this in mind.
- Uses Python Arcade for the game engine. Made with python for both client and server.

## Domain Model

![Screen Shot 2022-01-30 at 4 07 28 PM](https://user-images.githubusercontent.com/89756479/151723672-a78409ce-bb48-433e-a00c-847cb49c1a8b.png)

# About Game:-

This game is to teach SOLID principles through an interactive and collaborative Role Playing Game. The game has parts called modules. In each part, the player collaborates with game characters to finish tasks. While doing this, he learns about SOLID principles and why they're important.

## Characters:-

- Noah - Helping NPC(Non Playing Character).
- Alex - Mechanic
- Sara - Queen

## User Controls:-

- Right Arrow - To Move Right.
- Left Arrow - To Move Left.
- Shift - To Dash While Moving.
- ‘Z’ - To attack.
- Space - jump(when the user is not in the vehicle).
- Space - brake(when the user is in the vehicle).
- Double space - Double jump.
- Ctrl - to increase the number of life’s.
- P - to open the parachute attached to the car.
- E - to dismantle the parachute attached to the car.

## Lore:

SRP and OCP
- The narrative commences as the player, taking on the role of the protagonist, discovers a Queen confined within a jail.
- To effect the rescue of the Queen, the player embarks on a quest to locate a key, eventually succeeding in obtaining it.
- At a pivotal juncture, the player faces a choice to either proceed with rescuing the Queen or opt for a Bonus Level.
- Opting for the Bonus Level, the player is endowed with a car and tasked with navigating through challenging terrain.
- After encountering repeated failures, an NPC named Noah suggests seeking assistance from a mechanic named Alex.
- The player visits the mechanic, conveys the predicament, and initially receives advice to enhance the car's engine power.
- The mechanic modifies the engine, but the subsequent attempt results in overheating and destruction.
- Returning to the mechanic, a new approach is suggested – extending the engine power by incorporating boosters.
- Equipped with the modified car, the player successfully traverses the challenging terrain.
- Noah imparts a valuable lesson, emphasizing the importance of extension over modification, citing the Open-Closed Principle.
- The player then retraces steps to where the key was found and proceeds to the location of the Queen's imprisonment.
- To the player's dismay, the Queen is nowhere to be found, prompting the NPC to attribute the failure to the player's diversion from the main responsibility.
- The NPC underscores the Single Responsibility Principle, asserting that the tragedy ensued due to the player deviating from the singular task of saving the Queen.

LSP
- Post the earlier incident, the player resumes the journey and encounters a challenging situation on a slippery road.
- Seeking a resolution, the player once again consults the mechanic to address the current predicament.
- In response, the mechanic enhances the car's tires by introducing additional grip to tackle the slippery surface effectively.
- With the modified tires, the player successfully navigates the slippery road and proceeds to complete the level on a standard surface.
- The player discerns a crucial lesson – the enhanced tires, designed with extra grip, are considered subtypes of normal tires.
- This realization allows for the smooth substitution of gripped tires without necessitating alterations to the car's structure, exemplifying the Liskov Substitution Principle.

ISP
- The game challenges players to navigate a cliff using a car and necessitates the use of a parachute, an unconventional addition to a vehicle.
- Despite the typical absence of parachutes in cars, this game deliberately compels players to employ this unusual method, highlighting the mismatch between functionality and necessity.
- The forced integration of a parachute on a car in the game serves as a clear illustration of the principle that classes, like cars, should not be obligated to implement functions that deviate from their core purpose.
- This gaming scenario underscores the importance of avoiding the imposition of unnecessary methods on classes, emphasizing the need for alignment between a class's capabilities and the functionalities it is required to support.

DIP
- The player encounters an area with specific requirements, dictating the use of an electric engine in certain places and a petrol engine in others.
- To navigate this varied terrain, the player must obtain a hybrid engine by defeating a boss, highlighting the necessity of a versatile power source.
- Upon acquiring the hybrid engine, the player employs a layer of abstraction to seamlessly transition control between the electric and petrol engines.
- This gameplay mechanic underscores the importance of concrete classes, such as engines, relying on abstraction rather than self-dependency. This concept aligns with the Dependency Inversion Principle (DIP), emphasizing the advantages of building dependencies on abstractions rather than concrete implementations.

## System Requirements to run the Game

- 64-bit Windows 10/11 computers

# IZHV-Exercise06-2021

Solution for the 6th assignment from the subject _'IZHV (Introduction to Game Development)'_ for the academic year 2021/22 at VUT FIT. \
Řešení 6. úkolu z předmětu _'IZHV (Základy herního vývoje)'_ pro akademický rok 2021/22 na VUT FIT.

## Task: User Interface

**Objective:** Improve the “Principia Physica” user interface by integrating visual and sound feedback to enhance player-game communication.

- Construct a fundamental menu using Unity GUI.
- Design a responsive inventory with Unity UI Toolkit.
- Create a debugging menu using Unity IMGUI.

[Full Assignment Description](http://cphoto.fit.vutbr.cz/ludo/courses/izhv/exercises/e6/)

#### **Task Steps:**

---

**1. Understand Unity's Visual Systems:**

- Get acquainted with the three main visual user interface systems of Unity:
  - Unity GUI system
  - Unity UI Toolkit
  - Unity IMGUI

---

**2. Project Setup:**

- Download the project [template](./template.zip).
- Follow the procedures established in previous exercises.
- Change to 2D mode in Unity.
- Start with an initial game state of a black screen.

---

**3. Develop the Main Menu:**

_3.1. Dive into Unity GUI:_

- Grasp how Unity GUI integrates with the GameObject hierarchy.
- Learn about the Canvas and its crucial components: Canvas and Canvas Scaler.
- Comprehend the role of Event System in processing user input.

_3.2. Construct the Main Menu:_

- Utilize MainMenuRoot for setting the black background.
- Understand the significance of the Rect Transform component.
- Design a menu background using MMPanel.
- Insert Text and Buttons: MMTitle, MMBtnStartGame, and MMBtnExitGame.
- Conclude with interactive features: highlighting and button depression.

_3.3. Interface UI with Actions:_

- Link MMBtnStartGame with GameManager's StartGame function.
- Bind MMBtnExitGame to GameManager's QuitGame function.
- Program the QuitGame function for appropriate game exit.
- Confirm the functionality of the Start and Exit buttons in both Unity Editor and WebGL build.

---

**4. Unity UI Toolkit Tasks:**

_4.1. Foundation:_

- Navigate to the mentioned GameObject in Unity.
- Explore the UI Document component.
- Dive into the UI Builder window through the InventoryTemplate asset.
- Familiarize yourself with the various segments of UI Builder.

_4.2. Building and Styling:_

- Customize the CREATE button.
- Implement styles for different button states.
- Update the item description functionality.
- Enable and test the CREATE button.

_4.3. Debugging & IMGUI:_

- Activate the dummy character.
- Add cheat functions.
- Implement and test in-game UI elements.

---

**5. Bonus Challenge:**

- Explore Unity's sound system scripts.
- Learn about defining new game asset types.
- Experiment by creating novel items for the player's inventory.

## Result

TBD

## Evaluation

Total points: **6/6**

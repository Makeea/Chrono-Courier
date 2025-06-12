---

## **Core Concept**

You are a time-traveling courier, delivering packages across timelines and realities. You never meet other players directly, but your actions ripple into their stories. What you send, when you send it, and whether it even gets delivered can alter everything.

---

## **Core Game Loop (Player Experience)**

1. **Receive a mysterious package**

   * Includes a brief, cryptic note and strange contents (generated or player-contributed)

   * Might include partial metadata: sender name, timeline ID, etc.

2. **Explore a short story or interactive scene**

   * Each delivery takes place in a unique moment (e.g., an alternate 1998, post-collapse 2147\)

   * Light puzzle, narrative decision, or environmental interaction

3. **Modify or forward the package**

   * Choose what to keep, add, write, or remove

   * Optionally include a note or instructions for the next courier

4. **Choose a destination**

   * Deliver to another timeline, an NPC, or another player

   * The game gives vague or cryptic info about potential branches (player chooses without full clarity)

5. **Branch world state**

   * Outcomes subtly shift the global/shared game state

   * Other players may encounter echoes, relics, or consequences of your actions

6. **Repeat**

   * The game gives you another package with embedded history, including prior players’ input

---

## **Package System**

Packages contain:

* Items (game-generated or inherited)

* Written messages (optional)

* Metadata (player ID, event tags, anomaly flags)

* Delivery tags (destination type, urgency, stability)

Players may only be allowed to keep one item from each package before forwarding the rest. This creates scarcity and trade-offs.

---

## **Networked Features**

* **Persistent player trail:** Packages track how many timelines they’ve passed through and log key transformations.

* **Shared world state:** Certain global anomalies escalate or resolve as players interfere with the timeline.

* **Ghost echoes:** Players can occasionally receive "visual memories" (brief flashes or glitched events) from other players' interactions.

---

## **Gameplay Types**

* **Exploration modules:** Short point-and-click or choice-driven stories inside each delivery moment

* **Puzzle rooms:** Fix broken tech, forge documents, solve riddles tied to package contents

* **Narrative injections:** Add a sentence or label that the next player will see and must interpret

---

## **Interface Style**

* Retro terminal or courier OS-style UI

* Bleepy UI feedback, file corruption effects, old-school progress bars

* Optional voice log entries or glitched transmission overlays

---

## **Narrative Structure: Prologue \+ First 3 Chapters**

### **Prologue: Terminal Wake**

* **Narrative Role:** Onboarding \+ world intro

* **Setup:**  
   You wake up in a locked courier terminal in a dead zone outside known time. A failed delivery has corrupted your memory log. You’re patched into the network by a rogue AI that speaks in riddles and corrupted code.

* **Player Actions:**

  * Choose a name (or inherit one from a past player who "failed")

  * Repair your courier interface

  * Receive your first test package: empty, but tagged with anomaly metadata

* **Gameplay Goals:**

  * Introduce UI, package interface, and notes system

  * Let players write their first message into the system

  * Set tone: fractured time, unreliable memories, unseen overseers

### **Chapter 1: The Fault in Transit**

* **Narrative Role:** First real delivery

* **Setup:**  
   A small package appears in your queue with no sender ID. Its origin: a collapsing timeline marked 4A-98-ECHO. Contents: a pocket watch that ticks backward, and a letter written in mirror script. Something is watching the delivery route.

* **Player Actions:**

  * Choose one of two branching recipients:

    * A historian preserving time anomalies

    * A scavenger is trying to sell the watch for parts

  * Add an object or note to the package

  * Leave behind a message about what you saw (stored for future players)

* **Gameplay Twist:**

  * The package will appear in another player’s game in a future chapter

### **Chapter 2: Echo Relay**

* **Narrative Role:** Reveal the player-to-player mechanic

* **Setup:**  
   You receive a new package. Its contents match your first one—but it’s been altered. The watch ticks forward. There’s a new note inside. It's signed by a player-tag from a previous timeline. Your delivery affects theirs, and vice versa.

* **Player Actions:**

  * Choose which parts to keep, forward, or destroy

  * Encounter a mini-puzzle based on the sender’s note

  * Decide whether to override, erase, or preserve the previous player’s input

* **Gameplay Twist:**

  * You see a glitched “memory fragment” from the sender’s interaction

### **Chapter 3: Courier’s Dilemma**

* **Narrative Role:** Introduce risk and consequence

* **Setup:**  
   You’re offered a high-priority package flagged as a "Chrono Anomaly." It’s marked as dangerous and unstable. Completing the delivery may reward you, but corrupting it may remove you from the network. You can also forward it to another player to decide instead.

* **Player Actions:**

  * Inspect volatile metadata and incomplete instructions

  * Choose to:

    * Deliver as is (risky)

    * Alter contents (unknown effect)

    * Pass it forward with a warning or fake label

* **Gameplay Twist:**

  * What you do determines whether future packages are “clean” or “tainted”

  * Begins the idea of Courier “alignment”: archivist, manipulator, saboteur

---

## **Optional Narrative Motifs**

* “The Network is Watching” – subtle hints that the courier system may be sentient or compromised

* “Dead Routes” – timelines that no longer accept packages, but still send out broken ones

* “Courier Reclamation” – players who disappear might reappear later as corrupted NPCs or system ghosts

---

## **Chrono Courier – Online Gameplay System**

This is asynchronous multiplayer, where players leave behind traces, edit packages, and influence others through a shared backend, but never occupy the same timeline in real-time.

### **Core Networked Elements**

1. **Package Chain System**

   * Each delivery object has a unique Package ID

   * Tracks: creation origin, route history, sender/player tags, metadata mutations

   * Players can add, modify, or erase content

   * System stores a maximum of N player entries per package (e.g. ,3–5 deep)

2. **Player Influence via Timeline**

   * Each player has a timeline state (subtle alignment: archivist, meddler, courier, chaos)

   * Deliveries made influence global event flags (e.g., “Has Timeline 3 B-Delta received the Catalyst?”)

   * The backend assigns deliveries to compatible timelines based on:

     * Recent choices

     * Player alignment

     * Anomalies introduced or resolved

3. **Echo Memory System**

   * Optional player-generated logs get stored as “echo fragments.”

   * Future players receive glitched or partial playback of previous interactions

   * Examples:

     * A sentence

     * A visual glitch (if visual UI is present)

     * A delayed “ghost message” from the sender

4. **Global Network Variables (Soft MMO Layer)**

   * Persistent shared variables:

     * “Delivery Stability Index” (based on % of corrupted packages)

     * “Anomaly Spread” (measured by presence of blacklisted items)

   * When thresholds hit, the server sends altered packages to players

   * This allows emergent world events from collective behavior

5. **Multiplayer-Influenced Content Routing**

   * Players never choose exact recipients but select vague “targets”:

     * “A stable alternative”

     * “A version of me that failed.”

     * “Someone lost in transit.”

   * The backend selects a real player from a queue that matches that prompt

6. **Passive Multiplayer Interactions**

   * Players can:

     * Receive packages touched by other players

     * Read their notes, inherit their altered items, or witness their impact


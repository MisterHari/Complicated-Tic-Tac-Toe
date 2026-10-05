# Complicated-Tic-Tac-Toe
Image play a game of Tic Tac Toe on a cube with many rules

this is just a base model 

# 🎲 Cube Tac Toe

**Cube Tac Toe** is a 3D twist on the classic Tic-Tac-Toe game. Instead of playing on a single 3×3 board, players compete across **all six faces of a cube**, creating a game that requires spatial thinking, planning, and strategy.

The game is designed for **two players**: ❌ **X** and ⭕ **O**. Players take turns placing their symbol on any available square of the cube while managing face cooldowns and corner restrictions.

The objective is simple:

> **Create three in a row OR control two opposite physical corners before your opponent does.**

---

## 🎮 How to Play

The cube has **6 faces**, and each face contains a **3×3 grid**.

On your turn:

1. Choose any available face of the cube.
2. Select an empty square.
3. Your symbol (❌ or ⭕) is placed there.
4. The turn passes to the other player.
5. Continue until one player meets a winning condition.

You can **rotate the cube** using the direction buttons or by dragging the cube with your mouse to view the different faces.

---

## 🏆 Winning Conditions

There are **two ways to win**.

### 1. Three in a Row

Place three of your symbols in a straight line on **any single face**.

Lines can be:

```text
❌ ❌ ❌

❌
❌
❌

❌
  ❌
    ❌
```

The first player to create a valid three-in-a-row wins immediately.

---

### 2. Two Opposite Physical Corners

The cube has **8 physical corners**.

Each physical corner touches three different faces, but it counts as **one corner**.

If you control **two opposite corners**, you win immediately.

The opposite corner pairs are:

```text
A ↔ C
B ↔ D
E ↔ F
```

For example, controlling **A and C** gives you a win.

---

## 🔒 Face Cooldown

To prevent players from repeatedly using the same face, the game has a **5-move face cooldown**.

When you play on a face, that face becomes unavailable to **you** for your next **5 moves**.

However, your opponent can still play on that face.

### Example

If X plays on the **Front** face:

```text
X → Front

Front 🔒 for X
        ↓
X must use another face
        ↓
After X's next 5 moves
        ↓
Front becomes available again
```

Cooldowns are **independent for each player**.

---

## 🚫 Corner Restriction

Corners have an additional restriction.

If you play on a corner, your **next move must be a non-corner move**.

For example:

```text
Corner
   ↓
Non-Corner
   ↓
Corner allowed again
```

This restriction applies separately to each player.

---

## 🔄 Cube Controls

The cube can be viewed from different angles using:

| Control  | Action                 |
| -------- | ---------------------- |
| ↶        | Rotate left            |
| ↷        | Rotate right           |
| ↑        | Rotate up              |
| ↓        | Rotate down            |
| 🖱️ Drag | Freely rotate the cube |

You can also select a face directly from the **Choose Face** panel.

---

## 🧠 Strategy

Cube Tac Toe is more than traditional Tic-Tac-Toe because you have to think about the entire cube.

During every turn, consider:

* Can I create **three in a row**?
* Can I capture an important **physical corner**?
* Can I stop my opponent from getting two opposite corners?
* Which face should I play on?
* Will using this face put it on **cooldown** when I need it later?
* Should I take a corner now, knowing my next move must be non-corner?

The combination of **3D positioning, cooldowns, and corner control** makes every move important.

---

## 📜 Rules Summary

1. The game is played by **two players: X and O**.
2. The cube has **6 faces**, each containing a **3×3 grid**.
3. Players take turns placing their symbol in an empty square.
4. **Three symbols in a row on any face = win.**
5. **Two opposite physical corners = win.**
6. Playing on a face locks that face for that player's next **5 moves**.
7. The opponent can still use a face while it is on your cooldown.
8. After playing a corner, your next move must be **non-corner**.
9. Corner and cooldown restrictions apply **independently to each player**.
10. The game ends immediately when a player satisfies either winning condition.

---

## 🎯 Objective

Think ahead, control the cube, manage your cooldowns, and outsmart your opponent.

**Three in a row. Two opposite corners. One winner.**

### 🧊 Welcome to Cube Tac Toe.


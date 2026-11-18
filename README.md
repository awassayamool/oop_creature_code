# Creature Battle Project (OOP + Git Branching Practice)

This project is designed to help me learn **object-oriented programming** in Python — especially **inheritance** — while also practicing key **Git concepts** like branching, merging, conflict resolution, and version history.

I will begin with a base class (`Creature`) and create additional subclasses on separate Git branches to simulate a real development workflow.

---

## Learning Objectives

### Python / OOP
- Understand and implement **classes**
- Use **inheritance** to extend behaviors
- Override and extend methods (e.g., `attack()`)
- Practice writing simple test code in `main`

### Git / Version Control
- Create and switch branches
- Merge branches into `main`
- Resolve merge conflicts
- View commit history (`git log --graph --all`)


---

## Project Structure
oop_creature_code/
│
├── creature_simulation.py # Base class + subclasses
└── README.md

## Project Structure
```
oop_creature_code/
│
├── creature_simulation.py   # Base class + subclasses
└── README.md
```

## How to Run and Test

1. Make sure Python 3 is installed.
2. Open a terminal in the `oop_creature_code` folder.
3. Run:
   ```
   python creature_simulation.py
   ```
4. The test code runs in the `if __name__ == "__main__":` block. Each line reads "should be ... → Actual: ...", so the two values should match.
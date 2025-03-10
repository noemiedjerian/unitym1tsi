# 🎮 RPG Game Development Task List

## 📌 Project Setup
- [ ] Open Unity Hub and create a new project
- [ ] Select the **3D** template
- [ ] Name the project **RPG**
- [ ] Choose a save location
- [ ] Click **Create** and wait for Unity to launch
- [ ] Explore Unity's interface (Scene, Hierarchy, Inspector, Project)

## 🌍 World Creation
### Terrain Setup
- [ ] Create a terrain in **GameObject → 3D → Terrain**
- [ ] Import terrain textures from Unity Asset Store
- [ ] Adjust terrain size in **Inspector**
- [ ] Use **Paint Terrain** to:
  - [ ] Add mountains
  - [ ] Modify elevation (left-click to add, Shift + left-click to remove)
  - [ ] Smooth terrain for better visuals

### Environment Decoration
- [ ] Import assets (trees, bushes, rocks, houses)
- [ ] Create a **Prefabs** folder in `Assets`
- [ ] Add colliders to prevent characters from passing through objects
- [ ] Use **Paint Trees** to distribute trees across the terrain

## 🏃‍♂️ Character Creation
### Avatar Integration
- [ ] Import a character model from:
  - [ ] **Mixamo**
  - [ ] **Ready Player Me**
  - [ ] **Unity Asset Store**
- [ ] Adjust character size
- [ ] Attach the **Camera** to follow the character

### Character Physics
- [ ] Add a **Rigidbody** (freeze rotations)
- [ ] Attach a **Capsule Collider** for collision detection

### Character Movement Script (`CharacterMotion.cs`)
- [ ] Create and attach the movement script
- [ ] Declare variables:
  - [ ] Animation states: **Idle**, **Walk**, **Run**
  - [ ] Movement speeds: `walkSpeed`, `runSpeed`, `turnSpeed`
  - [ ] Input keys for movement (`inputFront`, `inputBack`, etc.)
  - [ ] Jump mechanics (`jumpSpeed`, `IsGrounded()` function)
- [ ] Implement character movement:
  - [ ] Translate movement using `transform.Translate`
  - [ ] Rotate character with `transform.Rotate`
  - [ ] Play correct animations based on movement
- [ ] Implement **sprint** (Shift + move forward)
- [ ] Implement **jumping** with `IsGrounded()`

---

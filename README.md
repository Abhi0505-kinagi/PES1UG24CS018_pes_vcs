
---

## 📝 1. Project Title

```markdown
# PES Version Control System (PES-VCS)
```

---

## 📌 2. Description

```markdown
A simplified Git-like Version Control System implemented in C.

This project supports:
- Object storage (blobs, trees, commits)
- Staging area (index)
- Basic commands like init, add, commit, status, and log
```

---

## ⚙️ 3. Features

```markdown
## Features

- Initialize repository (`pes init`)
- Stage files (`pes add <file>`)
- View status (`pes status`)
- Create commits (`pes commit -m "message"`)
- View commit history (`pes log`)
- Object storage using SHA-256 hashing
```

---

## 🛠️ 4. How to Build

````markdown
## Build Instructions

```bash
make clean
make all
````

````

---

## ▶️ 5. How to Run
```markdown
## Usage

### Initialize repository
```bash
./pes init
````

### Add file

```bash
./pes add file.txt
```

### Check status

```bash
./pes status
```

### Commit

```bash
./pes commit -m "first commit"
```

### View log

```bash
./pes log
```

````

---

## 🧪 6. Testing
```markdown
## Testing

Run test cases:

```bash
./test_objects
./test_tree
./test_sequence.sh
````

````

---

---

## 📸 7. Screenshots (VERY IMPORTANT for marks)

### Build Output
<img src="img3.png" alt="Build Output" width="600">

### Repository Initialization
<img src="img4.png" alt="Repository Initialization" width="600">

### Adding Files
<img src="img5.png" alt="Adding Files" width="600">

### Status Output
<img src="img10.png" alt="Status Output" width="600">
<img src="img6.png" alt="Status Output" width="600">

### Object Storage
<img src="img9.png" alt="Object Storage" width="600">

### Commit Output
<img src="img7.png" alt="Commit Output" width="600">

### Log Output
<img src="img8.png" alt="Log Output" width="600">

---
```
images/
```

---

## 📂 8. Project Structure

```markdown
## Project Structure

- object.c / object.h → Object storage
- tree.c / tree.h → Tree structure
- index.c / index.h → Staging area
- commit.c / commit.h → Commit handling
- pes.c → CLI interface
```

---

## ⚠️ 9. Known Issues (optional but good)

```markdown
## Known Issues

- Limited support for nested directories
- Basic error handling
```

---

## 👨‍💻 10. Author

```markdown
## Author

Abhishek H Kinagi  
PES University
```

---

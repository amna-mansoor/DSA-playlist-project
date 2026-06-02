# 💿 Legacy Playlist Manager (Java)
**A foundational exploration of Data Structures and Algorithms.**

This repository contains the legacy codebase for a console-based Music Playlist Management System. It served as the architectural foundation for the Software Re-engineering Project, **[Aurora Tunes](https://github.com/amna-mansoor/aurora-tunes)**, demonstrating the fundamental concepts of data organization and retrieval.

### 🧩 Core Data Structures Implemented
This project was designed to demonstrate the efficiency of classical DSA in a practical application:

*   **Queue (FIFO):** Managed the ordered playback sequence of songs.
*   **Stack (LIFO):** Powered the "Undo" functionality to remove the most recently added track.
*   **AVL Tree:** Provided a self-balancing Binary Search Tree to enable $O(\log n)$ song searching.
*   **Insertion Sort:** Implemented to maintain alphabetical ordering within the playlist.

### ⚙️ Technical Highlights
*   **Language:** Java
*   **Persistence:** Utilized Java Serialization to save and load playlist states via binary `.obj` files.
*   **Interface:** Terminal-driven menu system with sequential processing.
*   **Architecture:** Monolithic design, demonstrating core object-oriented principles.

### 🎓 Academic Context
Developed as part of the Data Structures and Algorithms coursework, this project explores how to manage data efficiently without a database. While limited by its local-machine environment, it provided the essential blueprint for the algorithmic mapping (Queue to Firestore, AVL Tree to Spotify Search) used in my modern re-engineered platform.


# Lab Practical Day_07
---
# 2020ICT107
---

This project demonstrates **parent-to-child** and **child-to-parent communication** in React using **props** and **state**. It is implemented with functional components.

---

## Features
- **Parent Component** sends a function as a prop to the child.
- **Child Component** invokes the function to send data (a name in this example) back to the parent.
- Demonstrates the core concepts of props and state management in React.

---

## Installation and Setup

### Prerequisites
- Node.js installed on your system. [Download Node.js here](https://nodejs.org/).

### Steps to Run

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-folder>
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the React development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## File Structure
```
src/
├── App.js          # Parent component
├── Childcom.js     # Child component
```

---

## How it Works
1. **App Component (Parent)**:
   - Maintains a state `childname` initialized with "Default".
   - Passes the `receiveName` function as a prop to `Childcom`.

2. **Childcom Component (Child)**:
   - Receives `receiveName` as a prop and invokes it with a string (`"My Name is Bob"`).

3. **Communication Flow**:
   - The child component sends data (`"My Name is Bob"`) to the parent.
   - The parent updates its state and reflects the change in its render output.

---

## Example Output
![image](https://github.com/user-attachments/assets/a91065f5-a98b-4f83-88b2-3eed450e9e72)


---

## Technologies Used
- React.js
- JavaScript 




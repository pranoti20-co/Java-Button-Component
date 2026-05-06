# 🔘 Java Button Component (AWT & Swing)

This project demonstrates how to use **Buttons in Java GUI** using AWT and Swing.

---

## 📌 What is a Button?

A **Button** is a UI component used to perform an action when clicked.

✔ Click → Action happens  
✔ Used in forms, apps, games  

---

## 🎯 Where Buttons Are Used

- Desktop Applications  
- Forms (Submit/Login)  
- Games  
- User Interfaces  

---

## 🔄 Types of Buttons in Java

1. **AWT Button**
2. **Swing JButton**

---

## ⚙️ Example: Button with ActionListener

```java
import javax.swing.*;
import java.awt.event.*;

public class ButtonExample {
    public static void main(String[] args) {

        JFrame frame = new JFrame("Button Action");

        JButton button = new JButton("Click Me");
        button.setBounds(100, 100, 120, 40);

        // Action when button is clicked
        button.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                JOptionPane.showMessageDialog(frame, "Button Clicked!");
            }
        });

        frame.add(button);
        frame.setSize(300, 300);
        frame.setLayout(null);
        frame.setVisible(true);
    }
}
```

---

## 🖥️ Output

- A window appears with a **"Click Me"** button  
- Clicking it shows → **"Button Clicked!"**

---

## 🚀 How to Run

### Compile:
```
javac ButtonExample.java
```

### Run:
```
java ButtonExample
```

---

## ⭐ Key Features

✔ Simple GUI  
✔ Event handling  
✔ Beginner-friendly  

---

## 👩‍💻 Author

**Pranoti Patil**  
Aspiring Software Developer  

---

## 📌 Connect

Feel free to connect and share feedback!

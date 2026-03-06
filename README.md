**1. Intent**
Intent is a messaging object used in Android to request an action from another component.
It is commonly used to start an Activity, Service, or send a Broadcast.
There are two types: **Explicit Intent** (specific component) and **Implicit Intent** (system chooses suitable app).

---

**2. Adapter**
Adapter acts as a bridge between **data source** and **UI components** like ListView or RecyclerView.
It converts data into a format that UI elements can display.
Example: `ArrayAdapter`, `RecyclerView.Adapter`.

---

**3. Threads**
A thread is a lightweight process used to perform tasks in the background.
In Android, long operations like network calls run on background threads to avoid freezing the UI.
The main thread is called the **UI Thread**.

---

**4. Event Listener**
Event Listener is an interface used to handle user actions such as clicks or touches.
It waits for an event and executes code when the event occurs.
Example: `OnClickListener` for button clicks.

---

**5. Broadcast Receiver**
Broadcast Receiver is a component that responds to system-wide broadcast messages.
It listens for events like battery low, network change, or device boot.
It works using the `onReceive()` method.

---

**6. Android Programming**
Android programming is the process of developing applications for Android devices.
It uses languages like **Java or Kotlin** and Android SDK tools.
Apps are built using components like **Activities, Services, Broadcast Receivers, and Content Providers**.

---

**7. Kotlin**
Kotlin is a modern programming language officially supported for Android development.
It is concise, safer, and reduces boilerplate code compared to Java.
It runs on the **Java Virtual Machine (JVM)** and is fully compatible with Java.

---

**8. Toast Message**
Toast is a small popup message used to show quick feedback to the user.
It appears for a short duration and disappears automatically.
Example: “Login Successful”.

---

**9. Fragment**
Fragment is a reusable UI component inside an Activity.
It represents a portion of the screen and helps build flexible UI designs.
Multiple fragments can be combined in one Activity.

---

**10. Activity**
Activity represents a single screen with a user interface in an Android app.
It acts as the entry point for user interaction.
Example: Login screen or Home screen.

---

**11. XML in Android**
XML (Extensible Markup Language) is used to design UI layouts in Android.
It defines elements like buttons, text views, and layouts.
Separating UI (XML) and logic (Java/Kotlin) makes apps easier to manage.

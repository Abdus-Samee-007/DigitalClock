### DigitalClock

#### Project Description

This is a simple digital clock application built using Java. The application provides a real-time display of the current time, day, and date in a user-friendly graphical interface. It is designed to be a standalone desktop application that is easy to run and provides essential time-related information at a glance.

#### Features

* **Real-time Clock:** Displays the current time in a `hh:mm:ss a` format that updates every second.
* **Current Day and Date:** Shows the current day of the week and the full date.
* **Graphical User Interface (GUI):** A simple and clean GUI built with Java's Swing library.
* **Customizable Display:** The different components of the clock (time, day, date) have distinct fonts, sizes, and colors for better readability.
* **Persistent Display:** The clock runs continuously in a loop, ensuring the displayed time is always accurate.

#### How It Works

The application utilizes Java's `Calendar` and `SimpleDateFormat` classes to get the current time, day, and date. A `while(true)` loop with a `Thread.sleep(1000)` call ensures the clock updates every second, providing a real-time display. The graphical components are built using `javax.swing` to create a `JFrame` and `JLabel`s to display the information.

#### Tech Stack

* **Language:** Java
* **Libraries:** `java.awt`, `javax.swing`

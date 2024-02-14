# CS2613: De,Aritra Library Experience Exploration Activity 1


5. Why did you select this package/library?
• “Because it is interesting” is not a valid answer. Should elaborate more.
6. How did learning the package/library influence your learning of the language?
7. How was your overall experience with the package/library?
• When would you recommend this package/library to someone?
• Would you continue using this package/library? Why or why not?


# Question and Answers (included below)

## Table of Contents
- [Introduction](#introduction)
- [Questions related to Library Experience](#questions)

## Introduction
This document provides my overall experience with Tkinter library and answers the provided qusetions.

## Questions

### General Questions
<details>
<summary>Which package/library did you select?</summary>
<p>

- I used the Tkinter standard GUI (Graphical User Interface) library for Python. 

</p>

</details>

<details>
<summary>What is the package/library?</summary>
<p>

- Tkinter library provides an object-oriented interface to the Tk GUI toolkit. I did not have to download as it is included with most Python installations, and it's widely used for creating simple and effective GUI applications due to its ease of use and the availability of comprehensive documentation.
- It is the primary module used to create GUI applications. It must be imported into our Python script to use its functionalities.

</p>
</details>

<details>
<summary>What purpose does it serve?</summary>
<p>
  
- Tkinter served the purpose of helping me develop a weather application which can provide user-friendly interface and observe dynamic upadtes.
- I used special labels and frames to configure my data points properly.
- It also helped me to integrate my application wit third party website and handles API requests.

</p>
</details>

<details>
<summary>How do you use it?</summary>
<p>
  
- In accord to my source code, I used it primarily for the visual represenatation of my weather data.
- I did face some issue while importing and using the libraries but I updated my certificate credentials temporarily
  to make use of the application.
- After creating the main application window (Tk), I added widgets to the application.
- My function also handled events and configured the labels properly to reflect the dynamic changes.
- I found the building blocks like including buttons, labels, frames to be easy to use and manage. Each widget in Tkinter is actually a Python class.

</p>
</details>

<details>
<summary>What are the functionalities of the package/library?</summary>
<p>
- Tkinter has great versatility and its functionality could be used to make easy frameworks like to-do lists, get reference, calculator, etc.
- This is the general template:
  import tkinter as tk
  def greet():
      print("Hello World!")
  
  # Create the main window
  root = tk.Tk()
  root.title("Simple code")
  
  # Create a button widget
  greet_button = tk.Button(root, text="Greet", command=greet)
  greet_button.pack()
  
  # Start the Tkinter event loop
  root.mainloop()


 - With good experience one can make a game in Tkinter. Example: 
    <img width="647" alt="Screenshot 2024-02-13 at 11 51 34 PM" src="https://github.com/CS2613-WI24-FR01B/exploration-activity-1-aritrade001/assets/114476308/d2f16e1d-08db-41f2-ae00-028a08fdd72f">
 - Just like my application, we could also make File Explorer: Navigate and manage the filesystem, Chat Application: Implement client-server chat interfaces.
   , and Music Player: Play, pause, and manage music files.
</p>
</details>

<details>
<summary>When was it created?</summary>
<p>
  
- Tkinter, as a Python interface to the Tk GUI toolkit, was introduced with Python version 1.0 in January 1994. Tk itself, which Tkinter wraps, was created by John Ousterhout in 1988.

</p>
</details>

<details>
<summary>When was it created?</summary>
<p>
- I selected this because it helps me as a beginner to explore the libary and it is easy to use. For my application, it required heavy GUI dashboard and this was a 
  good investment on time and energy. There was lot of open source documentation on the internet.
- It has cross-platform use case benefit and lot of videos on Youtube also supported my ideology.
- The standard library is also under python, so it does not make me worry about external installs.
</p>
</details>










## Asking Questions
If you have a question that's not listed, please:
- Check the existing [issues](#) to see if it has already been asked.
- If not, create a new issue and provide as much detail as possible to help others understand your question.

## Answering Questions
If you can answer a community question:
- Provide clear, concise, and helpful responses.
- Reference relevant parts of the documentation or code.
- Include examples or links to more information if possible.

## Contributing
Your contributions to improving this Q&A are welcome! Make sure to follow our contribution guidelines.
This project was a result of extensive research over the internet and youtube. I faced significant challenges in the last minute
to manage my certificate credentials in order to access the inner functional html calls. The best solution is to update your configurations internally in the terminal for the certificate. Do NOT edit your code as bypassing the control structures can lead to serious security implications.

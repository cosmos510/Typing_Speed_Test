# Typing Speed Test
This is a simple application that allows you to check your typing speed. It offers two levels of difficulty, both of which consist of a randomly generated sample of 20 words. The easy mode uses a text file of the most common English words, while the hard mode uses the english_words library.

## Getting Started
1. Clone the repository:

       git clone https://github.com/cosmos510/Typing_Speed_Test.git
2. Change directory into the project folder
3. Create virtual environment:

       py -m venv ven
       venv/Scripts/activate
4. Install the requiered packages:

       pip install -r requirements.txt

To get started, simply run the main.py file. The app will launch and display the starting screen:

![Screenshot 2023-12-15 at 15 58 39](https://github.com/cosmos510/Typing_Speed_Test/assets/149656366/448c8e15-45de-4f8d-9759-92233b113366)

## Features

### Instruction Screen

If you need instructions on how to use the app, you can click the "Instructions" button to display the instruction screen:

![Screenshot 2023-12-15 at 15 59 06](https://github.com/cosmos510/Typing_Speed_Test/assets/149656366/c9388134-daee-4220-9188-4ab9c820477b)

### Test Screen

Once you start the test, you will be presented with a screen that looks like this:

![Screenshot 2023-12-15 at 15 59 28](https://github.com/cosmos510/Typing_Speed_Test/assets/149656366/9ea7082d-be53-41fc-9e8e-7cbd20ffa6bc)

The text box at the bottom is where you type your response to the randomly generated text at the top. The app will keep track of your words per minute (WPM), net words per minute (NET WPM), characters per minute (CPM), and accuracy. The score board at the top of the screen will update as you type.

### Ckeck Spelling

If you make a mistake, the app will show the incorrect character in red and the correct character in white. The app will also add up the number of mistakes you make and show it in the "Mistakes" box. You can use the backspace key to correct your mistakes.

![Screenshot 2023-12-15 at 16 00 28](https://github.com/cosmos510/Typing_Speed_Test/assets/149656366/9ba4ae9f-fc1b-4b29-893d-ee360c28e328)

### End of Test

Once you have finished typing the text, the app will display your results in a message box:

![Screenshot 2023-12-15 at 16 03 06](https://github.com/cosmos510/Typing_Speed_Test/assets/149656366/5999cfe8-c6ee-4ff7-9b22-0ed618885a59)

The app will also save your highest NET WPM score in the data.txt file.

## Requirements

This app requires Python 3 and the following Python packages:

- Tkinter
- english_words







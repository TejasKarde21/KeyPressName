# KeyPressName

document.addEventListener("keydown", (e) => { ... });: This line of code adds an event listener to the entire document
(webpage) that listens for the "keydown" event. When a key is pressed and released, this event is triggered.
(e) => { ... }: This is an arrow function that defines the event handler. The e parameter represents the 
event object, which contains information about the key event, such as which key was pressed.

Inside the event handler function:
a. const key_name = e.key;: This line extracts the name of the key that was pressed and stores
it in the key_name variable. For example, if you press the "A" key, key_name will be set to "A".

b. const key_number = e.keyCode;: This line extracts the numeric key code of the 
key that was pressed and stores it in the key_number variable. The keyCode property represents the unique code associated with each key on the keyboard.

c. document.getElementById("key-name").innerText = key_name;: This line updates the text
content of an HTML element with the id "key-name" to display the name of the pressed key.
It sets the inner text of that element to the value stored in the key_name variable.

d. document.getElementById("key-number").innerText = key_number;: Similarly, 
this line updates the text content of an HTML element with the id "key-number" to display the numeric key code of the pressed 
key. It sets the inner text of that element to the value stored in the key_number variable.

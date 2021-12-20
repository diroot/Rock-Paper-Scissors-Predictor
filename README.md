# Rock-Paper-Scissors-Predictor

  Server and Client uses socket to communicate strings between each other to know what to do/expect. Ports 10000, 10001, and 12345 are used for this assignment. Settings to train the data are the same as the multiclass_image_classification.ipynb file.
  
  Both were tested using PyCharm community.
Images are expected to be in the same folder as the .py files.
prs.h5 must be in the same folder as the .py files.
The trained model is too large for upload and the one used for tested is available here: https://drive.google.com/file/d/1EBT0KhFCP-Ya_GWMXPGZUkq4B5KX-IyZ/view?usp=sharing 

Run both client and server files.
Wait for the server to print “The server is ready to receive”. (“quit” and “commands” will still work)
Once it has printed the statement the client may send data to the server.
“client” will send the request to the server and the server will return the string to print on the client.
“client *” will print like above but will also send an image to test to the server. Server will return what it predicts to the client to display to the user.
	* must include the file type of the file you are sending such as “shake.jpg.”
“commands” will print out the commands and descriptions on the client side.
“quit” will shut down both the server and client.

# Decision Made


The Application is meant to be worked as a private network the main thing is that in the dapp the Doctors and the patients are the two key peoples who is using it. The doctors have multiple number of patients and the patients will have only one doctor. The addressing is done in away that the first 6 characters of the address represents the doctor and the next 6 characters represents the patients id. When a doctor need to see the list of patients he treated he just need to enter the id given to him in the network. In case of the patients to get his treatment details he need to enter the doctors id which he has taken treatment from and his unique id.


In case of login the permitted key is allowed to login and a session for the key is stored if any other users gets to the doctors dashboard using the url he will be able to reah there but the session storage will not be there and to add the patients details you need to have a privatekey which is taken from the session storage so any other persons exepts the persons with the valid key will not be able to write to the state.


# BB84_Simulation
In this project I have implemented the BB84 quantum key encryption algorithm using python. <br>

<br><h3>Description of Programs</h3>

<br><b>Qubit.py</b><br>
This is the module where the qubit object is created. Here, I've defined the rotation of the qubits and photons using a qubit object.<br>
<br><b>Alice.py</b><br>
This module includes features such as creating the key and measuring the rotation of the qubits from bob.<br>
<br><b>Bob.py</b><br>
This bob is in charge of creating the photon sequence and defining the spin of the qubits. We'll also build the key in terms of bytes, which are equivalent to 8 bits.<br>
<br><b>Eve.py</b><br>
This is an optional module if we add this argument the eavesdropper will be present and we will get the changed sequence of the qubits when transferred.<br>
<br><b>main.py</b><br>
This module is the project's main function, and it's from here that we'll run the code. There is also a technique for displaying all of the project's choices. The bob will send the qubits first, and then the alice will measure them. If Eve is added, the qubits will be changed. After that, bob will compare the orientations sent by Alice, and the two of them will build keys and compare them. And it determines whether or not the eve is present.<br>

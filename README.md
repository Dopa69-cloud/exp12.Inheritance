CODE 1
1.Start program.

2.Define class Vehicle:

public data member brand initialized to "Ford".

public member function color() that writes "red" to standard output.

3.Define class car that publicly inherits Vehicle:

public data member model initialized to " Mustang" (note the leading space).

In main():

4.Create an object c of type car. This object contains brand and model.

Call c.color(). This prints the string "red" to the console (no newline).

Evaluate c.brand + " " + c.model to produce a single std::string and send it to cout.

5.Return 0 and exit program.
Start program.

CODE 2:
Define class Vehicle:

public member company initialized to "FORD".

public method type() that prints Mustang followed by a newline.

Define class Specs:

public member mileage initialized to "8 kmpl".

public method color() that prints Grey followed by a newline.

Define class Car that publicly inherits from both Vehicle and Specs:

public member seater initialized to "4 seater".

In main():

Construct an object f2 of type Car.

Call f2.color() → runs Specs::color() and prints Grey + newline.

Output f2.company followed by a single space (no newline).

Call f2.type() → runs Vehicle::type() and prints Mustang + newline.

Output (, then f2.seater, then ) and a newline.

Output the literal "mileage:" immediately followed by f2.mileage and a newline.

Return 0 (program exits).

Line-by-line mapping (what each key line does)

Car f2; → constructs f2 with company="FORD", mileage="8 kmpl", seater="4 seater".

f2.color(); → prints Grey and newline.

cout << f2.company << " "; → prints FORD and a single space (no newline).

f2.type(); → prints Mustang and newline (so line becomes FORD Mustang).

cout << "(" << f2.seater << ")" << endl << "mileage:" << f2.mileage << endl;

prints (4 seater) then newline,

prints mileage:8 kmpl then newline.

Program output (exact lines)
Grey
FORD Mustang
(4 seater)
mileage:8 kmpl


2.1 class

Mistake ongso
let name;
console.log(name);

right ongso
let name = 'Mosh';
console.log(name);

# modern language a sob alada alada lekha hoi.

some note;
console.log(name); in this bracket like (name)
01. cannot be a resensive key word.
02. should be meaningfull.,
03. cant start with a number. (1name
04. cant contain a space or hypen.
05. are case-senitive.

2.2 calass (constant)

right code..
let interstRate = 0.3;
interestRate = 1;
console.log(interestRate);

wrong code.. (beacuse let er jaigai const use kora)
const interstRate = 0.3;
interestRate = 1;
console.log(interestRate);

2.3 (primitive type) 2.3 te aita meay alochona. onno ta hosse Dynamic type.
A.......primitive type/Value type
01. string--onekta naam tyer
02. Number--jekono number typer. like A. floating B. Imagine....java script ai 2 dhoron er e hoi.
03. Boolen--ait a asole jekono sortho sapekkho bisoy bojhai.
04. Undefiend--onno 4 ta point chara jyta thake oitai Undefine type.
05. Null--null bolte konokicu onirdharito vabe prokas. jmn Red Green Blue 3 ta color onirdharito vabe bojhano.


let name = 'Mosh';
console.log(name);.........Sring type

let age=30;
console.log(age);..........Number Type

let isApproved = true;
console.log(isApproved);...Boolean Type

let firstName = undefine;
console.log(firstName);....run hoina tai undefine

last.A
let selectedColor = ['red', 'green'];
console.log(selectedColor);

last.B
let selectedColor = ['red', 'green'];
console.log(selectedColor[1]);

last.C
let selectedColor = ['Red', 'green'];......Color ghulo non case-sensetive.
selectedColor[2] = 'Blue';....ekhane blue er jaigai j kono number dile, sei number e output a uthbe.
console.log(selectedColor);

note: [2]...aita asole 2 number obostan nirdesh kore. 0 number Red, 1 number green, 3 number blue.
alra [10] dile [10] number oobostane Blue dekhabe r majher 7 ti empty file dekhabe.
...........................kono nirdharito na hoye akadhitkoption thakai aitai Null option.

2.4 (Dynamic type)
note: Javascript akti Dynamic Type language.

let name = 'John';
typeof(name);...........nam bijhanote aita--String type

let name = 2;
typeof(name);...........songsa bojhanote aita--Number type

results: name word ta akjaigai Sting typr abar onno jaigai Number type use hosse bolai aita--Dynamic type.
        aijonnei Javascript hosse Dynemic type language.

note: ekhane "typeof" nije akti keyword, not a veriable.

2.5 (Object)

A type- Normal
let person = {
name: 'Mosh',
age: 30            (Ekhane last a kono semiclone home nah)
};
console.log(person);

B type-
let person = {
name: 'Mosh',
age: 30
};
person.name = 'John';......ekhaner output a Mosh nah asey John Asbe. majhe DOt thakai ai style er nam Dot Notation.
console.log(person);

C ype-- Nijer Banano
let person = {
name: 'Mosh',
age: 30
};
person.name = 'John';
person.name = 'Kabir';
person.name = 'Bro';......ekhan theke bojha jai j console er opor last j nam thake just oitai show kore.
console.log(person);

D type--
let person = {
name: 'Mosh',
age: 30
};
person.name = 'John';
person.name = 'Kabir';
person['name'] = 'Bro';....aitao c type er motoi just ekhane Bracket Notation use hise. r akta bihoi lokkho kora jai, Dot & Bracket Notation Aksathe us ekor ajai. t
console.log(person);       tobe last a jyta thake sytai show hoi.

2..6 (Arary)

last.A
let selectedColor = ['red', 'green'];
console.log(selectedColor);

Type.B
let selectedColor = ['red', 'green'];
console.log(selectedColor.length);..........aita emon gonona kore j mot koit a metarial ache.
                                            ekhane lelth hosse akta prototype.
last.C
let selectedColor = ['red', 'green'];
console.log(selectedColor[1]);

last.D
let selectedColor = ['Red', 'green'];......Color ghulo non case-sensetive.
selectedColor[2] = 'Blue';....ekhane blue er jaigai j kono number dile, sei number e output a uthbe.
console.log(selectedColor);

note: [2]...aita asole 2 number obostan nirdesh kore. 0 number Red, 1 number green, 3 number blue.
alra [10] dile [10] number oobostane Blue dekhabe r majher 7 ti empty file dekhabe.
























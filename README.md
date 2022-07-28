# Day-3-json


1) For the given JSON iterate over all for loops (for, for in, for of, forEach)
Answer:
let students={"name":"abc", "age":23, "gender":"male"};
//For in loop
for(let g in students){
    console.log(g+" "+students[g]);
 }

 let students=[{"name":"abc", "age":23, "gender":"male"}];
//For loop
for(let i=0;i<students.length;i++){
console.log(students[i]);
}

For of loop
for(let j of students){
console.log(j);
}


Foreach loop
students.forEach(add)
function add(c){
    c.location="chennai";
    console.log(c);
}

2) Create your own resume data in JSON format
Answer:
let resume={
    "name":"Aruna Devi B", 
    "companyName":"ICICI BANK LTD",
    "Designation": "Assistant Manager",
    "Experience":"2 years",
    "Educational qualification":"B.Sc",
    "Skills":["Time management", "Leadership", "Team work"],
    "Certificates":["AMFI","IRDAI","Praveen Poorvardh"],
    "Marks":{"Maths":80,"Physics":100},
    "Languages": ["Tamil","English","Hindi"],
    "pincode": 626123,
    "isGraduated": true
    }
    for(let j in resume){
        console.log(j+":"+resume[j]);
    }

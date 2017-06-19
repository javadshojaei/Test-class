class Student{
    constructor(n,f,i){
    this.Name = n ;
    this.Family = f ;
    this.ID = i ;
}
    addname(){

        console.log('ok');
            }
}

class MaleStudent extends Student {

    AddGender1(){

        console.log('The Male Student ');
        super.addname();
    }

}

class FemelStudent extends Student {

    AddGender2(){

        console.log('The Femel Student');
        super.addname();
    }
}
var St1 = new Student('Ali','Alizadeh',1234);
var St2 = new Student('Zahra','Ahmadi', 2314);
var St3 = new MaleStudent();
var St4 = new FemelStudent();

var Id = 2;

if (Id == 1) {

    console.log('Name :' + St2.Name);
    console.log('Family : ' + St2.Family);
    console.log('Studnet ID : ' + St2.ID);
    St4.AddGender2();
} else {
    console.log('Name :' + St1.Name);
    console.log('Family : ' + St1.Family);
    console.log('Studnet ID : ' + St1.ID);
    St3.AddGender1();

}

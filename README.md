# dailytask6
https://github.com/rvsp/typescript-oops/blob/master/Practice/Movie.md
class movies{
constructor(tittle="",studio="",rating=""){
this.tittle=tittle;
this.studio=studio;
this.rating=rating||"PG";

}
getpg(data=[]){
return data.filter((d)=>d.rating==="PG")
}}
let movieutils=new movies();
let moviearray=[
new movies("ps","VA filims",null),
new movies("Casino Royale","Eon Productions","PG13")
] ;
console.log(movieutils.getpg(moviearray))
2.Write a “person” class to hold all the details.
class person {
constructor(name,age,gender){
this.name=name;
this.age=age;
this.gender=gender;
}

  introduce() {
    console.log(`Hi, my name is ${this.name}. I am ${this.age} years old and identify as ${this.gender}.`);
  }

}
let per1=new person("jayaprakash",23,"male")
per1.introduce();
3.write a class to calculate the uber price.
    this.baseFare = baseFare;
    this.costPerMinute = costPerMinute;
    this.costPerMile = costPerMile;
  }

  calculatePrice(distance, duration) {
    const price = this.baseFare + (this.costPerMinute * duration) + (this.costPerMile * distance);
    return price;
  }
}

const calculator = new UberPriceCalculator();
const totalPrice = calculator.calculatePrice(12, 10);
console.log(`The total price for the Uber ride is $${totalPrice}`);




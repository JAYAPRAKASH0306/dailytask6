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

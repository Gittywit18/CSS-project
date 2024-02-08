:root{
    --ff-poppins: 'Poppins', sans-serif;

}

*{
    background-color: #172937;
}
.main {
 display: grid;
 justify-content: flex-start;
 background-color:#172937;
}
.on {
 grid-column: 1/2;
 grid-row: 1/5;
 height: 800px;
 top: 40px;
 position: sticky;
 border-radius: 2cap;
 margin-top: 50px;
 margin-right: 10px;
 margin-left: 150px;
 margin-bottom: 30px;
 background-color: #253644;
 max-width: 300px;
 justify-content: center;
}
.up {
    grid-column: 2 / 6;
    grid-row: 1/5;
    margin: 10px;
    border-radius: 2cap;
    margin-top: 50px;
    height: 1400px;
    margin-right: 30px;
    margin-left: 30px;
    width: 870px;
    background-color: #253644;
}
.image {
    position: relative;
    margin:60px;
    border-radius: 2cap;
    margin-bottom: 30px;
    background-color: aliceblue;
    height:150px;
    width: 150px;
}
h1{ 
    background-color: #253644;
    text-align: center;
    color: white;
    font-size: 35px;
}
h4 {
 align-items: center;
 text-align: center;
 text-decoration: dashed;
 margin-left: 30px;
 margin-right: 30px;
 padding: 5px;
 font-size: 16px;
 border-radius: 1cap;
 color: white;
}
hr {
    background-color: red;
}
.a{
    position: relative;
    display: grid;
    height:50px;
    background-color:#253644;
    margin-bottom:20px;
}
.b{
    position: relative;
    display: grid;
    height:50px;
    background-color:#253644;
    margin-bottom:20px;
}
.c{
    position: relative;
    display: grid;
    height:50px;
    background-color: #253644;
    margin-bottom:20px;
}
.d{
    position: relative;
    display: grid;
    height:50px;
    background-color: #253644;
    margin-bottom:20px;
}
.icons img{
    width: 35px;
    height: 35px;
    border-radius: 1cap;
    margin:10px;
    background-color: #253644;
}
.icons p{
    grid-column: 2/4;
    margin: 5px;
    width: fit-content;
    color:white;
    margin-left: 2px;
    background-color:blue;
}
.Heading{
     text-align: flex-start;
     width: fit-content;
     margin:40px;
     margin-bottom: 20px;
}
.a span {
   margin-bottom: 10px;
   text-align: start;
    background-color:#253644;
    color:hsla(0, 0%, 84%, 0.7);

}
.b span {
    background-color: #253644;
    color:hsla(0, 0%, 84%, 0.7);
    text-align: start;
}
.c span {
    background-color: #253644;
    color:hsla(0, 0%, 84%, 0.7);
}
.d span {
    background-color: #253644;
    color: hsla(0, 0%, 84%, 0.7);
}
.up aside{
    background-color: #f37021;
    margin-left: 40px;
    margin-top: 10px;
    width: 50px;
    height: 6px;
    border-radius: 1.5cap;
}
.up p{
    background-color: #253644;
    margin:40px;
    margin-top: 10px;
    line-height: 1.4;
    font-size: 17px;
    color:hsl(0, 0%, 84%);
   
}
html{
    font-family: var(--ff-poppins);
}
h2{
    text-align: start;
    margin: 40px;
    margin-bottom: 10px;
    background-color: #253644;
    color: white;
    font-size: 26px;
}
.fields{
    display: grid;
    background-color:#253644;
    margin: 30px;
    margin-top: 8px;
    grid-template-columns: 400px 400px;
}
.fields > div{
    height: 170px;
    margin: 30px;
    justify-content: space-around;
    margin-bottom: 10px;
    border-radius: 1.5cap;
}
h3{
    text-align: start;
    margin-left: 40px;
    margin-bottom: 10px;
    font-size: 21px;
    color: white;
}
.image img {
    border-radius: 2cap;
    margin:0px;
    height: 150px;
    width: 150px;
}
.testimonials {
    display: grid;
    grid-template-columns: 415px 415px;
    background-color:#253644;
    margin: 30px;
    justify-content: space-around;
    margin-right: 15px;
    margin-left: 15px;
    margin-top: 8px;
}
.testimonials > div {
    height: 350px;
    margin-top: 20px;
    margin-right: 10px;
    margin-left: 10px;
    margin-bottom: 10px;
    border-radius: 1.5cap;
}
.testimonials img{
    margin: 20px;
    height: 250px;
    width: 350px;
}
iframe{
    margin: 20px;
    height: 253px;
    width: 350px;
}
.testimonials h3{
    margin-left: 20px;
}
.name{
    font-size: 30px;
}
p a{
    background-color: #253644;
    color: white;
    font-size: 15px;
    text-decoration: none;
}
.handles{
    display: flex;
    justify-self: center;
    justify-content: center;
    align-items: center;
    margin: 40px;
    margin-top: 0px;
    margin-left: 75px;
    background-color:#253644;
    width: 100px;
    height: 30px;
}
.handles img{
    height: 22px;
    margin: 10px;
    background-color: #253644;
    width: 22px;
}
.handles a{
    background-color: #253644;
}
.handles a:hover{
  opacity: 0.5;
  transition: 0.3s;
}
.fields h3{
    font-style: oblique;
    text-decoration:underline;
}
.fields h3:hover{
    cursor: pointer;
}
.testimonials img:hover{
    cursor:pointer;
}

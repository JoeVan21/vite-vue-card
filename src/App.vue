img{
  max-width: 400px;
}
button {
  cursor:pointer;
  margin: 1px;
  border: 2px dashed blue;
  color:#00FFFF; 
  background-color: black;
  border-radius:20px;
 text-transform: uppercase;
padding: 8px 8px;
}
.card {
  font-size: 15px;
  margin: 5px;
  padding: 10px;
  text-align:center;
  border: solid blue 10px;
  padding: 8px;
  max-width: 400px;
}
.borders {
 justify-content:center;
  display:flex;
}
button:hover{
  background-color: #0400FE;
}

button:focus{
  background-color: #0400FE;
}


@media screen and (min-width:501px) and (max-width:800px) {

}
@media screen and (max-width:500px) {
  .card{
    font-size: 3vw
  }
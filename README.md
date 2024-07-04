:root{
    --cor-fundo : rgb(29, 28, 28);
    --cor-primaria : rgb(255, 255, 255);
--cor-hover : rgb(38, 63, 63);

}
.dp-menu  {
    list-style-type: none;
    padding: 0%;
}
.dp-menu ul {background-color: VAR(--cor-fundo);

}
.dp-menu ul li{
display: inline;
position: relative;
}


.dp-menu ul li a{
 color:  var(--cor-primaria);
 text-decoration: none;
 display: inline-block;
 padding: 10px;
 color: border  white;
top: 10px;
    
}

.dp-menu ul li a:hover{
    background-color:  var(--cor-hover);
          
   }
   /*sub menu*/
   .dp-menu ul ul {
    display: none;
    left: 0;
    position: absolute;
   }
   .dp-menu ul  li:hover ul {
    display: block;
   
   }

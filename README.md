#  DSW1-Prova1-Ana Paula Souza Silva.
/*
Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
Click nbfs://nbhost/SystemFileSystem/Templates/ClientSide/css.css to edit this template
*/

.container{
    width:100%;
    height:100%;
    display:flex;
    flex-direction: row;
    position: absolute;
   }
body
{
    width: 100%;
    height:100%;
}
.container>div:nth-child(1){
    color: white;
    width:20%;
    height:100%;     
    background: navy; 
    text-align: center;
    vertical-align: middle;
    display:flex;
    align-items: center;
    justify-content: center;
    animation: azul 1s linear;
}


.container>div:nth-child(2){ 
    color: white;
    width:20%;
    height:100%;
    background: teal;
    text-align: center;
    vertical-align: middle;
     display:flex;
     align-items: center;
    justify-content: center;
    animation: azulclaro 1s linear;
}

.container>div:nth-child(3){
    color: white;
    width:20%;
    height:100%;
    background:purple;
    text-align: center;
    vertical-align: middle;
    display:flex;
    align-items: center;
    justify-content: center;
    animation: roxo 1s linear;
}

.container>div:nth-child(4){
    color: white;
    width:20%;
    height:100%;
    background:olive;
    text-align: center;
    vertical-align: middle;
    display:flex;
   align-items: center;
    justify-content: center;
    animation: bege 1s linear;
}

.container>div:nth-child(5){
   color: white;
    width:20%;
    height:100%;
    background:red;
    text-align: center;
    vertical-align: middle;
    display:flex;
    align-items: center;
    justify-content: center;
    animation: vermelha 1s linear;
}

  @keyframes azul {
      0%{ transform: translatex(-100%);  
       }
       100%{
           transform:translatex(0%);
       }
   }
   @keyframes azulclaro {
      100%{ transform: translatey(0%);  
       }
       0%{
           transform:translatey(100%);
       }
   }
   @keyframes bege {
      100%{ transform: translatey(0%);  
       }
       0%{
           transform:translatey(100%);
       }
   }
   @keyframes vermelha {
      0%{ transform: translatex(100%);  
       }
       100%{
           transform:translatex(0%);
       }
   }
   @keyframes roxo {
     0%{ transform: translatey(-100%);  
       }
      100%{
           transform:translatey(0%);
       }
   }
   
   @media(max-width:760px){
      .container{
    width:100%;
    height:100%;
    display:flex;
    flex-direction: column;
    position: absolute;
   }
     .container> div:nth-child(1){
    width: 100%;
    flex-direction: column;
   
     }
      .container> div:nth-child(2){
    width: 100%;
    flex-direction: column;
    
     }
     .container> div:nth-child(3){
    width: 100%;
    flex-direction: column;
   
     }
     .container> div:nth-child(4){
    width: 100%;
    flex-direction: column;
   
     }
     .container> div:nth-child(5){
    width: 100%;
    flex-direction: column;
   
     }
   }
   
   

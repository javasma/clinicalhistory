<template>
    <div id="HistoryView" class="historyView">
        <div class="header1">   
        </div>
         <div class="description">
            <h2>Bienvenido a su historia clínica ONline!</h2>
            <p>Revise toda su trazabilidad clínica en un solo lugar y descarguela cuando requiera.</p>
        </div>
      </div>
       
</template>

<script>

export default{

    name:"HistoryView",

    data: function(){
        return{
            user_in: {
                username:"jeison colme",
                password:"Gloria123",
            }
        }
    }
}
</script>

<style>
    .auth_user{
        margin: 0;
        padding: 0%;
        height: 100%;
        width: 50%;
        background-image: url("Fondo.jpg");
        display: flex;
        justify-content: center;
        align-items: center;

    }

    .container_auth_user {
        border: 3px solid  #283747;
        border-radius: 10px;
        width: 25%;
        height: 60%;
        
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .auth_user h2{
        color: #283747;

    }

    .auth_user form{
        width: 100%;
        
    }

    .auth_user input{
        /* height: 40px;
        width: 100%; */

        box-sizing: border-box;
        padding: 10px 20px;
        margin: 5px 5px;

        border: 1px solid #283747;
        
    }

    .auth_user button{
        width: 100%;
        height: 40px;

        color: #E5E7E9;
        background: #283747;
        border: 1px solid #E5E7E9;

        border-radius: 5px;
        padding: 10px 25px;
        margin: 5px 0;
    }

    .auth_user button:hover{
        color: #E5E7E9;
        background: crimson;
        border: 1px solid #283747;
    }
</style>
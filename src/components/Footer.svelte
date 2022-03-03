<div id='background'>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap" rel="stylesheet">  
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Arimo:wght@500&display=swap" rel="stylesheet">
    <div id='footer-top'> 

        <h1><h1><h1>GOLF</h1></h1></h1> 
         
        <div id='form'>
            <h1>Newsletter</h1>
            <div id='fields'>
                <input type="text" placeholder="EMAIL ADDRESS">       
                <select name="state" id="">
                    <option>CHOOSE YOUR STATE</option>
                    <option value="CA">CA</option>
                    <option value="CT">CT</option>
                </select>
                <button>CHOOSE WHICH EMAILS YOU WANT</button> 
            </div>
        </div>
    </div> 

    <div id='footer-bottom'>

        <div id='categories'> 
            
            <ul>
                <h1>Categories</h1>
                <li>NEWS</li>
                <li>INSTRUCTION</li>
                <li>GEAR</li>
                <li>LIFESTYLE</li>
                <li>TRAVEL</li>
            </ul>
        </div>


        <div>
             
            <ul>
                <h1>Services</h1>
                <li>DO NOT SELL MY INFORMATION</li>
                <li>CUSTOMER SERVCICE</li>
                <li>GOLF MEDIA KIT</li>
                <li>MASTHEAD</li>
                <li>FAQ & RETURNS</li>
            </ul>
        </div>


        <div>
            <ul>
                <h1>Social</h1>
                <li>Facebook</li>
                <li>Twitter</li>
                <li>Instagram</li>
                <li>YouTube</li>
            </ul>
        </div>


        <div>
            <ul>
                <h1>Magazine</h1>
                <img src="img/magazine.png" alt=""> 
            </ul>
        </div>
        
    </div> 
</div>

<style>

    h1 {
        font-family: 'Abril Fatface';
        margin-bottom: 15px;
    }

    #background {
        padding-top: 65px;
        display: flex;
        flex-direction: column;
        background-color: rgb(1, 48, 40);
        color: whitesmoke;
    }

    #footer-top {
        justify-content: space-around;
        display: flex;
        flex-direction: row;
    }

    #form {
        padding-top: 30px;
        display: flex;
        flex-direction: column;
    }

    #fields {
        display: flex;
        flex-direction: row;
        margin: 5px;
        justify-content: space-around;
        align-items: center;
        padding-top: 20px;
    }

    input {
        height: 40px;
        margin: 5px;
        width: 250px;
        
    }

    button {
        height: 40px;

       background-color: #e4a505;
       width: 250px;
    }

    select {
        height: 40px;
        width: 250px;
        margin: 10px;
    }

    #footer-bottom {

        margin-top: 100px;
        margin-bottom: 100px;
        display: flex;  
        justify-content: space-around;
        flex-direction: row;  
    }

    #categories {
        color: whitesmoke;
    }

    li {
        list-style: none;
        font-family: 'Arimo', sans-serif;
        padding-top: 10px;
        
    }

    img {
        padding-top: 10px;
    }

</style>
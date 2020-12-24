
<html>
    <head>

    </head>
    <body>
         <h1> HTML Forms</h1>
         <p> An HTML forms  is used to collect user input. the 
             user input is most often sent to server for prossecing.
         </p>
         <h3> Example</h3>
         <form action="myfolder/" method="get">
             <lebel> This is radio button</lebel>
            <input type="radio"><br/>
            <lebel> This is for inputting text</lebel>
             <input type="text"><br/>
             <lebel> This is for chackbox</lebel>
             <input type="checkbox"><br/>
             <label> This is submit button</label>
             <input type="submit"><br/>
             <lebel> This is button </lebel>
             <input type="button"><br/>

              <h2> Let's try some example of radio button</h2>
              <input type="radio" name="gender" >
              <lebel> Male</lebel>
              <input type="radio" name="gender" >
              <lebel> Female</lebel>
              <h1> This is for how create a chackboox</h1>
              <input type="checkbox">
              <lebel> I have a bike</lebel>
              <input type="checkbox" name="checkbox" value="vickle">
              <lebel>  I have a car</lebel> 
              <input type="submit">
              <h1> The select properties </h1>
              <select size="3">
                  <option> volvo</option>
                  <option> maruti</option>
                  <option selected> Ambasater</option>
              </select>
              <input list="browsers">
              <datalist id="browsers">
                  <option> Internet</option>
                  <option> Explorer</option>
                  <option> Opara</option>
                  <option> Firefox</option>
              </datalist>
          <input list="browsers">
         </form>
    </body>
</html>

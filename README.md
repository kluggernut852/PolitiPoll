<html>
    <head>
        <title>Phun with Polls</title>
        <meta charset="UTF-8">
        <style>
            body {
                background-color: blanchedalmond
            }
        </style>
        <script>
        // get data from form
        var formData = document.getElementById("daPoll");
        var partyOutput = "Your selected party is " + demParty
        var repParty = ["Trump", "Marco", "Carson", "Cruz", "McConnell", "Bush"];
        var demParty = ["Hillary", "Bernie", "Feinstein", "Brazille", "Schumer"];
        var repeatedOutput = repeatText(partyOutput, );
        document.getElementById("daPoll").outputField.value = repeatedOutput;
//        var repOne = "Trump";
//        var repTwo = "Marco";
//        var repThree = "Carson";
//        var repFour = "Cruz";
//        var repFive = "McConnell";
//        var demOne = "Hillary";
//        var demTwo = "Bernie";
//        var demThree = "Feinstein";
//        var demFour = "Brazille";
//        var demFive = "Schumer";
          function repeatText(text, ){
            var repeatedText = "";
            while(numRepeats > 0){
                repeatedText = repeatedText + text + " \n";
                numRepeats--;
                }
            return repeatedText;
          }

        </script>
    </head>
    <body>
      <h1>Welcome to the Politi-Poll!</h1>
        <form id="daPoll">
        <p>Enter your name: <input type="text" name="userName" value=""></p>
        <p><textarea name="outputField" rows="10" kols="40"></textarea></p>
        <p><input type="button" value="Your Political Party" onclick="demParty"</p>
        <p id="output"></p>
        </form>

    </body>
</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" />
    <title>Count Likes</title>
</head>
<style>
    .button {
        background-color: #4CAF50;
        /* Green */
        border: none;
        color: white;
        padding: 16px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        transition-duration: 0.4s;
        cursor: pointer;
    }
    
    .button1 {
        background-color: #f44336;
        color: white;
        border-radius: 20px;
        margin-bottom: 25px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }
    
    .button1:hover {
        background-color: #008CBA;
        color: white;
    }
    
    .counterStat {
        color: white;
        font-size: 16px;
    }
</style>

<body>

    <div class="CountLike" id="Like Count">
        <button class="button button1"><i class="fa fa-heart"></i> Like <span class="counterStat">...</span></button>
    </div>

    <!-- findfull article at https://tech.pathgriho.com/2021/06/like-button-using-javascript-firebase.html -->

    <!-- Firebase script -->
    <script src="https://www.gstatic.com/firebasejs/3.6.5/firebase.js"></script>

    <!-- Initialize Firebase -->
    <script>
        var config = {
            apiKey: "Paste Your API Key provided by Firebase",
            authDomain: "Paste Your authDomain provided by Firebase",
            databaseURL: "Create a database and then paste the url of that database here",
            storageBucket: "Paste Your storageBucket provided by Firebase",
            messagingSenderId: "Paste Your messagingSenderId provided by Firebase"
        };
        firebase.initializeApp(config);
    </script>

    <script type="text/javascript">
        var dCounters = document.querySelectorAll('.CountLike');
        [].forEach.call(dCounters, function(dCounter) {
            var el = dCounter.querySelector('button');
            var cId = dCounter.id;
            var dDatabase = firebase.database().ref('Like Number Counter').child(cId);

            // get firebase data
            dDatabase.on('value', function(snap) {
                var data = snap.val() || 0;
                dCounter.querySelector('span').innerHTML = data;
            });

            // set firebase data
            el.addEventListener('click', function() {
                dDatabase.transaction(function(dCount) {
                    return (dCount || 0) + 1;
                });
            });
        });
    </script>

</body>

</html>

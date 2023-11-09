<!DOCTYPE html>

<html>
    <head>
        <link rel="stylesheet" href="./styles/Home.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>

        <section id="Header">
            <div class="ott-heading">
                <h1>OTT Platform Analysis Tool</h1>
            </div>
        </section>

        <section id="OTT">
            <div class="ott-flex">
                <div class="ott-left">
                    <video src="Netflix.mp4" autoplay muted loop></video>
                </div>
                <div class="ott-right">
                    <h2>Netflix</h2>
                    <a href="Netflix.html">Click for Analysis<i class="fa fa-long-arrow-right"></i></a>
                </div>
            </div>
            <div class="ott1-flex">
                <div class="ott1-left">
                    <h2>Prime Video</h2>
                    <a href="Prime.html">Click for Analysis<i class="fa fa-long-arrow-right"></i></a>
                </div>
                <div class="ott1-right">
                    <video src="Prime.mp4" autoplay muted loop></video>
                </div>
            </div>
            <div class="ott2-flex">
                <div class="ott2-left">
                    <video src="Hotstar.mp4" autoplay muted loop></video>
                </div>
                <div class="ott2-right">
                    <h2>Disney+ </h2><h2>Hotstar</h2>
                    <a href="Hotstar.html">Click for Analysis<i class="fa fa-long-arrow-right"></i></a>
                </div>
            </div>
        </section>

        <div id="chat-btn">
            <h2>Hi Click on me to find a good movie</h2>
        </div>

        <script>
            window.watsonAssistantChatOptions = {
                integrationID: "c20abc07-86a8-4e20-a221-73dc60a89fb5", // The ID of this integration.
                region: "eu-gb", // The region your integration is hosted in.
                serviceInstanceID: "e4583f03-543d-4d71-9f0f-0860401323c2", // The ID of your service instance.
                onLoad: function(instance) { instance.render(); }
              };
            setTimeout(function(){
              const t=document.createElement('script');
              t.src="https://web-chat.global.assistant.watson.appdomain.cloud/loadWatsonAssistantChat.js";
              document.head.appendChild(t);
            });
          </script>
    </body>
</html>

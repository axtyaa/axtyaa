<body>
<h1 align="center">Hi 👋, I'm axtyaa</h1>

<h1 align="center">Languages & Tools</h1>
<p align="center">
    <img src="https://skillicons.dev/icons?i=github,ps,ai,visualstudio,javascript,java&perline=7"/>
</p> <br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=axtyaa&show_icons=true&theme=radical" /> 
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=axtyaa&theme=tokyonight&hide_border=true" />
</div>

</body>

<div class="headers-container second-side">
    <script>
      function fetchHeartbeat() {
        const userId = '964828677311455262';
        fetch(`https://api.lanyard.rest/v1/users/${userId}`)
              .then(response => {
              if (!response.ok) {
          throw new Error('Network response was not ok');
        }
        return response.json();
      })
        .then(data => {
          console.log(data);
          const dataContainer = document.getElementById('data-container');
          dataContainer.innerHTML = JSON.stringify(data, null, 2);
        })
          .catch(error => {
          // handle the error
          console.error(error);
          const errorMessage = 'No data to show.';
          document.getElementById('error').textContent = errorMessage;
        });
        }
          // Trigger heartbeat fetch request every 0,969 second
          setInterval(fetchHeartbeat, 969000);
    </script>
         <div class="wrapper">
            <div class="box box1"></div>
            <img src="https://lanyard.cnrad.dev/api/964828677311455262?&amp;bg=222834&amp;idleMessage=I&#x27;m not doing anything right now." alt="Discord Live Activity Presence" width="100%" height="100%">
           </div>   
                    <div class="headers-text-wrap">
                      <div class="headers-text-orders  headers-text-resize-container">
                        <!-- Header 1 -->
                        <div data-aos="fade-up">
                      </div>
                      <div class="header-spacer" data-text-exist="true" data-action-exist="false">
                      </div>
                    </div>
                  </div>
                </div>

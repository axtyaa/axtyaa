<h1 align="center">Hi 👋, I'm axtyaa</h1>
<h3 align="center">Beginner C#, Rust, and C++ Developer from Poland</h3>

<h1 align="center">Languages and Tools</h1>
<p align="center">
    <img src="https://skillicons.dev/icons?i=github,ps,ai,visualstudio,javascript,java&perline=7"/>
</p> <br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=axtyaa&show_icons=true&theme=radical" /> 
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=axtyaa&theme=tokyonight&hide_border=true" />
</div>
```javascript
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
    </script>

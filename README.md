<h1 align="center">Hi 👋, I'm Mate beridze</h1>
<h3 align="center">A passionate frontend developer from Georgia</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=beridzemate&label=Profile%20views&color=0e75b6&style=flat" alt="beridzemate" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=beridzemate" alt="beridzemate" /></a> </p>

- 🔭 I’m currently working on [https://github.com/beridzemate/ModernWeb-app.git](https://github.com/beridzemate/ModernWeb-app.git)

- 🌱 I’m currently learning **gsap,Material ui,ui/ux design**

- 👯 I’m looking to collaborate on [https://github.com/beridzemate/react-threads.js.git](https://github.com/beridzemate/react-threads.js.git)

- 👨‍💻 All of my projects are available at [https://github.com/beridzemate?tab=repositories](https://github.com/beridzemate?tab=repositories)

- 📫 How to reach me **mateberidze464@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/https://www.facebook.com/profile.php?id=100069011828281" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="https://www.facebook.com/profile.php?id=100069011828281" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<script>
    // Define the API endpoint
    const apiUrl = "https://api.restful-api.dev/objects/4";

    // Function to fetch data from the API
    async function fetchData() {
      try {
        const response = await fetch(apiUrl);

        // Check if the response is successful
        if (!response.ok) {
          throw new Error(`HTTP error! Status: ${response.status}`);
        }

        
        const data = await response.json();

        // Display the data in the HTML
        const objectDataDiv = document.getElementById("object-data");
        objectDataDiv.innerHTML = `
          <h2>Object ID: ${data.id}</h2>
          <p><strong>Name:</strong> ${data.name}</p>
          <p><strong>Description:</strong> ${data.description || "N/A"}</p>
          <p><strong>Type:</strong> ${data.type}</p>
        `;
      } catch (error) {
        // Handle errors
        console.error("Error fetching data:", error);
        document.getElementById("object-data").innerHTML = `<p>Error loading data. Please try again later.</p>`;
      }
    }

    // Call the function to fetch data when the page loads
    fetchData();
  </script>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=beridzemate&" alt="beridzemate" /></p>


<h1 align="center">
  Welcome 🙏, I'm Narendra Bariha </h1>
<h3 align="center">A passionate Data Science from India</h3>



- 🌱 I’m currently learning **Python, Tableau, SQL, Advance Excel, PowerBI, Machine Learning, Deep Learning, NLP, Artificial Intelligence.**


<table width="100%">
  <tr>
    <td align="left">
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=narendrabariha&show_icons=true&locale=en&layout=compact&theme=vision-friendly-dark" height="150" alt="Top Languages"/>
    </td>
    <td align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=narendrabariha&show_icons=true&locale=en&theme=vision-friendly-dark" height="150" alt="GitHub Stats"/>
    </td>
    <td align="right">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=narendrabariha&theme=vision-friendly-dark" height="150" alt="GitHub Streak"/>
    </td>
  </tr>
</table>





| ![narendrabariha GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=narendrabariha&bg_color=121212&color=9e9e9e&line=D1C4E9&point=9575CD&title_color=9e9e9e&area_color=673AB7&hide_border=true&area=false&radius=0) |
| :-------------------------------------------------------------------------------------------------------------------------------------------: |  

- 📫 How to reach me
 **narendrabarihan@gmail.com**



<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/narendra bariha" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="narendra bariha" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/narendra-bariha/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="narendra bariha" height="30" width="40" /></a>
</p>

<h2 align="center"> Languages & Tools</h2>

<p align="center">
  <!-- Programming Languages -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>

  <!-- Data & BI Tools -->
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" alt="Tableau"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white" alt="Excel"/>

  <!-- AI & ML Technologies -->
  <img src="https://img.shields.io/badge/Artificial%20Intelligence-FF6F00?style=flat-square&logo=openai&logoColor=white" alt="AI"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-007396?style=flat-square&logo=scikitlearn&logoColor=white" alt="Machine Learning"/>
  <img src="https://img.shields.io/badge/Deep%20Learning-FF0000?style=flat-square&logo=pytorch&logoColor=white" alt="Deep Learning"/>
  <img src="https://img.shields.io/badge/NLP-5A5A5A?style=flat-square&logo=google&logoColor=white" alt="Natural Language Processing"/>
  <img src="https://img.shields.io/badge/GenAI-663399?style=flat-square&logo=chatbot&logoColor=white" alt="Generative AI"/>

  <!-- Web Technologies -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"/>
</p>







Counting of visitors to this page

<a href="http://s01.flagcounter.com/more/ap7"><img src="https://s01.flagcounter.com/countxl/ap7/bg_FFFFFF/txt_000000/border_CCCCCC/columns_8/maxflags_250/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>

<p align="center"> <b>Thanks for visiting<b> 
<br>
  <img src="https://profile-counter.glitch.me/{narendrabariha}/count.svg" alt="narendrabariha" />
</p>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced Visitor Counter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        #counter {
            font-size: 24px;
            font-weight: bold;
            color: #673AB7;
        }
        .visitor-info {
            margin-top: 20px;
            font-size: 16px;
            color: #333;
        }
    </style>
</head>
<body>

    <h1>Website Visitor Counter</h1>
    <p>Total Visitors: <span id="counter">Loading...</span></p>

    <div class="visitor-info" id="visitor-info">Fetching visitor details...</div>

    <script>
        // Function to get and update visitor count
        function updateVisitorCount() {
            let count = localStorage.getItem("visitorCount");
            if (!count) {
                count = 1;
            } else {
                count = parseInt(count) + 1;
            }
            localStorage.setItem("visitorCount", count);
            document.getElementById("counter").textContent = count;
        }

        // Function to fetch visitor details using an API
        async function fetchVisitorDetails() {
            try {
                let response = await fetch("https://ipapi.co/json/");
                let data = await response.json();
                let visitorInfo = `You are visiting from ${data.city}, ${data.country_name}`;
                document.getElementById("visitor-info").textContent = visitorInfo;
            } catch (error) {
                document.getElementById("visitor-info").textContent = "Unable to fetch visitor details.";
            }
        }

        // Initialize functions
        updateVisitorCount();
        fetchVisitorDetails();
    </script>

</body>
</html>

